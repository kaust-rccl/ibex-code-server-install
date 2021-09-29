# ibex-code-server-install
Bash scripts for Ibex users that install (or uninstall) VS Code server

## Installing VS Code Server

Login to Ibex using your KAUST credentials.

```bash
ssh $USERNAME@ilogin.ibex.kaust.edu.sa # use glogin.kaust.edu.sa if you need GPU nodes
```

Clone this git repository in your Ibex home directory.

```bash
cd ~/
git clone https://github.com/kaust-rccl/ibex-code-server-install.git
```

Change into the newly cloned repository directory and source the install script. Sourcing the 
install script runs each of the commands in the script as if you had entered them manually at 
the prompt.

```bash
cd ibex-code-server-install/
source install-code-server.sh
```
