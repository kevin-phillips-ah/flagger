## Earnin Flagger PoC

This subdirectory contains all of the rationale for the Earnin fork of Flagger and information regarding the proof-of-concept work done so far.

### What the Fork?

While flagger does have OOTB support for AWS App Mesh, the upstream implementation has the following short-comings.

  * `VirtualNode`, `VirtualRouter`, and `VirtualService` are assumed to be created and managed by controller. Reconcile fails if any exist prior.
  * Traffic shift facilitated by label selector changes to ClusterIP service.
  * 

### Proof-of-Concept

#### Design

#### Setup

#### Verification
