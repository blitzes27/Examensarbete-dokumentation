# Examensarbete-dokumentation
Examensarbete dokumentation

[Förstudie](<Förstudie Examensarbete.pdf>)

[Technical documentation](<Technical documentation.pdf>)

Ansible scripts automate provisioning and configuring Ubuntu VMs on Proxmox, then install and initialize a Kubernetes cluster. Key steps include disabling sleep, setting hostnames, configuring SSH, mounting NFS, installing Docker & cri-dockerd, and initializing Kubernetes with Calico networking. The playbooks also install Helm, MetalLB for load balancing/metrics, and Rook for Ceph storage. All tasks rely on variables defined in the inventory and use modular roles.
