# -Project 1 Answers-

##Part 1:

(This was made assuming VirtualBox was used)
In order to create a guest os first you need to select new. Then create the name, location, and OS that you will be using. Now the RAM will need to be allocated. Depending on how much RAM your host has, allocate the amount you want to give the guest. (This will depend on what purpose the guest has and how many guests will be running.) Then you choose how much storage you want to give the guest. (Again, this depends on the host's storage and how many guests.) Then select the hard disk file type. This depends on whether or not this machine will be used on other software but for now we will choose VDI. We will also choose dynamically allocated on the next screen. Then hit create and the machine is now created. If you would like to add guest additions to the machine, you will want to right click on the machine and go to settings. For example, I use Drag and Drop. which allows me to move files with my mouse to and from the machine. Another option on the guest machine would be the 3D acceleration. This allows the guest to use the host GPU for graphics. I would not reccomend this unless your host GPU is strong enough to handle the load.
## Part 2:

1. Yes, but you will need to use the shared folders option on VirtualBox or similar software.
2. A snapshot is only a copy of the disk file at a certain point. (A sort of fail safe.) A template is the entire virtual machine and takes up much more space.
3. In my network, I am running a Personal Computer that is running Windows. On that computer I have VirtualBox as the hypervisor and that hypervisor has guest running thorugh it.
## Part 3:

1. In order to enable Host-only networking, you will need to go to your VM's settings then network and in the drop down(attached to box go to Host-only. 
