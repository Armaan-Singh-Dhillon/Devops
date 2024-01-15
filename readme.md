## Connecting To remote machine

```bash
sudo apt install openssh-server
sudo systemctl start ssh
sudo systemctl enable ssh
```

### login thorough terminal

now to login through the terminal of host machine as

```bash
ssh <username>@<IPv4 of remote machine>
```

### login thorough vscode remote development setup.

now to login through the terminal of host machine as

```bash
<username>@<name-of-remote>
```

## Basics Linux

### symbol meaning in CLI

```bash
armaan@WhiteOrchard:~$
    |          |
username  computername
    ~ means => home/user
    $ means => Regular User
    # means => Root User
```

### Remove Command

```bash
rm <filename> -> used to delete file
rm -r <directony_name> -> used to delete folder and all files in it
```
