# honma
A tiny script for managing subcommands and boilerplate options. You can use commands like directory.

Beat too much commands such as `git`, `kubectl`, `docker`!

**Currently just conceptual implementation**


## How to use
### Install honma
```sh
wget https://github.com/amaya382/honma/raw/master/honma
chmod +x honma
sudo mv honma /usr/local/bin
```

### Try honma
```sh
honma {base_command} # Set base command
{some_subcommands} # Exec command
/{some_subcommands} # Append subcommands to base command
.. # Pop last subcommand
${some_command} # Exec command on BASE shell, w/o honma env
:quit # Quit honma
^D # Quit honma
```


## Future works
* Allow to use arrow keys
* History by base shell
* Completion
* Integrate into zsh or fish (as a plugin)

