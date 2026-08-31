# 💻 Interactive Computer Architecture Simulators

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-brightgreen.svg)](https://dag94s.github.io/computer-architecture-simulators/)
[![Author](https://img.shields.io/badge/Author-DAG94S-blue.svg)](https://github.com/DAG94S)

A collection of interactive, web-based visual simulators designed for teaching and exploring core concepts in **Computer Architecture**, **Operating Systems**, and **Hardware-Software Interaction**.

Developed by **Diego García** (M.Sc. Software Engineering, University Lecturer in Computer Architecture).

---

## 🚀 Live Demos

Try the interactive simulators directly in your browser:

👉 **[Launch Main Simulator Hub](https://dag94s.github.io/computer-architecture-simulators/)**

### Included Simulators:

1. **[RAM & Cache Memory Simulator](https://dag94s.github.io/computer-architecture-simulators/simulators/cache-memory/)**
   - Direct Mapping, Fully Associative, and Set-Associative Cache organization.
   - Real-time visualization of cache hits, misses, latency, and memory block updates.

2. **[Page Fault & Replacement Simulator](https://dag94s.github.io/computer-architecture-simulators/simulators/page-fault/)**
   - Visual simulation of Virtual Memory Page Replacement algorithms: **FIFO**, **LRU**, **Optimal**, and **Clock**.
   - Step-by-step frame allocation, page fault tracking, and Belady's Anomaly demonstration.

3. **[Virtual Memory Paging Simulator](https://dag94s.github.io/computer-architecture-simulators/simulators/paging-system/)**
   - Logical-to-Physical Address Translation using Page Tables and TLB (Translation Lookaside Buffer).
   - Interactive breakdown of page numbers, frame numbers, and byte offsets.

4. **[Instruction Cycle & Pipeline Suite](https://dag94s.github.io/computer-architecture-simulators/simulators/instruction-cycle/)**
   - Step-by-step micro-operation execution: **Fetch**, **Decode**, and **Execute** stages.
   - Multi-stage CPU Instruction Pipeline simulator showing pipeline throughput, structural/data hazards, and stall cycles.

---

## 🛠️ Tech Stack & Philosophy

- **Frontend:** Pure Vanilla JavaScript (ES6+), HTML5, CSS3, Tailwind CSS.
- **Zero Dependencies:** Runs natively in any web browser without Node.js, compilation, or server setup.
- **Pedagogical Focus:** Built specifically to provide intuitive visual feedback for computer engineering and computer science students.

---

## 📦 Local Installation & Usage

No build tools required! Simply clone the repository and open `index.html` in your web browser:

```bash
git clone https://github.com/DAG94S/computer-architecture-simulators.git
cd computer-architecture-simulators
# Open index.html in your default browser
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
