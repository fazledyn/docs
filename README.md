# Simple Static File Server
This is my simple file server, hosted at https://files.fazledyn.com/ or https://fazledyn.github.io/files/. This project uses [apindex](https://github.com/libthinkpad/apindex) to generate static index pages. This feels like a great way to upload and share files.


# Requirements
- Python 3


# Getting Started
- Copy `apindex.py` and `share/` directory to your repo
- Create a directory called `docs/` where you'll upload your files
- Generate index pages using-
  ```
  python3 apindex.py docs/
  ```
- Commit the updated HTMLs and push to remote.


# Caution
- GitHub won't let you upload binaries/exe files directly. To upload those, you can zip them first.
- Any files greater than 50 MB is going to generate a warning from git. Be sure to keep file sizes smaller. [Read More](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github)

