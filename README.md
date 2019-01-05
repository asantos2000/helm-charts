# asantos2000 - Helm Charts Repo

```bash
# Rebuild index
helm repo index .

# Add repo
helm repo add asantos2000 https://asantos2000.github.io/helm-charts

# Update
helm repo update
# Output
Hang tight while we grab the latest from your chart repositories...
...Successfully got an update from the "asantos2000" chart repository
...Successfully got an update from the "stable" chart repository
Update Complete. ⎈ Happy Helming!⎈
##

# List charts
helm search asantos2000
# Output
NAME                            CHART VERSION   APP VERSION     DESCRIPTION
asantos2000/mychart      0.1.0           1.0             A Helm chart for Kubernetes
#
```

## Hosted helm-charts
* [mychart - Example](mychart.md)