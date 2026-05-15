In next i have leaned about the processes
how to view processes using the "ps" and "ps aux" command.
how to use htop as a live dashboard.
how tofilter the processes using the 'pipe (|)' and 'grep' commands.
how to use "kill"- (kills the process after its execution) and "kill -9"- (kills the process imediatedly without letting the process to save the work) commands.
let me give a real-time use case of the above commands:
you got a phone call to see the problem arised on server that website is stopped working and asked you to resolve the issue.
now,you go to the terminal and type "ps aux --sort=-%cpu | head -10" command which view the top 10 processes which are filtered on their CPU usage.
and you see a rouge python script process which is eating up most of the memory.
now what you need to do is kill the process before it get even worse by using the "kill -9 process_id" command.
now the website runs smoothly.
