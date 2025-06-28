# Welcome to RedkillTech!

Redkill Tech is building the next-generation, open-source, safety-critical software stack designed and developed entirely in India. 
Our platform targets aerospace, defense, automotive, space-tech, and medical systems, where safety, reliability, and real-time guarantees are non-negotiable.

Our mission is to create a sovereign, certifiable, and developer-friendly alternative to legacy foreign safety OS platforms. 
By combining modern system design, formal methods, and transparent licensing, we aim to put control back in the hands of Indian OEMs and innovators.

The Redkill Safety Stack is being built from first principles, with a focus on formal verification, safety certification, and hardware-software co-design. It consists of:

## Microkernel
A formally verified, safety-certified, fully preemptive SMP microkernel designed for deterministic real-time behavior and strong memory protection. Features include:

- Preemptive multi-threading
- Priority based hard real-time scheduling
- Memory partitioning and virtual memory support
- Minimal Trusted Computing Base (TCB)

## Hypervisor
A type-1 safety certified hypervisor purpose-built for safety-critical applications. It ensures:

- Spatial and temporal isolation of guests
- Integration of mixed-criticality systems

## Userspace
Our userspace layer is modular and safety-certified:

- Peripheral drivers designed for real-time and safety
- Middleware for networking, file systems, and time synchronization
- Application frameworks for mission logic with restricted privilege execution
