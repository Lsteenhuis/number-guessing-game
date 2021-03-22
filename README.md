#### Cloning code repositories

The project uses `git` submodules to manage repositories. There is a different GitHub
repository per application component (`server` and `client`) 
Each submodule is linked to the `main` repository.

Clone the `main` repository on GitHub to your local machine.
Run the commands below to pull the latest code for each submodule.

```bash
git submodule update --init
git pull --recurse-submodules
```
