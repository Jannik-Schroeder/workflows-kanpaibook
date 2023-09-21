# workflows-kanpaibook

# Was du machen musst

## CI/CD (Workflows)

* Dateien in .github/workflows/ kopieren
* Secrets in GitHub auf Organisationsebene NICHT auf Repo ebene eintragen: secrets.WEBHOOK_API_KEY / secrets.DISCORD_WEBHOOK
* Discord Channel und Webhook erstellen Schlüssel kopieren und in GitHub eintragen als secret mit dem Namen DISCORD_WEBHOOK
* Secret für Webhook API werde ich per Solun zukommen lassen. Dieses Secret muss in GitHub als secret mit dem Namen WEBHOOK_API_KEY eingetragen werden.
* Dockerfiles für die jeweiligen Branches machen. Dockerfile.dev / Dockerfile.main
