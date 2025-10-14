🐍 Day 6 – File Handling

File handling allows Python programs to **store, read, and modify data** permanently on disk.  
It’s useful for reading and writing files such as text documents, logs, or configuration data.

🔹 Opening a File

Files are opened using the `open()` function.  

| Mode | Description |
|-------|--------------|
| `'r'` | Read (default mode) |
| `'w'` | Write (overwrites file if exists) |
| `'a'` | Append (adds new data to the end) |
| `'r+'` | Read and Write mode |

🔹 Reading from a File

- Reading allows you to **access and display the contents** of a file.  
- It is done using the `open()` function in **read mode (`'r'`)**.  
- When you call `read()`, it returns the entire content of the file as a string.  
- You can also use:
  - `readline()` → reads one line at a time  
  - `readlines()` → reads all lines into a list  
- Always **close the file** after reading to free system resources, or use `with open()` to handle it automatically.

🔹 Writing to a File

- Writing allows you to **create or modify** the contents of a file.  
- It is done using the `open()` function in **write mode (`'w'`)**.  
- If the file already exists, **its old data will be erased** before writing new data.  
- The `write()` or `writelines()` methods are used to store text in the file.  
- After writing, always close the file to save the changes.

🔹 Appending Data to a File

- Appending allows you to **add new data at the end** of an existing file without erasing previous content.  
- It is done using the `open()` function in **append mode (`'a'`)**.  
- Each time you use `write()` in append mode, the new text is placed **after the existing content**.  
- This mode is useful for adding logs, new entries, or continuous updates to a file.  
- The file remains intact — only new data is added at the end.

🔹 Using `with open()` – Best Practice
- Automatically closes the file after use.
- Recommended for safer file handling.

🧠 Summary

| Concept | Description |
|----------|-------------|
| open() | Opens a file |
| read() / write() | Reads or writes data |
| close() | Manually closes the file |
| with open() | Automatically closes the file |
| Modes | 'r', 'w', 'a', 'r+' |
