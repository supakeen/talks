---
marp: true
theme: uncover
---

<!-- paginate: false -->

# What is image-based Linux?

Simon de Vlieger \<cmdr@supakeen.com\>

---

<!-- paginate: true -->
<!-- header: What is image-based Linux? -->

#  Linux

---

<!-- header: What is image-based Linux? -->

# Image Based

The system as a whole.

- Update **everything** in one operation.
- The system is immutable\*.

---

# Targets

IoT, Edge, Automotive.

- No physical security.
- Hard to get to.
- Recovery from failure.

---

# ostree

`ostree` manages your filesystem for you.

Used by *Fedora IoT*, *Fedora CoreOS*, *EndlessOS*, *CentOS Automotive*, *RHEL for Edge*, and many others.

---

# Unified Kernel Image

Your `kernel` and `initramfs`, as a single signed binary.


---

# fsverity

`fsverity` makes sure your filesystem has not been tampered with.

---

# composefs

`composefs` allows an overlay that propagates the `fsverity` status. Allowing for a writable overlay without losing validity.

---

# This Talk

https://github.com/supakeen/talks
