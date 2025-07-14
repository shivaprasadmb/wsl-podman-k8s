# wsl-podman-k8s
Tells how to setup podman desktop with k8s and use wsl to interact with k8s. This is mainly for Windows system.

## Pre-requisites
- have wsl 2 version installed, reference => https://learn.microsoft.com/en-us/windows/wsl/install
- podman desktop for windows, reference => https://podman-desktop.io/docs/installation/windows-install
- recommended to have 16GB ram laptop (to run podman and local k8s cluster)


# Steps
### 1.

once the podmand desktop is installed, it will prompt for installing few extensions. Select next and install all.
Enable below extensions if not enabled:

![Extensions in Podman Desktop](images/pic1.png)
Mainly kubectl and minikube extensions are needed.

Go to settings page and you will see Minikube cluster options.
![Settings in Podman Desktop](images/pic2.png)