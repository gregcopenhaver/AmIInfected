




Requirements:
  + Yara exe
  + Yara Rule List
  + Output folder
 
 AMIINFECTED is a process enumerator/yara memory scanner.  Using GetProcessById and a set max fuzz point, it guesses all open processes and
 then runs YARA on all processes.



Executable  is located in bin/debug

Still a work in progress, so may or may not work on first try. Also, may or may not require administrator mode.

Word of warning: It's not very fast.  I mean, the process enumeration? 10,000 possible PIDs in 30 seconds.  But for the actual yara scanner,
it took around 25 minutes to run.


This also requires a bit of setup prior to running

