# Linux Command Line Cheat Sheet

|    <mark style="background: #D2B3FFA6;">**$ Command $**</mark>     | <mark style="background: #FF5582A6;">explanation</mark> |
| :----------------------------------------------------------------: | :-----------------------------------------------------: |
|                              **pwd**                               |                 Print working directory                 |
|                               **cd**                               |                    Change directory                     |
|                                cd -                                |            Go to the last working directory             |
|                               **ls**                               |                       List files                        |
|                             **ls -a**                              |                     List all files                      |
|                             **ls -l**                              |                   Long listed format                    |
|                             **ls -h**                              |                 Human-readable numbers                  |
|                           **ls -altrh**                            |                         Use it!                         |
|                                                                    |                                                         |
|                           man {command}                            |                   Manual for command                    |
|                          touch {filename}                          |                    To create a file                     |
|                           echo \ printf                            |                       Print text                        |
|                                                                    |                                                         |
|                           cat {filename}                           |                   To see file content                   |
|                          less {filename}                           |    Outputs file content from top, scroll with Enter     |
|                          head {filename}                           |          Outputs the first 10 lines of a file           |
|                          tail {filename}                           |           Outputs the last 10 lines of a file           |
|                                                                    |                                                         |
|                          mkdir {dirname}                           |                    Make a directory                     |
|                        mv {name} {new name}                        |                      Rename a file                      |
|                          mv {file} {dir}                           |               Move file to the directory                |
|                          cp {file} {dir}                           |               Copy file to the directory                |
|                           rm {file_path}                           |                       Remove file                       |
|                            rmdir {dir}                             |                 Remove empty directory                  |
|                            rm -rf {dir}                            |                    Remove directory                     |
|                                                                    |                                                         |
|                       {command} > {filename}                       |      Redirect the output of the command to a file       |
|                   grep 'string' {file location}                    |        Searches the string in the mentioned file        |
|                                 \|                                 |                          Pipe                           |
|                              history                               |                  Used commands history                  |
|                                !84                                 |          Run the 84th command from the history          |
|                              sudo !!                               |        Run the last command with sudo privileges        |
|                                ping                                |                   Send ping requests                    |
|                                                                    |                                                         |
|                              Ctrl + w                              |             Clear words in the command line             |
|                                                                    |                                                         |
| $ killall {name-of-the-program}$ xkill (turns the cursor to a `x`) |                   Terminate processes                   |
|                                                                    |                                                         |
|                   jp2a picname --border --color                    |            Create ASCII version of a picture            |
|                     xclip -sel c < input_file                      |             Copy file content to clipboard              |
|                           sudo fdisk -l                            |                     List partitions                     |
|                             sudo blkid                             |                  View UUID of a drive                   |
