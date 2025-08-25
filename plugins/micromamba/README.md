# micromamba plugin

This plugin is based on the micromamba plugin, and just changes the aliases to better fit the 'micromamba'
command.

The micromamba plugin provides [aliases](#aliases) for `micromamba`, usually installed via [anamicromamba](https://www.anamicromamba.com/) or [micromamba](https://docs.micromamba.io/en/latest/minimicromamba.html).

To use it, add `micromamba` to the plugins array in your zshrc file:

```zsh
plugins=(... micromamba)
```

## Aliases

| Alias    | Command                                 | Description                                                                     |
| :------- | :-------------------------------------- | :------------------------------------------------------------------------------ |
| `mna`    | `micromamba activate`                        | Activate the specified micromamba environment                                        |
| `mnab`   | `micromamba activate base`                   | Activate the base micromamba environment                                             |
| `mncf`   | `micromamba env create -f`                   | Create a new micromamba environment from a YAML file                                 |
| `mncn`   | `micromamba create -y -n`                    | Create a new micromamba environment with the given name                              |
| `mnconf` | `micromamba config`                          | View or modify micromamba configuration                                              |
| `mncp`   | `micromamba create -y -p`                    | Create a new micromamba environment with the given prefix                            |
| `mncr`   | `micromamba create -n`                       | Create new virtual environment with given name                                  |
| `mncss`  | `micromamba config --show-source`            | Show the locations of micromamba configuration sources                               |
| `mnde`   | `micromamba deactivate`                      | Deactivate the current micromamba environment                                        |
| `mnel`   | `micromamba env list`                        | List all available micromamba environments                                           |
| `mni`    | `micromamba install`                         | Install given package                                                           |
| `mniy`   | `micromamba install -y`                      | Install given package without confirmation                                      |
| `mnl`    | `micromamba list`                            | List installed packages in the current environment                              |
| `mnle`   | `micromamba list --export`                   | Export the list of installed packages in the current environment                |
| `mnles`  | `micromamba list --explicit > spec-file.txt` | Export the list of installed packages in the current environment to a spec file |
| `mnr`    | `micromamba remove`                          | Remove given package                                                            |
| `mnrn`   | `micromamba remove -y -all -n`               | Remove all packages in the specified environment                                |
| `mnrp`   | `micromamba remove -y -all -p`               | Remove all packages in the specified prefix                                     |
| `mnry`   | `micromamba remove -y`                       | Remove given package without confirmation                                       |
| `mnsr`   | `micromamba search`                          | Search micromamba repositories for package                                           |
| `mnu`    | `micromamba update`                          | Update micromamba package manager                                                    |
| `mnua`   | `micromamba update --all`                    | Update all installed packages                                                   |
| `mnuc`   | `micromamba update micromamba`                    | Update micromamba package manager                                                    |
