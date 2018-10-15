[fullstack-nanodegree-vm](https://github.com/udacity/fullstack-nanodegree-vm)
=============

Common code for the Relational Databases and Full Stack Fundamentals courses

# [Usage](https://classroom.udacity.com/courses/ud088/lessons/3621198668/concepts/35960790720923)
##### Run the virtual machine!
Using the terminal, change directory using the command `cd fullstack/vagrant`, then type `vagrant up` to launch your 
virtual machine.

Once it is up and running, type `vagrant ssh`. This will log your terminal into the virtual machine, 
and you'll get a Linux shell prompt. When you want to log out, type `exit` at the shell prompt. 
To turn the virtual machine off (without deleting anything), type `vagrant halt`. 
If you do this, you'll need to run `vagrant up` again before you can log into it.

Now that you have Vagrant up and running type `vagrant ssh` to log into your virtual machine (VM). 
Change directory to the `/vagrant` directory by typing `cd /vagrant`. This will take you to the shared folder 
between your virtual machine and host machine.

##### Sharing files between the vagrant virtual machine and your home machine.
Be sure to change to the `/vagrant` directory by typing `cd /vagrant` before creating new files or pasting files 
that you want to be shared between your host machine and the VM.

# Set up
Run 
```bash
python database_setup.py
python lotsofmenus.py
python project.py
```

