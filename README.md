# vf_integration

## Install Kubernetes on Dev machine

To run the installer follow the steps:

- GIT instalation: `yum install git`

- Clone integration project: `git clone https://github.com/Gratski/vf_integration.git`

- Open the folder install-scripts and run: `chmod 755 dev-software.sh`

- Run the install script: `./dev-software.sh`

## Deploy **nginx** 

To deploy nginx follow the steps:

- Apply: `kubectl apply -f dep-nginx.yaml`

