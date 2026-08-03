# steam-monitor (espelho)

Espelho automático dos patterns do OpenSteamTool, usado pelo launcher UnLockedGames
para reconhecer novas versões da Steam (evita "Unsupported Steam Version").

- Branch `pattern` / `ipc`: os arquivos que o app baixa (`fetch_ost_patterns`).
- Sincroniza de `OpenSteam001/steam-monitor` a cada 3h via GitHub Action.

O app aponta para cá (`raw.githubusercontent.com/Lurizin/steam-monitor/...`) em vez
do terceiro, então a disponibilidade não depende mais de uma conta que não é sua.
