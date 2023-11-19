First we bootstarp our github with flux with the command: flux bootstrap github \
  --token-auth \
  --owner=moyu597 \
  --repository=DevSecOps-Toolbox-Mo \
  --branch=main \
  --path=clusters/mason-dev \
  --personal \
  --network-policy=false

first we got to settings developer settings and create a classic tokenm we use this token to bootstarp the flux on our terminal at run time.

Nb: the bootsrap command above is run on the command line terminal 