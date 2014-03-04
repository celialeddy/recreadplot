#Program for the record reading waveform plot
##Written by Ge Jin, ge.jin@ldeo.columbia.edu, jinwar@gmail.com
March, 2013

#Instruction: 

* On povel, change earthquake informaiton in sod.xml, Run: nohup sod -f sod.xml > log &
* Copy the folder with sac files into your laptop, copy everything of this program to the same folder (one level above sac files)
* Change the eventid in recread_sac2eventmat.m, modify the filters if necessary
* Run recread_sac2eventmat.m, it will generate a mat file: "eventid".mat
* Modify the phases you want to have in the cheatsheet in plot_recread.m. If the phase you interested is not in the database, use make_phasedb.m to add it.
* Load the matfile and then run plot_recread.m

Command list can be found in command_list.txt

TIP: You must restart your matlab if you plug or unplug a monitor to your computer.

Enjoy!

Jingle