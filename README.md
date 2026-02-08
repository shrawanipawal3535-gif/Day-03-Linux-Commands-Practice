# Day-03-Linux-Commands-Practice

*Process Management Commands:

ps=Shows running processes
ps -ef=Shows all running processes
top=Live view of CPU & memory usage
htop=Better version of top (if installed)
kill PID=Stop a process by ID
kill -9=PID	Force stop a process
bg=Run process in background
fg=Bring background process to front
jobs=Show background jobs

*File System Commands:

ls=List files
ls -l=Detailed file list
ls -a=Show hidden files
pwd=Show current directory
cd=foldername	Move into a folder
mkdir folder=Create folder
rmdir folder=Delete empty folder
rm file=Delete file
rm -r folder=Delete folder + contents
cp file1 file2=Copy file
mv file newname=Move / rename file
touch file.txt=Create empty file
cat file=View file content
less file=Scroll file content
find / -name=file	Find file

*Networking & Troubleshooting Commands:

ip a=Show IP address
ifconfig=Network info (older systems)
ping google.com=Check internet connectivity
netstat -tulnp=Check open ports
ss -tulnp=Modern replacement of netstat
curl url=Test API or website
wget url=Download files
traceroute google.com=Check network path
nslookup domain=DNS lookup
hostname=Show system hostname
