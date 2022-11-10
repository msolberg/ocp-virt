This directory provides a Dockerfile suitable for building and pushing a container image from a qcow2 file for openshift virt.

Here's how I built my image:
 
```
# mv ~/Downloads/Fedora-Cloud-Base-36-1.5.x86_64.qcow2 .
# sudo podman build -t quay.io/msolberg/ocp-virt-images/fedora-cloud-base:36-1.5 .
# sudo podman push quay.io/msolberg/ocp-virt-images/fedora-cloud-base:36-1.5 
```
