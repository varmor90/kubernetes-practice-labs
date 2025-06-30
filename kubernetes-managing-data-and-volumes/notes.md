# Notes – Data and Volumes

– Volumes in K8s are more flexible than in Docker. They survive container restarts (but not always Pod deletion).  
– `emptyDir` = basic temp storage that lives as long as the Pod lives.  
– `hostPath` = maps a folder from the host machine. Works, but not great for multi-node clusters.  
– CSI = like a plugin system for real-world storage (e.g. cloud disks). Didn’t dive deep yet.  
– Persistent Volumes (PV) = cluster-level storage. Not tied to a specific Pod.  
– Persistent Volume Claim (PVC) = a request for space. Pod gets storage through the claim.

🔧 Next step:  
Try building a Deployment that uses a PVC from scratch. Also want to test what happens if the Pod dies.
