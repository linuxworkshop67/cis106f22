# Question 1

## awk
* Description:
    * awk is asdasdkasdpkasdmfasdfkad psd as
* Formula:
* `awk + options + {awk command} + file`
* `command output` | `awk + options + {awk command}`

* Examples:
    * how to print the first field of a file:
        * `awk -F':' '{print $1}' /etc/passwd`
    * How to start printing from a different line 
        * `awk 'NR > 3 {print}' /etc/passwd`
    * how to change a field to upper case:
        * `awk -F: '{print toupper($1)}'`
## cat
## cp
## cut
## grep
## head
## ls
## man
## mkdir
## mv
## tac
## tail
* Description:
* Formula:
* Examples
    * How to see the last line in a file
        * `tail -1 /etc/passwd`
> command output
```
sshd:x:130:65534::/run/sshd:/usr/sbin/nologin
```
## touch
## tr
## tree
## vim/nano


# Question 2

* How to work with multiple terminals open?
    * open one terminal the  open another terminal and set them side by side. Or user tillix and split the terminal as needed.
* How to work with manual pages?
* How to parse (search) for specific words in the manual page
* How to redirect output (> and |)
* How to append the output of a command to a file
* How to use wildcards (For copying and moving multiple files at the same time)
* How to use brace expansion (For creating entire directory structures in a single command)
