# Kubernetes internals:

## Understanding the architecture

Before you look at how Kubernetes does what it does, let’s take a closer look at the components that make up a Kubernetes cluster. 
 * Kubernetes cluster is split into two parts:
    *  The Kubernetes Control Plane 
    * The (worker) nodes
- Let’s look more closely at what these two parts do and what’s running inside them.
### COMPONENTS OF THE CONTROL PLANE
The Control Plane is what controls and makes the whole cluster function.the components that make up the Control Plane are
  * The etcd distributed persistent storage 
  * The API server
  * The Scheduler
  * The Controller Manager
