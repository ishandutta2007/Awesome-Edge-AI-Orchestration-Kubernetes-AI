# Awesome-Edge-AI-Orchestration-Kubernetes-AI

markdown

## Top Edge AI Orchestration & Kubernetes AI



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Edge Kubernetes Distributions, Cloud-Edge Workload Orchestration, Edge AI Inference & Distributed GPU Clusters*  

**Last updated: November 2026**



This repository tracks notable **SaaS/Enterprise platforms** and **open-source projects** for **Edge AI Orchestration & Kubernetes AI**. These tools power lightweight Kubernetes clusters on resource-constrained edge nodes, cloud-edge device synchronization, federated AI model deployment, GPU operator scheduling, and autonomous edge inference across industrial IoT, retail, telecom, and robotics infrastructure.



**Examples** include AWS IoT Greengrass, Azure IoT Edge, Google Distributed Cloud Edge, Red Hat OpenShift Edge, NVIDIA Fleet Command, SUSE Edge, Zededa, BalenaCloud, Avassa, and Spectro Cloud Palette Edge (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for lightweight edge Kubernetes (`K3s`, `MicroK8s`, `Talos`), cloud-native edge frameworks (`KubeEdge`, `OpenYurt`, `Akri`, `Baetyl`, `EdgeX Foundry`), and Kubernetes AI/GPU orchestration (`NVIDIA GPU Operator`, `KServe`, `vLLM`, `Ray`, `KubeRay`) — ideal for MLOps engineers, edge infrastructure architects, and platform teams building distributed AI fleets.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS IoT Greengrass](https://amazon.com)**  

  Managed edge runtime and cloud service enabling devices to locally execute Lambda functions, Docker containers, and ML inference models with intermittent connectivity.



- **[Azure IoT Edge](https://microsoft.com)**  

  Cloud-managed service from Microsoft that deploys containerized workloads, Azure AI services, and custom machine learning models directly onto edge gateways.



- **[Google Distributed Cloud Edge](https://google.com)**  

  Fully managed hardware and software edge infrastructure bringing Google Cloud Kubernetes Engine (GKE) and Vertex AI inference closer to local data sources.



- **[Red Hat OpenShift Edge](https://redhat.com)**  

  Enterprise Kubernetes platform supporting single-node OpenShift, remote worker nodes, and zero-touch provisioning for telco and industrial edge AI deployments.



- **[NVIDIA Fleet Command](https://nvidia.com)**  

  Managed hybrid-cloud platform for securely deploying, updating, and monitoring containerized AI applications across distributed NVIDIA EGX and Jetson edge systems.



- **[ZEDEDA](https://zededa.com)**  

  Cloud-native edge orchestration SaaS built atop LF Edge EVE-OS for zero-trust provisioning, lifecycle management, and observability of distributed edge AI nodes.



- **[balenaCloud](https://balena.io)**  

  Managed container-based IoT and edge fleet management platform providing delta updates, remote VPN access, and hardware abstraction for ARM/x86 AI devices.



- **[Avassa](https://avassa.io)**  

  Application orchestration SaaS engineered specifically for distributed edge environments, enabling centralized lifecycle management of containerized workloads across retail and industrial sites.



- **[Spectro Cloud Palette Edge](https://spectrocloud.com)**  

  Enterprise Kubernetes management platform automating full-stack OS, K3s/RKE2, and GPU driver lifecycles across thousands of air-gapped or bandwidth-limited edge locations.



- **[SUSE Edge](https://suse.com)**  

  Commercial edge computing stack combining SUSE Linux Enterprise Micro, Rancher, and K3s for centralized lifecycle management of cloud-native edge clusters.



## Open-Source GitHub Projects



- **[NVKE (`dsx-ai-factory/nvke`)](https://github.com)**  

  Open-source Kubernetes-native AI and GPU orchestration framework designed to streamline accelerated AI factory and edge cluster deployments.



- **[KubeEdge (`kubeedge/kubeedge`)](https://github.com)**  

  Graduated CNCF project extending native Kubernetes containerized application orchestration and device management to hosts at the edge with offline autonomy.



- **[OpenYurt (`openyurtio/openyurt`)](https://github.com)**  

  CNCF open-source platform transforming standard upstream Kubernetes into an edge-ready cluster with node autonomy, edge-cloud tunneling, and unitized deployment.



- **[Rancher K3s (`k3s-io/k3s`)](https://github.com)**  

  Lightweight, CNCF-certified Kubernetes distribution packaged as a single <100MB binary optimized for ARM64, IoT gateways, and resource-constrained edge AI nodes.



- **[EdgeX Foundry (`edgexfoundry/edgex-go`)](https://github.com)**  

  LF Edge vendor-neutral open-source microservices framework providing plug-and-play Southbound device connectivity and Northbound data export for edge AI analytics.



- **[Baetyl (`baetyl/baetyl`)](https://github.com)**  

  LF Edge open-source cloud-native edge computing framework extending cloud computing, data processing, and AI model inference seamlessly to local edge devices.



- **[LF Edge Akraino (`akraino-edge-stack`)](https://lfedge.org)**  

  Linux Foundation open-source software stack offering tested, production-grade blueprints for telco, 5G MEC, industrial IoT, and carrier-scale edge AI infrastructure.



- **[MicroK8s (`canonical/microk8s`)](https://github.com)**  

  Canonical's zero-ops, single-package CNCF Kubernetes distribution featuring one-command addons for NVIDIA GPU acceleration, Kubeflow, and high-availability edge clustering.



- **[Talos Linux (`siderolabs/talos`)](https://github.com)**  

  Modern, immutable, API-driven Linux OS built strictly for Kubernetes, eliminating SSH and package drift across distributed bare-metal and edge GPU fleets.



- **[Akri (`project-akri/akri`)](https://github.com)**  

  CNCF Kubernetes resource interface that automatically discovers leaf devices (IP cameras, USB sensors, GPUs) and exposes them as schedulable cluster resources.



- **[SuperEdge (`superedge/superedge`)](https://github.com)**  

  Open-source container management system extending native Kubernetes to edge computing with distributed health checks, service groups, and edge-cloud tunnels.



- **[WasmEdge (`WasmEdge/WasmEdge`)](https://github.com)**  

  CNCF high-performance WebAssembly runtime tailored for edge computing and serverless AI inference with WASI-NN support for PyTorch, TensorFlow, and Llama.



- **[SpinKube (`spinkube/spin-operator`)](https://github.com)**  

  Open-source Kubernetes operator enabling ultra-fast, low-footprint WebAssembly workloads to run alongside traditional containers on edge clusters.



- **[EVE-OS (`lf-edge/eve`)](https://github.com)**  

  LF Edge bare-metal edge virtualization engine providing zero-trust security, remote attestation, and container/VM orchestration on distributed edge hardware.



- **[NVIDIA GPU Operator (`NVIDIA/gpu-operator`)](https://github.com)**  

  Open-source Kubernetes operator automating the provisioning of NVIDIA drivers, container toolkits, MIG partitioning, and DCGM monitoring across GPU nodes.



- **[KubeRay (`ray-project/kuberay`)](https://github.com)**  

  Open-source Kubernetes operator simplifying deployment and autoscaling of distributed Ray clusters for multi-node AI inference, training, and agent workflows.



- **[KServe (`kserve/kserve`)](https://github.com)**  

  Standardized serverless ML inference platform on Kubernetes supporting autoscaling, canary rollouts, and high-performance runtimes like vLLM, Triton, and PyTorch.



- **[vLLM (`vllm-project/vllm`)](https://github.com)**  

  High-throughput, memory-efficient LLM inference and serving engine widely deployed inside Kubernetes clusters via PagedAttention and OpenAI-compatible APIs.



- **[LocalAI (`mudler/LocalAI`)](https://github.com)**  

  Self-hosted, drop-in OpenAI API replacement running LLMs, multimodal, and audio models locally on consumer GPUs, CPUs, and edge Kubernetes nodes without cloud dependencies.



- **[Ollama (`ollama/ollama`)](https://github.com)**  

  Lightweight open-source model runner and REST server frequently containerized on edge K3s nodes for local quantization and low-latency LLM inference.



- **[Triton Inference Server (`triton-inference-server/server`)](https://github.com)**  

  NVIDIA's open-source multi-framework inference serving engine optimizing concurrent GPU/CPU model execution across TensorRT, ONNX, PyTorch, and OpenVINO.



- **[OpenVINO Model Server (`openvinotoolkit/model_server`)](https://github.com)**  

  Scalable, C++-based open-source microservice optimized for running computer vision and generative AI inference on Intel edge CPUs, iGPUs, and NPUs.



- **[Eclipse ioFog (`eclipse-iofog/Agent`)](https://github.com)**  

  Open-source edge compute network platform enabling developers to deploy and orchestrate microservices across heterogeneous edge hardware seamlessly.



- **[Fleet (`rancher/fleet`)](https://github.com)**  

  Open-source GitOps container management engine engineered by Rancher to manage up to a million Kubernetes clusters across edge and data center topologies.



### Additional Strong Open-Source Options



Use code with caution.

• Edge AI & Vision Pipelines like Frigate (blakeblackshear/frigate) and DeepStream / Savant (insight-platform/Savant) for hardware-accelerated real-time object detection on edge nodes.

• Lightweight Container & VM Runtimes like k0s (k0sproject/k0s) and Kairos (kairos-io/kairos) for immutable, zero-dependency edge Kubernetes operating systems.

• Edge Messaging & Telemetry like Eclipse Mosquitto (eclipse/mosquitto), EMQX (emqx/emqx), and NanoMQ (nanomq/nanomq) for ultra-lightweight MQTT brokering between sensors and AI inference pods.

• Distributed Storage for Edge K8s like Longhorn (longhorn/longhorn) and OpenEBS (openebs/openebs) for resilient persistent volumes holding local AI model weights.

• Edge Service Mesh & Networking like Cilium (cilium/cilium) and Tailscale / Headscale (juanfont/headscale) for encrypted eBPF networking and NAT traversal across remote edge sites.

Frameworks for building custom systems: Combine K3s or Talos Linux, KubeEdge / OpenYurt, NVIDIA GPU Operator, Triton / vLLM, and Rancher Fleet to build a self-hosted, GitOps-driven edge AI orchestration platform capable of autonomous local inference.



How to Contribute



1. Fork the repo.

2. Add/edit entries in README.md (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.

Star the repo if you find it useful!



Disclaimer



• This is a community-curated list — not exhaustive and not an endorsement.

• Edge AI deployments operate in physically accessible or intermittent-network environments; ensure secure boot, disk encryption, mutual TLS, and signed container images are enforced.

• Hardware acceleration (CUDA, ROCm, OpenVINO, Jetson JetPack) requires careful kernel and driver compatibility testing before rolling out over-the-air updates to remote edge fleets.

Made for MLOps engineers, edge infrastructure architects, Kubernetes operators, and embedded AI developers.

Let's make edge AI orchestration and distributed Kubernetes more open, resilient, and autonomous.
