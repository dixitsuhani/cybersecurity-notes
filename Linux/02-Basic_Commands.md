# Print Working Directory (pwd)
- Used for determining where we are currently located in the file system.
- Prints the full path of the current working directory.
- **Syntax:**
  ```text
  pwd [options]
  ```
# Changing Directories (cd)
- Used for navigating the file structure.
  ```text
  cd [options] [path]
  ```
- 2 types of paths:
  - **Absolute Paths:** Allows us to specify the exact location of directory. Always starts with root directory (/). For example,
    ```text
    cd /home/sysadmin
    ```
  - **Relative Paths:** Gives direction to a file relative to current location in the file system. - Specifies the location of a file or directory relative to the current working directory. For example,
    ```text
    cd Documents
    ```
- Shortcuts:
  - **The .. characters (cd ..):** Move to the parent directory.
  - **The . characters (cd .):** Stays in the current directory.
  - **The ~ characters (cd ~):** Moves to home directory.
# Listing Files (ls)
- Used to list the contents of a directory.
  ```text
  ls [options] [file]
  ```
- **Default Usage:** Lists the contents of current directory.
- **-l option:** Displays a detailed (long) listing, including file type, permissions, owner, size and modification time.
- **Sorting:**
  - **-t:** Sort files by timestamp.
  - **-S:** Sort files by file size.
  - **-r:** Reverses any type of sort. Reverses in alphabetical order by default.
