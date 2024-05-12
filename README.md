# Loadbalanced UI for Proxmox via Ansible

This repo contains Ansible files and Keepalived and HAProxy configs to make the Proxmox UI Loadbalanced and Highly Available.  
At the same time by using Keepalived and Session Cookie Transferal via HAProxy this allows for opened datastreams from one node to seemlessly move to another if that one node shuts becomes unavailable.

---

**Sources**:  
https://forum.proxmox.com/threads/proxmox-vnc-behind-haproxy.141061/  
https://devopstales.github.io/linux/proxmox-haproxy-lb/  
http://docs.haproxy.org/2.9/configuration.html#4-bind
