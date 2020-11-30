# Boinc Load Balancer

This script manages how much CPU [BOINC client](https://boinc.berkeley.edu) is using and adjusts client settings to varying system load. It increases BOINC CPU utilization when the system load is lower than the target and increases when it's higher. It allows running the BOINC client without sacrificing system responsiveness under heavy loads.
