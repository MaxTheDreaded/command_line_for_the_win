# command_line_for_the_win

## Using SFTP

- Used the 'put' command to transfer from my local machine to the remote machine(sandbox envrionment).
    - Steps followed:
        - Navigate to the directory containing the files (screenshots in this case) on your local machine.
        - connect to the sftp server using the sandbox provided address.
        - once connected, navigate to the remote directory where you want to place the incoing files. Create them if necessary.
        - using the put command, make sure to type in the exact name of the file as it appears on your local machine. A file of the same name will be created on the remote machine. However, if you need to, you can also specify a new name for saving the file on the remote machine by passing it as an argument
          
