## 19CS416-CS-Ex-3-Linux-Commands
Linux is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.
## Name: S Madhumitha
## Reg no:212225040217
**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```


**Output:**
<img width="984" height="210" alt="Screenshot 2026-09-05 125847" src="https://github.com/user-attachments/assets/1b36e739-fa8f-4a96-9fbc-5110bd427947" />


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**
<img width="309" height="137" alt="Screenshot 2026-09-05 125856" src="https://github.com/user-attachments/assets/daee17f0-7daa-4fe2-a31f-f359cbe1ec34" />

### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```


**Output:**
<img width="318" height="121" alt="Screenshot 2026-09-05 125903" src="https://github.com/user-attachments/assets/d39b28b9-2569-4dc3-bdf2-1405e017ba81" />

### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**
<img width="383" height="121" alt="Screenshot 2026-09-05 190325" src="https://github.com/user-attachments/assets/636ad503-45f4-46f7-b934-64427b01d4e7" />

### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**
<img width="446" height="237" alt="Screenshot 2026-09-05 190333" src="https://github.com/user-attachments/assets/9683e6c9-b7a0-432d-be06-f381a4578e93" />

### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**
<img width="383" height="91" alt="Screenshot 2026-09-05 190342" src="https://github.com/user-attachments/assets/6bd86b5d-54a1-4cee-8271-93aa993ce72c" />

### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**
<img width="384" height="200" alt="Screenshot 2026-09-05 190349" src="https://github.com/user-attachments/assets/13aa2bfc-fc6a-4df7-8576-d239fee86579" />

### 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
```

**Output:**
<img width="944" height="686" alt="Screenshot 2026-09-05 190401" src="https://github.com/user-attachments/assets/27036037-92c1-4448-b2d2-dfa87222fa47" />

### 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
```

**Output:**
<img width="427" height="229" alt="Screenshot 2026-09-05 190408" src="https://github.com/user-attachments/assets/d60c2e1f-5444-4f48-ad52-1513f9ce1130" />

### 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
```

**Output:**
<img width="1040" height="377" alt="Screenshot 2026-09-05 190422" src="https://github.com/user-attachments/assets/697aa6c7-b360-4eba-a5ed-04d1374f185a" />

### 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename 's/old-name/new-name/' <files>
```

**Output:**
<img width="1037" height="364" alt="Screenshot 2026-09-05 190437" src="https://github.com/user-attachments/assets/a963f5af-ea36-42ea-a82b-695897e8d331" />

### 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
```

**Output:**
<img width="1039" height="380" alt="Screenshot 2026-09-05 190457" src="https://github.com/user-attachments/assets/e3b73cb5-16f6-47c9-a641-2f65cf08dc64" />

### 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
```

**Output:**
<img width="570" height="141" alt="Screenshot 2026-09-05 190505" src="https://github.com/user-attachments/assets/9ef38019-a20e-4f4f-8b55-c7da14ccb95a" />

### 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

**Output:**
<img width="334" height="98" alt="Screenshot 2026-09-05 190512" src="https://github.com/user-attachments/assets/36593162-b225-4a5e-bfcd-8dc29bde3d83" />

### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

**Output:**
<img width="1048" height="388" alt="Screenshot 2026-09-07 134119" src="https://github.com/user-attachments/assets/029e06c8-0138-40dd-b4d3-25f5ce9fea23" />

### 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
```

**Output:**
<img width="339" height="98" alt="Screenshot 2026-09-07 134140" src="https://github.com/user-attachments/assets/81a61e97-a171-496d-8043-1521524ed8e6" />


### 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
```

**Output:**
<img width="765" height="914" alt="Screenshot 2026-09-07 134157" src="https://github.com/user-attachments/assets/dcc3dda5-eae2-428e-801e-412422b5a3f0" />

### 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
```

**Output:**
<img width="637" height="784" alt="Screenshot 2026-09-07 134220" src="https://github.com/user-attachments/assets/89d1d67c-9162-4307-8e58-8a7f41703e19" />

### 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
```

**Output:**
<img width="881" height="792" alt="Screenshot 2026-09-07 134231" src="https://github.com/user-attachments/assets/01aaed47-9a9c-4739-8344-f831fd479c65" />

### 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
```

**Output:**
<img width="277" height="180" alt="Screenshot 2026-09-07 134239" src="https://github.com/user-attachments/assets/0ca7f170-3471-48f3-aced-4239392e335a" />

### 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

**Output:**
<img width="1040" height="214" alt="Screenshot 2026-09-07 134248" src="https://github.com/user-attachments/assets/1b44016d-721c-46c8-87c6-1e8b912690f9" />

### 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
```

**Output:**
<img width="907" height="456" alt="Screenshot 2026-09-07 134255" src="https://github.com/user-attachments/assets/4050572e-ecd0-4c85-8445-ee91e2531c08" />

### 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
```

**Output:**
<img width="494" height="439" alt="Screenshot 2026-09-07 134304" src="https://github.com/user-attachments/assets/7794c1cf-f9a8-4e98-9fe8-77ccc5e77850" />

### 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip <file1> <file2> <file3>...
```

**Output:**
<img width="314" height="339" alt="Screenshot 2026-09-07 134314" src="https://github.com/user-attachments/assets/9c30f093-247e-4c55-a70d-719552bb4063" />

### 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
```

**Output:**
<img width="247" height="96" alt="Screenshot 2026-09-07 134321" src="https://github.com/user-attachments/assets/b13ce56f-9182-4aae-9b8a-e0f1ab78b34c" />

### 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

**Output:**
<img width="247" height="96" alt="Screenshot 2026-09-07 134321" src="https://github.com/user-attachments/assets/db4d325a-b520-4387-ab01-718cdf4ad72c" />
<img width="556" height="175" alt="Screenshot 2026-09-07 134328" src="https://github.com/user-attachments/assets/03955607-1877-40de-b566-6569e3b26be2" />

### 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

**Output:**
<img width="1040" height="615" alt="Screenshot 2026-09-07 134337" src="https://github.com/user-attachments/assets/31ef8ad2-d3e9-4a58-9efb-85d0281843c6" />

### 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

**Output:**
<img width="785" height="535" alt="Screenshot 2026-09-07 134345" src="https://github.com/user-attachments/assets/a89e5c01-5247-4b45-b755-bde7396b4e50" />

### 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

**Output:**
![Uploading Screenshot 2026-09-07 134157.png…]()


### 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
```

**Output:**
<img width="637" height="784" alt="Screenshot 2026-09-07 134220" src="https://github.com/user-attachments/assets/3087ce46-8407-475c-8809-e2b0eca6a6cb" />

## Result
