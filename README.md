# Secure_File_Archiver


This is a Java-based File Packer and Unpacker project. It allows users to combine multiple .txt files into a single file and later extract them back to their original form.

The project also includes basic encryption and decryption using XOR.

Features
Pack multiple text files into one file
Unpack files back to original format
XOR encryption and decryption
Command-Line version
GUI version using Java Swing

Technologies Used
Java
Java Swing
FileInputStream and FileOutputStream
ArrayList and byte arrays
XOR encryption (Key = 0x11)

How It Works

Packing:
Reads multiple files
Stores file name and size as header
Encrypts data
Writes into a single file

Unpacking:
Reads packed file
Decrypts data
Uses header info to recreate original files

Usage

Command Line:
java Packer <directory> <output_file>
java Unpacker <packed_file> <destination_folder>

GUI:
Run the GUI class

Select files
Click Pack or Unpack
