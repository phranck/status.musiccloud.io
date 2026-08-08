# musiccloud status & uptime

GitHub-native monitoring and the public status page for musiccloud status & uptime, live at **[status.musiccloud.io](https://status.musiccloud.io)**.

[Velvet](https://github.com/phranck/velvet) checks the endpoints listed in [`velvet.yml`](velvet.yml) and records what it finds on the `velvet-data` branch. Confirmed failures and planned maintenance are tracked as GitHub Issues.

Nothing here needs an external monitoring provider or an API key. Monitoring and deployment run through GitHub Actions with this repository's own `GITHUB_TOKEN`.
