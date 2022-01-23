# Install Visual Studio Code On Web

```bash
curl -fsSL https://code-server.dev/install.sh | sh

mkdir -p /home/FILES
chmod 777 -Rv /home/FILES

nano ~/.config/code-server/config.yaml

bind-addr: 127.0.0.1:8080
auth: password
password: masuk123
cert: false

code-server /home/FILES (example run code-server with directory folder)



open localhost:8080
masuk123



setting -> find "json" 

edit settings.json
"editor.minimap.enable" : false,
"editor.acceptSuggestionOnCommitCharacter": false,

got setting again -> find "font"
set to 8







```