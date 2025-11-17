[x] Playground
[x] Playground Cilium 
[x] APIServer crash
    - /var/log/pods
    - /var/log/syslog
    - journalctl -u unut
    - journalctl | grep unit
[x] API Server missconfigured
[x] API Server NodeRestriction
    - [x] What the NodeRestriction does? 
        - node-restriction.kubernetes.io label is reserved for administrators to 
          label their Node objects for workload isolation purposes, and kubelets 
          will not be allowed to modify labels with that prefix.
        - https://kubernetes.io/docs/reference/access-authn-authz/admission-controllers/#noderestriction
[x] AppArmor
    - [ ] do tutorials on AppArmor
        - apparmor_parser /root/profile
        - aa-status | grep nginx
    - apparmor_status
    - k explain deploy.spec.template.spec.securityContext.appArmorProfile   
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
[x] Secret ServiceAccount Pod
    - k explain very handy
    - k run my-pod --dry-run=client -o yaml > pod.yaml  
[ ] ServiceAccount Token Mounting
[ ] Static Manual Analysis Docker
[x] Static Manual Analysis K8s
    - securityContext 
    - dropCapabilities 
    - privileged
[ ] Syscall Activity Strace
[ ] System Hardening Close Open Ports
[ ] System Hardening Manage Packages
[x] Verify Platform Binaries 
    - sha256sum
    - systemctl status kubelet > check kubelet.service > find bin
        - /usr/bin/kubelet version
        - sha256sum it's bin
        - sha256sum downloaded bin
        - /usr/bin/kubelet version


