## 02203 serial interface

This application allows the download and the upload of a P2-type PGM image of size 352x288 pixels using the serial port.

### EXE generation for Windows

To genenrate the .exe for MS windows run the following command. Probably the full path for the icon is needed.

'''
pyinstaller --windowed --onefile --icon=icon.ico --name="Serial interface" serial_interface.py
'''

### ToDo:

- Write Makefile
- Support Python 2 (if possible)
- Upload the icon.ico
- Write a proper README.md
