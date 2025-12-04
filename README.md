# 🎵 MP3 Tag Reader & Editor (C Project)
This project reads and edits ID3v2 tags (Title, Artist, Album, Year, Genre, Comment) from MP3 files using C.
It helps understand how MP3 metadata is stored and teaches file handling, endian conversion, and frame parsing in real binary files.

# 📌 Features

Read ID3v2 tags from an MP3 file

Show metadata in a clean output

Edit selected tags without disturbing audio

Converts endianness properly (Big ↔ Little)

Works fully from the command line

Creates a temp file internally and replaces old metadata safely

# 📁 ID3 Tags Supported

TIT2 → Title

TPE1 → Artist

TALB → Album

TYER → Year

TCON → Content Type (Genre)

COMM → Comment

# Requirements
Language   : Advanced C


Compiler   : GCC (GNU Compiler Collection)

Operating System  : Linux / Windows

Libraries Used  : <stdio.h>, <stdlib.h>, <string.h>


File Format  : MP3 (ID3v2 Tag Format)

# Block Diagram

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/03046cd4-5eef-40a6-8174-2df3198ea5ae" />


The MP3 file first goes into the READ module, where the program reads the ID3v2 tags like Title, Artist, Album, etc.
If the user gives an Edit Command, the file moves to the EDIT module, where the selected tag is modified.
Finally, the updated information is written back into the same MP3 file.

# Sample Output
# 1.view data

<img width="819" height="359" alt="Screenshot 2025-12-04 233035" src="https://github.com/user-attachments/assets/5468dffd-5afc-471c-9b3b-30c0d39c220d" />

# 2.Edit data

<img width="902" height="344" alt="Screenshot 2025-12-04 233101" src="https://github.com/user-attachments/assets/acfce04d-447e-458b-a92b-ce352df89d4b" />








