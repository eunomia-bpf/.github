## Hi there 👋 This is eunomia-bpf project

eunomia lab is an organization oriented for exploring and improving the toolchains and runtimes for eBPF.

Our projects include:

- [bpftime](https://github.com/eunomia-bpf/bpftime): A userspace eBPF runtime. It offers rapid uprobe 10x faster than kernel uprobes, and syscall hook capabilities. It's compatible with kernel eBPF and existing eBPF toolchains, and can be injected into any running process without restart or manual recompilation. It can work with kernel eBPF or the eBPF runtime in other userspace processes.
- [Wasm-bpf](https://github.com/eunomia-bpf/wasm-bpf): Cooprated with [WaseEdge](https://github.com/WasmEdge/WasmEdge), we build the first user-space development library, toolchain, and runtime for general eBPF programs based on WebAssembly, allows lightweight Wasm sandboxes to deploy and control eBPF applications in k8s clusters.
- [GPTtrace](https://github.com/eunomia-bpf/GPTtrace): The first tool generates eBPF programs and traces the Linux kernel through natural language. With our AI agents, it can produce correct eBPF programs on 80\%, while a baseline of GPT-4 is 30\%.
- [eunomia-bpf](https://github.com/eunomia-bpf/eunomia-bpf): A tool to help developers build, distribute and run eBPF programs easier with JSON and Webassembly OCI images

For more interesting projects and details, please refer to our [website](https://eunomia.dev)!

---

Want to learn more about eBPF? Checkout our eBPF developer tutorial and examples!

- Website: https://eunomia.dev/tutorials
- Github code repo and examples: https://github.com/eunomia-bpf/bpf-developer-tutorial
- Blogs: https://eunomia.dev/blogs/

---

- "bpftime: Fast uprobes with user space BPF runtime" at [Linux Plumbers Conference 2023](https://lpc.events/event/17/abstracts/1741/)
- "eBPF + Wasm: Lightweight Observability on Steroids" at [KubeCon North American 2023](https://sched.co/1R2uf)
- "eunomia-bpf: Lightweight Development Framework for eBPF and Wasm" at [Apsara Conference 2022](https://www.alibabacloud.com/blog/eunomia-bpf-the-lightweight-development-framework-for-ebpf-and-webassembly-is-now-available_599688)
- "KEN: Kernel Extensions using Natural Language" at https://arxiv.org/abs/2312.05531
- "bpftime: userspace eBPF Runtime for Uprobe, Syscall and Kernel-User Interactions" at https://arxiv.org/abs/2311.07923

