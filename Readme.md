# Update chart
```
helm package */helm
```
# Update index.yaml
```
helm repo index ./ --url https://raw.githubusercontent.com/poncheg/helm-repo/main
```
# Add helm project in git repo
```
helm repo add my-test https://raw.githubusercontent.com/poncheg/helm-repo/main/
```