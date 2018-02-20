# git Branch aktuell halten

1. das eigene Repo klonen
git clone git@github.com:USER/REPO.git
cd REPO

2. geforktes Repo als "upstream" im lokalen Repo eintragen
git remote add upstream git://github.com/FORKED_USER/FORKED_REPO.git
git fetch upstream

3. Änderungen in eigenen master-Branch übernehmen
git pull upstream master

4. Änderugen in eigenes Repo auf github hochladen
git push
