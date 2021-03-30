IMPERATIVE COMMANDS
Passing credentials via environment variable
https://cloud.google.com/docs/authentication/production#passing_variable
WINDOWS
`set GOOGLE_APPLICATION_CREDENTIALS=GOOGLE_CREDENTIALS.json`
LINUX
`export GOOGLE_APPLICATION_CREDENTIALS="GOOGLE_CREDENTIALS.json`

Authenticate Google Cloud API
https://stackoverflow.com/a/63181221/1445318
`gcloud auth login`
`gcloud container clusters get-credentials <cluster name> --zone <zone> --project <project id>`
`gcloud config set project <project id>`

TODO: Test Istio, grafana, prometheus etc in gcloud

Mongoose user model vs mongoose user document
Mongoose user model represents the entire collection of users, while Mongoose user document represents one single user

Create a secret
`kubectl create secret generic jwt-secret --from-literal=JWT_KEY=asdf`

Get existing secret
`kubectl get secrets`

Switch cygdrive directory
`cd /cygdrive/e/Projects/Samples/Microservices/ticketing/auth/`

TODO: Test if building services without istio is faster

Start skaffold in dev mode with manual trigger
`skaffold dev --trigger=manual`

TODO: Use skaffold profiles to switch between local and GCP contexts
