api-server crash

/var/log/pods
/var/log/syslog

journalctl -u unit
journalctl | grep unit


[x] Playground Cilium 
[x] APIServer crash
[x] API Server missconfigured
[ ] API Server NodeRestriction
[ ] AppArmor
[ ] Auditing Enable Audit Logging
[ ] CertificateSigningRequest sign manually
[ ] CertificateSigningRequests sign via API
[ ] CIS Benchmarks fix Controlplane
[ ] Container Hardening
[ ] Container Image Footprint User
[ ] Container Namespaces Docker
[ ] Falco Change Rule
[ ] ImagePolicyWebhook Setup
[ ] Image Use Digest
[ ] Image Vulnerability Scanning Trivy
[ ] Immutability Readonly Filesystem
[ ] Ingress Create
[ ] Ingress Secure
[ ] NetworkPolicy Create Default Deny
[ ] NetworkPolicy Metadata Protection
[ ] NetworkPolicy Namespace Selector
[ ] Privilege Escalation Containers
[ ] Privileged Containers
[ ] RBAC ServiceAccount Permissions
[ ] RBAC User Permissions
[ ] Sandbox gVisor
[ ] Secret ETCD Encryption
[x] Secret Access in PODS   
[ ] Secret Read and Decode
[ ] Secret ServiceAccount Pod
[ ] ServiceAccount Token Mounting
[ ] Static Manual Analysis Docker
[x] Static Manual Analysis K8s
    securityContext, dropCapabilities, privileged
[ ] Syscall Activity Strace
[ ] System Hardening Close Open Ports
[ ] System Hardening Manage Packages
[ ] Verify Platform Binaries 
 
