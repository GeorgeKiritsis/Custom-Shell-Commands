# Custom Shell Commands

 I've created 2 "custom" commands [rename and delete] for Unix-like Systems while learning how to programm basic shell scripts
 
\*I personally tested them on macOS*

#### Features:
- Delete
- Rename

### Usage

## - Delete
`$ delete napkin.txt` -> `$ mv napkin.txt ./~Trash`

## - Rename
`$ rename napkin1.txt napkin2.txt ` -> `$ mv napkin1.txt napkin2.txt`



In order to make these commands global  perform `$ sudo mv delete rename /usr/local/bin`
