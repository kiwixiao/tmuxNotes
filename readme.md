Tmux personal notes
-----------------

# Welcome!
Thanks for reading this, all the info are original from internt and will be honoured if this helpful.
If there is any mistakes wecolme to pointed out.

# What is tmux?
tmux’s authors describe it as a terminal multiplexer. Behind this fancy term hides a simple concept: Within one terminal window you can open multiple windows and split-views (called “panes” in tmux lingo). Each pane will contain its own, independently running terminal instance. This allows you to have multiple terminal commands and applications running visually next to each other without the need to open multiple terminal emulator windows.

On top of that tmux keeps these windows and panes in a session. You can exit a session at any point. This is called “detaching”. tmux will keep this session alive until you kill the tmux server (e.g. when you reboot)2. This is incredibly useful because at any later point in time you can pick that session up exactly from where you left it by simply “attaching” to that session.

# How to use tmux as a beginner?

Here are some very basic commands to help you get started with tmux.

### tmux
if you type tmux in the command line. it will open a new session, the session name start from 0 as default.

### prefix (control+b) + d
this will allow you deattach from he current session, but this will not end the session.

### tmux ls
once deattched, if you want to find out how many seesion is in the backgroud, this command will show all the sessions deattched.

### tmux attach -t session-name
this command will help yuo re-attach to the seesion, depends on the session name given. The first default session name is: 0. Session name can be find out using tmux ls command.
    
### tmux new -s mysession
if you want to start a session with custmosied or meaningful name "mysession", this command will help you with this.

### tmux rename-session -t 0 newname
if you want to rename the current session with new name "newname".

    
