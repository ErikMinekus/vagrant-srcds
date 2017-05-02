```bash
vagrant up
vagrant ssh
steamcmd +login anonymous +force_install_dir ~/srcds +app_update 232250 +quit
cd srcds
./srcds_run -game tf +map cp_dustbowl +maxplayers 24
```
