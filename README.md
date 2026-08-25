# 💫 About Me
CS undergrad @ UoM. Interested in C/C++ systems programming, concurrency, and performance engineering.

# 🎯 Current Focus
* Low-level systems programming (C/C++/Rust)
* Studying operating systems and networking fundamentals (Linux, self-hosting)
* Practicing strong fundamentals in backend system architecture (.NET)

# 🔧 Current Projects

## [BVH-Builder](https://github.com/ms1d/bvh-builder)

C++23 Bounding Volume Hierarchy (BVH) builder that runs concurrently on the CPU

### Features
- Daemon-client architecture to minimise thread/memory allocations (systemd friendly)
- Low latency concurrent building via a [custom thread pool implementation](https://github.com/ms1d/thread-poollib)
- Efficient memory allocations via [custom bump and arena allocators](https://github.com/ms1d/memory-poollib)

### Planned features
- Output tree evaluation for traversal efficiency
- SAH binning to improve tree quality

### Benchmarks
- 1024-thread stress tests showed ~30–40x throughput improvements after reducing false sharing with atomic alignment/padding optimisations, improving scalability
- Improved BVH construction throughput by ~50% through improved scheduling
- 20M tris/s end-to-end on Ryzen 7 8845HS

## [Path Tracer](https://github.com/ms1d/path-tracer-engine)

C++20 CLI renderer that runs concurrently on both the CPU and GPU

### Planned Features
- Support for UDP previews & TCP checkpoints + final results
- Ports for CPU & GPU platforms
- BVH acceleration

## [Maths Libraries](https://github.com/ms1d/matlib)

C++20 matrix and vector libraries for linear algebra applications

### Features
- CUDA compatible
- Test suite for accuracy of floating point calculations

# 🌐 Socials
[![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:mahadsiddiqui07@outlook.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ms1d) 

# 💻 Tech Stack
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=flat&logo=csharp&logoColor=white)
![.Net](https://img.shields.io/badge/.NET-5C2D91?style=flat&logo=.net&logoColor=white)
![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=flat&logo=unity&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=flat&logo=microsoftazure&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=flat&logo=githubactions&logoColor=white)

# Other Facts
Arch + Neovim btw
