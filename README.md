# ECK deployment with fluxCD
Fork this repo to your account and create a personal access token. 
Then Simply run below command to bootstrap your cluster with fluxcd assuming that flux cli is already installed on your system.


```
# Create a GitHub personal access token and export it as an env var
export GITHUB_TOKEN=<my-token>
flux bootstrap github --owner=<owner> --repository=eck-example --private=false --personal=true
```