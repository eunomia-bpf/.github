# Hi there 👋 This is eunomia-bpf project

eunomia is an organization oriented for exploring and improving the toolchains and runtimes for eBPF.

Our projects include:

- [bpftime](https://github.com/eunomia-bpf/bpftime): bpftime is a High-Performance userspace eBPF runtime and General Extension Framework designed for userspace. You can extern eBPF to anywhere you want as a *General Extension Framework*, while compatible with current eBPF ecosystem. It enables faster Uprobe, USDT, Syscall hooks, XDP, and more event sources by bypassing the kernel and utilizing an optimized compiler like LLVM.
- [llvmbpf](https://github.com/eunomia-bpf/llvmbpf): Userspace eBPF VM with llvm JIT/AOT compiler. The core component for bpftime without application, event, maps support.
- [Wasm-bpf](https://github.com/eunomia-bpf/wasm-bpf): Cooprated with [WasmEdge](https://github.com/WasmEdge/WasmEdge), we build the first user-space development library, toolchain, and runtime for general eBPF programs based on WebAssembly, allows lightweight Wasm sandboxes to deploy and control eBPF applications in k8s clusters.
- [GPTtrace](https://github.com/eunomia-bpf/GPTtrace): The first tool generates eBPF programs and traces the Linux kernel through natural language. With our AI agents, it can produce correct eBPF programs on 80\%, while a baseline of GPT-4 is 30\%.
- [eunomia-bpf](https://github.com/eunomia-bpf/eunomia-bpf): A tool to help developers build, distribute and run eBPF programs easier with JSON and Webassembly OCI images

For more interesting projects and details, please refer to our [website](https://eunomia.dev)!

---

## News

- **Our Paper [Extending Applications Safely and Efficiently](https://www.usenix.org/conference/osdi25/presentation/zheng-yusheng) Got accepted by OSDI'25!**
- "eBPF and Wasm: Unifying Userspace Extensions With Bpftime" at [KubeCon Europe 2025](https://sched.co/1txFJ)
- "bpftime: Userspace eBPF Runtime for Network and Observability" at [eBPF summit 2024](https://ebpf.io/summit-2024-schedule/)
- "bpftime: Fast uprobes with user space BPF runtime" at [Linux Plumbers Conference 2023](https://lpc.events/event/17/abstracts/1741/)
- "eBPF + Wasm: Lightweight Observability on Steroids" at [KubeCon North American 2023](https://sched.co/1R2uf) and also [Arxiv](https://arxiv.org/abs/2408.04856v1)
- "eunomia-bpf: Lightweight Development Framework for eBPF and Wasm" at [Apsara Conference 2022](https://www.alibabacloud.com/blog/eunomia-bpf-the-lightweight-development-framework-for-ebpf-and-webassembly-is-now-available_599688)

---

Want to learn more about eBPF? Checkout our eBPF developer tutorial and examples!

- Website: https://eunomia.dev/tutorials
- Github code repo and examples: https://github.com/eunomia-bpf/bpf-developer-tutorial
- Blogs: https://eunomia.dev/blogs/

- "Kgent: Kernel Extensions Large Language Model Agent" at [eBPF '24: Proceedings of the ACM SIGCOMM 2024 Workshop on eBPF and Kernel Extensions](https://dl.acm.org/doi/10.1145/3672197.3673434)
- "bpftime: userspace eBPF Runtime for Uprobe, Syscall and Kernel-User Interactions" at https://arxiv.org/abs/2311.07923
- "Code-Survey: An LLM-Driven Methodology for Analyzing Large-Scale Codebases" at https://arxiv.org/abs/2410.01837 and https://github.com/eunomia-bpf/code-survey
---

Contact us:

- Discord: [https://discord.gg/jvM73AFdB8](https://discord.gg/jvM73AFdB8)
- Email: team@eunomia.dev
