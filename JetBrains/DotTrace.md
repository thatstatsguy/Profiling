Here's instruction on how to run the profiler for the server/client. The most involved part of the process is getting the process ID from the Task manager and the script will do the rest. If you need to profile the Client then you'll obviously go and find the process ID for the client app.

Example of the text I used

`dottrace attach 1234 --save-to=snapshot.dtp --profiling-type=Timeline --timeout=30s`

Additional info on how to use and download
https://www.jetbrains.com/help/profiler/Performance_Profiling__Profiling_Using_the_Command_Line.html 
https://www.jetbrains.com/profiler/download/#section=commandline 