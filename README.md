# kubernetes-networkpolicies-examples

Here you find a bunch of networkpolicies for kubernetes.  
By default, every traffic is blocked (deny_all). The communication between the pods inside a namespace is restricted to the needed ports (except gitlab).  
Traefik can access the pods with a webui.
