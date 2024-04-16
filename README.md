ktsuss-slackware
=======
*In this fork of the project, we introduced two key modifications to enhance functionality. First, we implemented the 'su -l' command to execute the given command with the environment variables of the target user, ensuring a more comprehensive and secure execution environment. Additionally, we incorporated a call to the 'tty_raw' function, enabling the program to operate in raw mode when interacting with the terminal, enhancing its responsiveness and usability. These changes improve the overall user experience and reinforce the security and robustness of the application.So the recent enhancements to the ktsuss application offer significant benefits to Slackware users seeking full root access. By incorporating the 'su -l' command, the application now executes commands with the complete environment variables of the target user, ensuring a more comprehensive root environment. Additionally, the integration of 'tty_raw' enables the application to operate in raw mode, enhancing both usability and security. These modifications empower Slackware users to utilize ktsuss confidently, knowing they can execute commands with full root privileges while maintaining a robust and secure operating environment.*


======

ktsuss stands for "keep the su simple, stupid", and as the name says, is a graphical version (frontend) of su written in C and GTK+ 2. The idea of the project is to remain simple and bug free.
======


