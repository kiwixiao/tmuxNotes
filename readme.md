Tmux personal notes
-----------------

### Welcome!
Thanks for reading this, all the info are original from internt and will be honoured if this helpful.
If there is any mistakes wecolme to pointed out.

### What is tmux?
tmux’s authors describe it as a terminal multiplexer. Behind this fancy term hides a simple concept: Within one terminal window you can open multiple windows and split-views (called “panes” in tmux lingo). Each pane will contain its own, independently running terminal instance. This allows you to have multiple terminal commands and applications running visually next to each other without the need to open multiple terminal emulator windows.

On top of that tmux keeps these windows and panes in a session. You can exit a session at any point. This is called “detaching”. tmux will keep this session alive until you kill the tmux server (e.g. when you reboot)2. This is incredibly useful because at any later point in time you can pick that session up exactly from where you left it by simply “attaching” to that session.

### How to use tmux as a beginner?

Here are some very basic commands to help you get started with tmux.

*   tmux
if you type tmux in the command line. it will open a new session, the session name start from 0.
    by reading the [online tutorials](http://www.itksnap.org/pmwiki/pmwiki.php?n=Documentation.HomePage).
*   If you downloaded ITK-SNAP source code, please follow these [online
    instructions](http://www.itksnap.org/pmwiki/pmwiki.php?n=Documentation.BuildingITK-SNAP)
    to compile and build ITK-SNAP.
*   You will need a 3D image to use this software. Images with which ITK-SNAP
    is known to work are found on the [ITK-SNAP download page](http://www.itksnap.org/download/snap)
*   There are also materials (images, exercises, video) from training courses
    available on the [documentation page](http://www.itksnap.org/pmwiki/pmwiki.php?n=Documentation.SNAP3). 
