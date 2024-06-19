# IT4IT-Academy

## Vorrausetzungen

> Git installieren: `winget install --id Git.Git -e --source winget`

> VScode installieren: `winget install -e --id Microsoft.VisualStudioCode --accept-package-agreements` &nbsp;
	
> Windows-Terminal `New-Item GitHub -Type Directory` &nbsp;


## VS Code Extensions
- Git Graph
- GitHub Actions
- PowerShell
- Rainbow CSV


## Terminal Befehle
```
New-Item GitHub -Type Directory
cd .\GitHub\
git clone https://github.com/christianpillinger/IT4IT-Academy.git

git config --global user.email "vorname.nachname@example.com"
git config --global user.name "GitHubUsername"
```

## Git Befehle
|Befehl|Beschreibung|
|--------|--------|
|    git config --global --list    |    Konfiguration anzeigen    |
|    git clone [https][ssh]    |    Klont das Projekt in das Verzeichnis auf Ihrem Rechner    |
|||
|    git pull    |    Holt die Änderungen aus dem Remote Repository ab    |
|    git add .    |    Alle geänderten Dateien gleichzeitig zum Index hinzufügen    |
|    git commit -m "added feature1"    |    Kurzbeschreibung der Änderung    |
|    git push origin master    |    Änderungen zum Master-Branch hinzufügen    |




