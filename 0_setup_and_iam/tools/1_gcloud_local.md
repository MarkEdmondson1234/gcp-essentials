# Use Google Cloud SDK Client Tools Locally

Although you could use the included Cloud Shell (VM) from within Google Cloud to use the set of Google Cloud SDK scripting tools (`gcloud`, `gsutil`, `bq`, others...), 
some customers prefer to install these tools on their local laptops.

## Process

- Go to https://cloud.google.com/sdk/docs/install
- Follow instructions for your OS - be sure to close terminal and re-open and then run `gcloud init...`
- Verify install using `gcloud version`
- Init and auth https://cloud.google.com/sdk/docs/initializing

## More

- Cli cheatsheet - https://cloud.google.com/sdk/docs/cheatsheet
- Manage multiple configurations - https://cloud.google.com/sdk/docs/configurations
- Testing newer services, run `gcloud components update` first
- Configure proxy - https://cloud.google.com/sdk/docs/proxy-settings
- Uninstall - https://cloud.google.com/sdk/docs/uninstall-cloud-sdk
