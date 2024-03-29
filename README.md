# What's the silliest way of implementing Kubernetes?

> You know what kubernetes is? Do you know what it is? It's 20 while true loops in a trench coat pretending to be a control plane. And that's fine! - [Hazel Weakley](https://www.linkedin.com/posts/hazelweakly_if-your-service-cant-be-run-on-a-laptop-activity-7164055151618584576-PpfU)

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
