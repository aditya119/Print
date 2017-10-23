# Print
A shell script to print a text file from a printer connected to a remote computer on the same network.
This will work only when both the user and remote computers are running on Linux OS.
Replace the <user-name> and <ip> tags in the 'print' file with the username and IP of the remote computer to which the printer is connected.
After downlaoading the script,
  - Make your own "/bin" directory in the "/home"directory.
  - Move the "print" script in that directory.
  This can be done using the following commands:
  cd ~; mkdir bin
  mv print bin
  - Run the command "echo $PATH", you should find /home/<your-username>/bin as on of the path in this; if it is not already, then paste the following command in the ".bashrc" file in your "/home" direcotry
  export PATH=~/bin:"$PATH"
  And re-read the ".bashrc" file to make the changes available using the command:
  . .bashrc
After following the above mentioned steps, you can access the print file from anywhere, and it would work like any other command.
To print a file: open the Terminal, traverse to the directory containing the file, and run the print command using "print" and follow the steps as required.
