
|              | Minikube                                                  | Kind                                                      | K3s                                                        |
|:------------:|:---------------------------------------------------------:|:----------------------------------------------------------:|:----------------------------------------------------------:|
|   **Description** | Minikube is a tool for running Kubernetes within a local environment. | Utility for launching local Kubernetes clusters using containers as cluster nodes. | It is a Kubernetes distribution designed to be extremely lightweight. |
| **Features <br> OS and Technology Support** | Linux, macOS, Windows, Docker, VirtualBox, QEMU, Podman, Hyper-V, KVM | Linux, macOS, Windows, Docker | Linux |
| **Advantages** | Large community > 28k GitHub stars, built-in management utility, built-in monitoring tools | Ability to deploy multi-node clusters on a single machine, low resource requirements, large community > 12k GitHub stars | Very low resource footprint, support for Helm charts, built-in LoadBalancer |
| **Disadvantages** | High resource requirements | No stable release yet | Slightly different from native Kubernetes |

Conclusion: 
Minikube: if compatibility with older developments needs to be maintained and MacOS and Windows are required. 
Kind: if testing applications on real nodes and non-Linux OS is necessary. 
K3s: if working with very limited resources and where Linux is the only OS available. 

Demo:
Minikube
![Image](./minikube.gif)

