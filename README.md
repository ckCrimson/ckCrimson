# Hi, I'm Aditya Kumar 👋

**Systems Engineer | High-Performance Computing | Backend Architect**

I specialize in bridging high-level Object-Oriented domain logic with bare-metal, hardware-accelerated execution. By day, I build robust, scalable enterprise backends and APIs using Java and Spring. By night, I architect high-performance mathematical frameworks to model complex stochastic dynamic systems.

### 🛠️ Core Tech Stack
* **Languages:** Python, Java, C++, C
* **High-Performance Compute:** JAX, Numba, NumPy, Hardware-Accelerated Vectorization (GPU/TPU)
* **Backend & Enterprise:** Spring Ecosystem, RESTful APIs, Distributed Systems
* **Mathematics:** Linear Algebra, Tensors, Markov Chains, Stochastic Modeling

---

### 🚀 Featured Architectures

#### 1. [Discrete State Engine (FDS Framework)](https://github.com/ckCrimson/discrete-state-engine)
A high-performance, Python-based stochastic physics engine engineered to bypass Python's computational overhead in complex iterative environments.

* **The Architecture:** Designed a "Dual-Flow Architecture" that enforces strict architectural separation. Components like the Field Mapper and Topology are entirely independent, communicating exclusively via decoupled, C-aligned Bridge Data objects.
  
* **The Performance:** Achieves near-C execution speeds in the simulation "hot loop" using **Numba JIT compilation**, custom **CSR (Compressed Sparse Row)** memory bridging, and strictly managed C-contiguous NumPy arrays.
  
* **The Impact:** Allows users to execute millions of iterative coordinate updates and overlapping multi-particle fields in $O(1)$ time without manually managing low-level pointers.
  
* * 🧪 Run the Interactive Colab Demo: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ilXh1Z-xg83XilleJGA4lG8OXFCWFaR8?usp=sharing)

#### 2. [Hybrid ECS: Dual-Flow Architecture](https://github.com/ckCrimson/Hybrid_ECS_RANDOM_WALKER.git)
A generalized Entity Component System explicitly designed to bypass the "Python Object Tax."

* **The Architecture:** Flattens pure OOP hierarchical structures into contiguous C-arrays using strict memory contracts.
  
* **The Performance:** Achieved a **~300x execution speedup** on a 100,000-entity spatial simulation by using Dependency Injection to swap between CPU mutation (Numba) and GPU vectorization (JAX).
  
* 🧪 Run the Interactive Colab Benchmark: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/12PKDNMeRHfSFkAyzqzX700PppJcD3SsM/view?usp=sharing)


#### 3. [Legacy Field Dynamic System (JAX Engine)](https://github.com/ckCrimson/Field_Dynamic_System.git)
The mathematical predecessor to the Discrete State Engine, built to explore tensor-based operations. 

* **The Architecture:** Explores the mathematical foundations of State Spaces, Vector Fields, and custom generalized Markov chain engines.
  
* **The Performance:** Leverages JAX to linearize complex spatial evaluations, allowing heavy probabilistic models to run directly on hardware-accelerated infrastructure.
---

### 📫 Connect with me
* **LinkedIn:** (www.linkedin.com/in/adityakumar70042)
* **Email Id:** (ak7004271114@gmail.com)
* **Current Focus:** Targeting research-level engineering roles and rigorous systems optimization challenges.
