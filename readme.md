Greetings!!

This is a fun little bash script that randomly selects a contry that your nordvpn client
can connect to, and makes that connection!!

___________
  Install
__________


Copy nvpnc into your script folder. I will use bin in this example.

	cp nvpnc ~/bin/nvpnc

Next, Change to that directory and make the file executable.

	cd ~/bin
	chmod +x nvpnc

If you have not setup for yout terminal to access your own scripts,
you will need to set that up.

Depending on the term you use, is what config file you will need to edit.

~/.bashrc is the default for most systems
~/.zshrc for Z-Shell
~/.tcshrc for TCSH
~/.kshrc for PDKSH

At the end of the file, add the following:

	export PATH="$HOME/bin:$PATH"

Save and restart your terminal.
