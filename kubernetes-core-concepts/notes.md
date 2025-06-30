Notes on core concepts
# Notes – Core Concepts

– Kubernetes doesn’t create infrastructure. I need to set that up myself (e.g. with Terraform). K8s just manages containers.  
– Deployment = a recipe for how Pods should run. YAML > CLI for real control.  
– Service = stable access to Pods that can come and go. ClusterIP = internal, NodePort = testable from outside.  
– Label = tag. Selector = filter using that tag. Simple but powerful.  
– Rollback = undo for Deployments. Super useful.  
– Liveness probe = not just “is it running?”, but “is it actually alive and doing something?”

🔧 Next step:  
Try writing a full Deployment YAML from scratch — no copy-paste.
