# Performance-evaluation-of-zigbee-based-on-ns2

You have to run this in an ubuntu based platform in the terminal using 
-> zigbee.scn: network topology in 3D
-> zigbee.tcl: network script written in tcl
-> thr_drop_delay.awk: eualuation script written in awk

How to
1.Please make sure zigbee_topology.scn and zibee.tcl are in the same folder. The simulation script is written for NS-2.34 with tcl8.4.
2.cd to the folder by terminal
3.run ns zigbee.tcl. This will generate the simulation results stored in the output file named “zigbee.tr”.
4.run awk -f thr_drop_delay.awk zigbee.tr to get the performance results.
5.run gnuplot and plot xxx.dat to get the figures of simulation results.
