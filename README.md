# cpulimitname
Script that will pass PID to cpulimit so that you don't have to know the PID to limit the process.

# dependencies

cpulimit (Debian: apt-get install cpulimit)

# usage

Limit process with name vm2 to 10% of CPU:

$cpulimitname -name "vm2" -limit 10 

Cancel cpulimit on vm2

$cpulimitname -cancel -name "vm2"
