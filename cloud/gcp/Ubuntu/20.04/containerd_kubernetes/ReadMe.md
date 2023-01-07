Packer configuration that builds an image with Ubuntu 20.04, installs containerd and Kubernetes

Pass the variables file to Packer using the -var-file flag:

packer build -var-file=variables.json template.json
