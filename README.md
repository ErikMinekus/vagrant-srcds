```bash
vagrant up
vagrant ssh
steamcmd +login anonymous +force_install_dir ~/srcds +app_update 232250 +quit

cd ~/srcds/tf
wget "https://www.metamodsource.net/latest.php?os=linux&version=1.10" -O - | tar -xz
wget "https://www.sourcemod.net/latest.php?os=linux&version=1.10" -O - | tar -xz

cd ~/srcds
./srcds_run -game tf +map cp_dustbowl +maxplayers 24
```
