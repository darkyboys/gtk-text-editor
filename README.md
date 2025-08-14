<p align="center">
  <img src="https://github.com/Matheuschn/gtk-text-editor/blob/main/src/assets/gtkeditor.png?raw=true" alt="GTK Text Editor icon" class="center" width="200" height="200" > 
</p>
<h1 align="center">
  GTK Text Editor
</h1>
A simple text editor written in C and using the GTK toolkit, inspired on the
classic Windows text editor notepad.exe.

# Building
The project uses the Cook Build System to build itself so in order to build this please install the github.com/darkyboys/cook first.

To build on Linux, make sure you have the GTK4 library installed, and follow the steps:
  1. Clone the repo using `git clone`.
  2. Switch into the project's directory and run `cook`.
  3. Run `sudo cook install` to install the binary located on `bin/` to your system (`/usr/local/bin`).

There is no current instruction to build on Windows. If you manage to build it,
please create a Pull Request to change this file.

# Usage
To use the editor, open the application on your system's application menu or 
run the command `gtkeditor` on your terminal.
