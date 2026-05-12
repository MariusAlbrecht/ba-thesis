# A Future-proof and Microarchitecture-agnostic Approach to Collecting CPU Hardware Samples

This repo contains the code produced in my Bachelor's thesis. See the thesis itself. The implementation
isn't very good frankly.

Under thesis/ is the latex code for the thesis itself.
I used the Latex workshop VSCode extension to compile.

under code/ is the main calimitos.h header, which contains the main code for collecting samples.
And the cali_to_csv.py script, which converts Caliper cali output files to csv.

Under code/bench/ are the codes used for testing original mitos (bench/mitos) and the new implementation (bench/cali).

To use the code the user needs to have Caliper installed. For sample callback functionality my Fork of Caliper is required.
Both upstream Caliper, as well as my fork provide a spack package which is the recommended way to install them. 