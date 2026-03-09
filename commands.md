# Useful Linux Commands

## File Permissions
chmod +x file.sh
chmod 755 file.sh

## Change Ownership
sudo chown user file.txt
sudo chown user:group file.txt

## File Searching
find /home -name file.txt
find / -type f

## Text Searching
grep "password" file.txt
grep -r "password" /home

## Process Management
ps
top
kill PID
kill -9 PID

## Package Management
sudo apt update
sudo apt install package-name
sudo apt upgrade
sudo apt remove package-name
