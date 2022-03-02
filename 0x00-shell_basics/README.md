pwd: prints the working directory
ls: display the contents list of the working directory
cd: returns to the root directory
ls -l: display the contents of current directory in long format
ls -a : Display current directory contents, including hidden files
ls -an: Display current directory contents:
- Long format
- with user and group IDs displayed numerically
- And hidden files (starting with .)

mkdir /tmp/my_first_directory: creates my_first_directory in tmp directory

rm /tmp/my_first_directory/betty: removes betty file

rmdir /tmp/my_first_directory: deletes my_first_directory
10-back: changes to the previous working directory

ls -a -l . .. /boot:  lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format

file /tmp/iamafile : prints the type of iamafile

ln -s /bin/ls __ls__: Create a symbolic link to /bin/ls, named __ls__. on the current working directory

cp -u *.html ..: copies html items from current working directory to parent of the current working directory
