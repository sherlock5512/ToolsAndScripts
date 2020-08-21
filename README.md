# Tools And Scripts

This Repository is a collection of all the Tools and Scripts that I have made.
Some more useful than others. Hopefully I'm not the only one who finds use for them.




## wgetshell 
 path: `Bash/wgetshell`  
 It takes links and downloads them, just paste them in!  
 Schedules the downloads in a non blocking manner.

 This script prompts you for URLs with the prompt `wget>`  
 Any link pasted in is added to a task spool to be downloaded  
 Due to using ts the input is not blocked while other files download  
 exits on empty input or (q/Q)
### Dependencies
 * Bash
 * Wget
 * ts/task-spooler (not in ___every___ distros repository):
[Source](https://github.com/sherlock5512/TaskSpooler "My GitHub Clone of the source")