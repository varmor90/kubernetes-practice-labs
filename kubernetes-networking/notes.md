# Notes – Networking

– Containers inside the same Pod talk via `localhost`. Easy.  
– Different Pods = separate IPs. Communication works across nodes, but IPs can change.  
– Using just IPs = risky. Env vars help, but DNS is best.  
– Service gives a stable name. ClusterIP by default.  
– Multi-container Pods: useful when containers must share the same volume or process (e.g. logging sidecar).  
– Reverse proxy (like Nginx) in front of multiple backend services makes frontend setup easier.

🔧 Next step:  
Try setting up a simple frontend + multiple backends + Nginx as reverse proxy. Bonus if I can break it and fix it 😅
