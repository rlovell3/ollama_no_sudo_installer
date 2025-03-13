# ollama_no_sudo_installer
My personal ollama installer

I Use Linux exclusively.  The above script is a modification of the original ollama install script for Linux from about December 19th, 2024.  Their original may have changed by now.  

The purpose of the script is to install ollama into my local, user-permissioned account, without needing sudo permission.  I have spend a great deal of time setting up Nvidia GPUs along with CUDA and tons of other stuff, and I do not want anyone's installation scripts messing with anything to do with my existing setup.  So, the ollama script was chopped up and modified to install everything into a local directory within my /home/me directory space on the machine.  It also skips over the search for existing Nvidia and cuda info as those are already installed, complete with zsh environment variables and everything else I've put together on this machine. I don't want duplicates, and I don't need your script to do anything other than read the associated environment variables I've already got in place.   

Let's be clear:  although this script is being stored in a public Github repository, it is MY script that was designed for ME.  If you choose to use this script, it has an MIT license, just like the ollama source from whence it came.  It may not work on your machine at all.  So do yourself a favor.  If you want to use this script, examine it carefully and/or have an AI model give it a look, and only then decide if you need to modify it to suit your own needs.  I posted it here merely as a source of inspiration for those of you who are fed up with every goddamn app developer deciding they require sudo permission to put their stuff on my machine.  Take a stand, and start telling every one of them to change the way they approach installation.  

Good luck.
