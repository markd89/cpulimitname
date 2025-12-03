# cpulimitname
Script that will pass PID to cpulimit so that you don't have to know the PID to limit the process.

# dependencies

cpulimit (Debian: apt-get install cpulimit)

# usage

#limits process with name vm2 to 10% of CPU
cpulimitname -name "vm2" -limit 10 

#cancel cpulimit
cpulimitname -cancel -name "vm2"
