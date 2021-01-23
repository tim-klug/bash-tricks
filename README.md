# bash-tricks

| Command                   | Result                                             |
| :------------------------ | :------------------------------------------------- |
| **Ctrl + L**              | clear the actual window                            |
| `sudo !!`                 | run the last command with sudo privileges          |
| `grep -Ev '^#\|^$' <file>`| display file content with comments and empty lines |
| **Ctrl + R**              | search in bash history up                          |
| **Ctrl + S**              | search in bash history down                        |
| `cd -`                    | go to the previous path                            |
| `cd ~`                    | go to home path                                    |
| `pwd`                     | print the actual path                              |
| `#something`              | use hashtag for faster search                      |
| **Ctrl + q**              | park the actual command                            |
| **Ctrl + z**              | send task to background                            |
| **Ctrl + X + Ctrl + E**   | open command in vi                                 |
| `fc`                      | open last command in vi                            |
| `du -sk * \| sort -n`     | show the total folder size for subfolders          |
| `cat /etc/*release`       | display distro information                         |
| `uname -r`                | get kernel version                                 |
| `uname -a`                | get all kernel infos                               |

## Get a Servers Fingerprint

```bash
$> ssh-keygen -lf <(ssh-keyscan hostname 2>/dev/null)
```

