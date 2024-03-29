# What's the silliest way of implementing Kubernetes?

A very silly idea. Obviously in Rust.

## Todo

- [ ] A kubelet implementation
- [ ] A kube api implementation
- [ ] A scheduler implementation

## Assumptions / Simplifications

- Authentication? LOL
- RBAC? Nope
- Containerd only
- CSI? Nope
- CNI - maybe?
- Control plane data? In-memory. Might write it out as a YAML file or something equally silly

## Aims

- Worker and master node
- Schedule a Pod on a worker node
