# MP3 Tag Reader & Editor

## 📌 Description

MP3 Tag Reader & Editor is a C-based application used to read and modify metadata information stored in MP3 audio files.

The project works with ID3 tags to display and edit information such as song title, artist, album, year, genre, and comments.

## 🎯 Objective

The main objective of this project is to understand MP3 file structure, ID3 tag handling, file operations, and binary data processing using C.

## ✨ Features

- Read MP3 metadata
- Display song information
- Edit MP3 tag information
- Update song title
- Update artist name
- Update album name
- Update year
- Update genre
- Update comments
- Handle MP3 files using file operations
- Supports command-line arguments

## 🛠️ Technologies Used

- C Programming
- File Handling
- Structures
- Pointers
- Command-Line Arguments
- Binary File Operations
- ID3 Tag Format

## 🎵 ID3 Tags

The project works with ID3 metadata stored in MP3 files.

Common fields handled by the project include:

| Tag | Description |
|---|---|
| Title | Name of the song |
| Artist | Name of the artist |
| Album | Album name |
| Year | Release year |
| Genre | Music genre |
| Comment | Additional information |

## ⚙️ Working

### Reading Tags

1. Open the MP3 file in binary read mode.
2. Read the ID3 tag information.
3. Extract the required metadata fields.
4. Display the information to the user.

### Editing Tags

1. Open the MP3 file in read/write mode.
2. Select the tag that needs to be modified.
3. Read the existing tag information.
4. Replace it with the new information.
5. Write the updated data back to the MP3 file.

## 📂 Project Structure

```text
MP3-Tag-Reader-Editor/
│
├── main.c
├── mp3_tag_reader.c
├── mp3_tag_reader.h
├── mp3_tag_editor.c
├── mp3_tag_editor.h
├── types.h
└── README.md
