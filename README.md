![](terminal.png)

# bsh

Run bun shell as a standalone interactive shell.

```bash
bunx @tr1ckydev/bsh
```



### Commands

> [!CAUTION]  
> Many commands are under development and might not work as expected. If you find any issue report them in Bun's GitHub repository.

The following bash commands are available natively in bun shell.

| Command  | Description                                         |
| -------- | --------------------------------------------------- |
| `cat`    | Concatenate files and print on the standard output. |
| `touch`  | Create, change and modify the timestamps of a file. |
| `mkdir`  | Create directories, if they do not already exist.   |
| `export` | Display or export environment variables.            |
| `cd`     | Change the current working directory.               |
| `echo`   | Display a line of text.                             |
| `pwd`    | Output the current working directory.               |
| `which`  | Display the full path of (shell) commands.          |
| `rm`     | Remove files or directories.                        |
| `mv`     | Move or rename files and directories.               |
| `ls`     | List directory contents.                            |
| `exit`   | Exit the shell with an optional exit code.          |
| `true`   | Return a successful result.                         |
| `false`  | Return an unsuccessful result.                      |

...and all other commands available globally in the system.


### Flags

- `--version`: Print bsh and bun version.

- `-c`: Pass shell command as string to bsh and execute.

  ```bash
  bunx @tr1ckydev/bsh -c "pwd"
  ```

### Known issues

- Command history doesn't work with `prompt` but works with `readline` on linux which behaves weirdly on windows.

This is an experimental project! File an issue if you find bugs and weird behaviours.



## License

This repository uses MIT License. See [LICENSE](https://github.com/tr1ckydev/bsh/blob/main/LICENSE) for full license text.
