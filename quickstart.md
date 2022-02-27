# Quickstart

```bash
# create venv
python3 -m venv env
source env/bin/activate
python3 -m pip install -r requirements.txt
ipython kernel install --user --name=env # Install new kernel for Jupyter Notebook in VS Code
# Need to restart VS Code to pick up new kernel

# Run image-refresher.ipynb - which will spit out a markdown file containing all Arc images as a README.md

# To run skopeo to validate manually
# arcdata
skopeo inspect docker://mcr.microsoft.com/arcdata/arc-service-proxy:v1.4.0_2022-02-25 # Contains created date
skopeo inspect docker://mcr.microsoft.com/arcdata/arc-server-controller:latest # Contains created date
skopeo inspect docker://mcr.microsoft.com/arcdata/arcdataservices-extension:1.1.18031001 # No created date

# azurearck8s
skopeo inspect docker://mcr.microsoft.com/azurearck8s/westcentralus/stable/azure-arc-k8sagents:1.6.6 # No created date
skopeo inspect docker://mcr.microsoft.com/azurearck8s/arc-preview/fluxctl:0.2.0 # No created date
```
