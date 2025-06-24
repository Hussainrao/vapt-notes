# vapt-notes
day-1
================================================<>Basic to kali<>====================================================
cat /etc/shells = this contain the shell cmnds of the linux user which are useful in vapt
on this shells some commands works on some files and other on other files
r bash = restricted bash 
cat etc/passwd = this file contains the user information and passwords all the other things.
/usr/bin/zsh = this shows the value of the the user 
what is the value of root= 0
echo $0 = to check the current shell
echo $shell= 
why we are using $ sign repeatedly= becoz this stores the data like variable
example= a=1
echo $a = 1
by defining the variable we can assign new values through the $ sign.
there are two types of variable local and global 
//we use export cmd 
export ip=1.1.11
$ sh
//result..
$ echo $ip
1.1.1.1
//new exmp
//to check enviroment variables  
env
// i want to switch shell i have cmnds 
man chsh = to see whole files related to the shell
chsh -s 
//for location 
which whoami
which ls
which python
// i want to print vlaue in variable
pyth=(which python)
// related to cmnds
linux stores dfrnt types of files 
shells can be changed with single cmnd (gtfobin ..website) , here a container is present which contains the cmnds which changes shell in single command from there we can get cmnds and open in vm editor)
suid = cmnds that run by default on kali linux
to find  cmnds wee use = find /-user root -perm /4000 2>dev/null
sudo -l (to check which cmnds can be used on the machine)
temp folder is the folder which can be used to write privileges,such as payload and other executable permission are used
c windows task = this folder is also same as like temp folder on which evrry user can use if he has permissioin or not,
cat /proc/version =info abt linux like kernel,debian ve, machine, architecture, last upgrade
sys info = system information
for window (systeminfo) here you can system vulnerablity patches 
sudo cat /etc/shadow (user passwords hashs are stored here this is the location of that folder )
cd .ssh  - (ls -al) (this stores the keys to connect through the ssh )
chron jobs = this cmnds are used to run a on a specific time
cmnd = cat etc/crontab
ls /usr/wordlist (this folder contains more passwords using dirbuster)
sudo gzip -d /usr/share/wordlists/rockyou.txt.gz 
/usr/share/wordlists/rockyou.txt.gz: Path to the popular password wordlist used in brute-force attacks (commonly in Kali Linux). 






























