# Hi, I'm Aditya Kumar 👋

**Software Engineer | Complex Systems Modeler| High Performence Computing | Backend Architect**

I am a Software Engineer with two years of enterprise experience specializing in bridging high-level Object-Oriented domain logic with bare-metal, hardware-accelerated execution. By day, I build robust, scalable enterprise products and backend APIs using Java and the Spring ecosystem at TCS. By night, I architect high-performance computational mathematics frameworks and stochastic simulation engines in Python.

### 🎯 Career Objectives & Domains
* **Target Roles:** Scientific Software Engineer, Simulation & Modeling Engineer, R&D Systems Architect.
* **Domain Focus:** Complex Systems Modeling, High-Performance Computing (HPC), and translating heavy computational mathematics into hardware-optimized code.

---

### 🛠️ Technical Competencies & Engineering Practices

* **Languages:** Python, Java, C++, C
* **Computational Math & Simulation:** NumPy, JAX, Mathematical Modeling, Stochastic Systems. 
* **Performance Optimization:** Numba (JIT compilation), CSR Memory Bridging, contiguous memory allocation.
* **System Architecture:** Enterprise System Design, Decoupled Component Managers, Data-Oriented Design (DOD).
* **Enterprise Backend:** Java Spring Boot, RESTful API design, Scalable Product Engineering.

---

### 🚀 Featured Architectures & Physics Engines

#### 1. [FastSpatialEngine: Multi-Threaded Query Kernel](https://github.com/ckCrimson/SwarmCore.git)
A high-performance, bare-metal 3D spatial proximity engine engineered in native C++20 with seamless Python interoperability.

* **The Architecture:** Implements a Struct of Arrays (SoA) memory layout and a 3D Uniform Spatial Hash Grid, reducing proximity query time complexity from an $O(N^2)$ brute-force down to an $O(N)$ hash-bucket lookup.
  
* **The Performance:** Benchmarked to process **1,000,000 active entities at 60 FPS** by leveraging data-parallelism, custom memory arena allocation, and CPU cache-line prefetching optimization.
  
* **The Interoperability:** Integrated **pybind11** cross-language bindings to expose the high-throughput native C++ compute kernel to Python simulation environments with zero-copy data passing.

###  Upcoming Architectures (v2 Roadmap)

* **Cross-Language Bake-and-Sync Architecture:** Engineering a dual-layer simulation pipeline bridging a high-level **C#/.NET** domain layer with a native **C++20** backend. High-level entity configurations are "baked" into tightly packed contiguous memory regions, using an optimized synchronization layer to replicate states across the managed/unmanaged boundary with minimal marshaling overhead.
* **Narrow-Phase Collision Detection:** Expanding the `SwarmCore` kernel to move from broad-phase spatial hashing to exact, primitive-level collision detection and resolution algorithms optimized for multi-core scaling.
* **Modular Physics Modules:** Devising a decoupled plugin architecture allowing researchers to hot-swap custom interaction fields (e.g., fluid dynamics, structural stress boundaries) into the unified compute loop.


#### 2. [Discrete State Engine (FDS Framework)](https://github.com/ckCrimson/discrete-state-engine)
A stochastic physics engine engineered to bypass Python's computational overhead in complex iterative environments.

* **The Architecture:** Designed a "Dual-Flow Architecture" that enforces strict separation between high-level mathematical rules and low-level memory operations.
  
* **The Performance:** Achieves near-C execution speeds in the simulation "hot loop" using Numba JIT, mapping coordinates to 64-bit aligned memory blocks.
  
* **The Impact:** Executes millions of iterative coordinate updates and overlapping multi-particle fields in $O(1)$ time without exposing users to low-level pointers.

  * 🧪 Run the Benchmark: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ilXh1Z-xg83XilleJGA4lG8OXFCWFaR8?usp=sharing)
 
#### 3. [Legacy Field Dynamic System (JAX Engine)](https://github.com/ckCrimson/Field_Dynamic_System.git)
The mathematical predecessor to the Discrete State Engine, built to explore tensor-based operations. 

* **The Concept:** Explores the mathematical foundations of State Spaces, Vector Fields, and custom generalized Markov chain engines.
  
* **The Execution:** Leverages JAX to linearize complex spatial evaluations, allowing heavy probabilistic models to run directly on hardware-accelerated infrastructure.


#### 4. [Hybrid ECS: Dual-Flow Architecture](https://github.com/ckCrimson/Hybrid_ECS_RANDOM_WALKER.git)
A generalized Entity Component System explicitly designed to bypass the "Python Object Tax."

* **The Architecture:** Flattens pure OOP hierarchical structures into contiguous C-arrays using strict memory contracts.
  
* **The Performance:** Achieved a **~300x execution speedup** on a 100,000-entity spatial simulation by swapping between CPU mutation (Numba) and GPU vectorization (JAX).
  
* 🧪 Run the Benchmark: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/12PKDNMeRHfSFkAyzqzX700PppJcD3SsM/view?usp=sharing)


---

### 🎓 Professional Background
* **Product Engineer & Backend Developer** @ Tata Consultancy Services (TCS) — *(2024 - Present)*
* **B.Tech in Computer Science & Engineering** @ Institute of Engineering and Management (IEM)

---

### 📫 Connect with me
* **LinkedIn:** [linkedin.com/in/adityakumar70042](https://www.linkedin.com/in/adityakumar70042)
* **Email:** ak7004271114@gmail.com
