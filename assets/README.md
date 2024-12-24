
    PROJECT: LC-Project-management-tool
   -------------------------------------
     taskwarrior based task management
=============================================

I) supporting scripts: 
   
	1) lc-task:
		- Provides an more efficent way to manage tasks
		- then current cli taskwarrior version
	2) lc-tasknote:
		- adds a note to each task created and adds a UUID to the note
	3) lc-lock:
		- locks screen and displays panding tasks
		- planned: record all bash commands ever executed
		- parse required info eg:
	    a) last three commands including vim and or nvim
		   to establish three last edited documents and add to taskwarrior programmaticaly
		   thus when screen lock is activated by idle state, it will be displayed on screen
		b) 
II) lc-task todos

	a) Center the highlighted text
	b) Change Color
	a) Functions to add:
		1. countdown on tasks of the day
		2. dayplanner
		3. merge 2 templates after editing programatically as 
		   2 text blockes togather and save as one file
		4. xxx
	
	
III) taskwarrior directory tree structure

.
├── assets
│   ├── lc-lock
│   ├── lc-task
│   ├── lc-tasknote
│   └── README.md
├── backlog.data
├── completed.data
├── hooks
├── notes  (lc-tasknote creates this directory to store and retrive any 
            task related notes, which are named according to their respective UUID)            
├── pending.data
├── undo.data
└── variables

4 directories, 10 files

	




