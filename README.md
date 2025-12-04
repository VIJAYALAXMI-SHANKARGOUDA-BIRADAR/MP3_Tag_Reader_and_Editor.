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

Language : Advanced C
Compiler : GCC (GNU Compiler Collection)
Operating System : Linux / Windows
File Format : MP3 (ID3v2 Tag Format)
Libraries Used : <stdio.h>, <stdlib.h>, <string.h>




