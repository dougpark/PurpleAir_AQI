
# How to find the pid for a running process 
https://unix.stackexchange.com/a/237911
ps ax | awk '! /awk/ && /myprocessname/ { print $1}'


# How to run a job on startup
cat /etc/rc.local

## Example
cd ~pi/aqi
ls -la
sudo python3 stats.py &
