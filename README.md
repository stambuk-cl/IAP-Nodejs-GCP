# A very simple POC of a node.js app with IAP at GKE for GCP (Readme in progress :nerd_face:)

This a very simple POC to see how IAP works on GCP, you must do some pre-config for this to work, the most part of the setup is done but i recommend to take a look on the .yamls to understand what are you doing here.


First run
npm install express --save

At this part, you can build the docker image and see the app :sunglasses:

Then you must follow the following configuration for the secrets and consent page at IAP GCP

Configuring the OAuth consent screen
https://cloud.google.com/iap/docs/enabling-kubernetes-howto#oauth-configure

Creating OAuth credentials
https://cloud.google.com/iap/docs/enabling-kubernetes-howto#oauth-credentials

Setting up IAP access
https://cloud.google.com/iap/docs/enabling-kubernetes-howto#iap-access

Creating a Kubernetes Secret
https://cloud.google.com/iap/docs/enabling-kubernetes-howto#secret-create
