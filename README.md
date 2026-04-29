- # DevOps Journey

## Day 01 - Linux Basics + Nginx

### What I Did
- Used basic Linux commands: `pwd`, `ls`, `cd`
- Created and removed files/directories
- Installed nginx
- Started and stopped nginx service
- Tested server using `curl`

### Break & Fix
- Stopped nginx → curl failed
- Identified issue (service down)
- Restarted nginx → fixed

### Commands Used
See: `day01-commands.txt`

### Learning
- Linux navigation basics
- Service management using `systemctl`
- Debugging mindset (break → observe → fix)
- Day 02 - Permissions & Processes
  
## Day 02 -Permissions & Processes

## What I Did
- Practiced chmod, chown
- Worked with file permissions (644, 755, 000)
- Explored processes using ps, grep
- Killed processes using kill

## Break & Fix
- Removed file permissions → "Permission denied"
- Checked permissions using ls -l
- Restored using chmod 644

- Script failed to run → no execute permission
- Fixed using chmod 755

- Created process using sleep
- Found PID using ps aux | grep
- Killed process using kill

## Learning
- Permissions control access (r, w, x)
- chmod changes permissions
- chown changes ownership
- ps shows running processes
- kill stops processes
