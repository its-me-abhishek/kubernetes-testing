# kubernetes-testing

# What I did
- installed kind
- kind create cluster --name ccsync-cluster
- kubectl to interact w cluster
- then installed kompose to turn docker-compose into kubernetes

# What went Wrong and how to fix
- backend connection to syncserver ----- shall be a different protocol --- fix: use service name instead of localhost in env.

TO-DO:
