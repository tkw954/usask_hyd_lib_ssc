Pipeline Library
This library implements a Lumped Element Method hydraulic pipeline model for
Simscape.

These models divide the pipeline into a number of segments, with each 
segment comprised of a fluid resistance, inertance and compressible volume.

The "Segmented Pipeline" block models a pipe of constant diameter. It uses
the Simscape Foundation Library elements for the segments: the hydraulic 
resistance uses a Colebrook Equation model for laminar or turbulent flow
and the compressible volume includes a caviation model.

The "Shaped Segmented Pipeline" uses the same elements as the "Segmented
Pipeline", except the pipeline's diameter can change over its length, 
allowing for internally generated reflections. This shape is defined by a 
lookup table of diameters and lengths.

The "Linear Shaped Segmented" block is similar to the "Shaped Segmented 
Pipeline" except nonlinearities are removed.  Thus, the resistance is assumed
to be laminar and the compressible volume has a contrant bulk modulus
with no cavitation model.

This library is the work of Travis Wiens t.wiens@usask.ca.