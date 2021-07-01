# Azuresshmodule
Azure AKS node doesn't allow direct SSh or any port forwarding to public, Hence this container package has been created to rout traffic via this pod.
Currently this only forwards SSH (port 22) & Tinc VPN (port 655) to the node on which it is running.
The node Ip will be determined autometically from environment variables & acoordingly it will apply iptables rule.

In case you need any specific port forwarding please add feedback
