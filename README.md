# TickMaster

## Get Started
```bash
./google-cloud-sdk/install.sh
source ~/.zshrc

gcloud auth login
gcloud init
gcloud components install gke-gcloud-auth-plugin

gcloud container clusters get-credentials ticketing-dev

gcloud auth application-default login

# update the package to the latest
npm install ts-node-dev@latest ts-node@latest
```