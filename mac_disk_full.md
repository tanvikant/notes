##Mac Disk full

df -h
df -h /System/Volumes/Data
diskutil apfs list # Tells us what is eating up the free space
du -hd 1 ~ 2>/dev/null | sort -hr # Tells us the largest folders - might also take a couple of seconds
