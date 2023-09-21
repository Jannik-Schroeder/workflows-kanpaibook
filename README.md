# workflows-kanpaibook

# Was du machen musst

## CI/CD (Workflows)

* Dateien in .github/workflows/ kopieren
* Secrets in GitHub auf Organisationsebene NICHT auf Repo ebene eintragen: secrets.WEBHOOK_API_KEY / secrets.DISCORD_WEBHOOK
* Dockerfiles für die jeweiligen Branches machen. Dockerfile.dev / Dockerfile.main
