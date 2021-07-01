# Azuresshmodule
Azure / AWS AKS node doesn't allow direct SSH or any port forwarding to public IP, Hence this container package has been created to route traffic via this pod.
Currently this only forwards SSH (port 22) & Tinc VPN (port 655) to the node on which it is running.
The node IP will be determined autometically from environment variables & acoordingly it will apply iptables rule.

In case you need any specific port forwarding please add feedback
