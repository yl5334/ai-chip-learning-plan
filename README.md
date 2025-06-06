# ai-chip-learning-plan

# AI Chip Learning Plan 📚

This repository documents a 24-week weekend learning plan focused on building a solid foundation in AI chip design, dataflow architecture, RTL implementation, and compiler optimization. The plan is designed for working engineers with limited weekday time and aims to bridge the gap from basic computer architecture to advanced AI accelerator development.

## 🧠 Learning Focus

The full plan is divided into 4 major stages:

### 0. Foundations (Weeks 1–4)
- Computer systems fundamentals (CPU, memory hierarchy, ISA)
- Deep learning basics (MLP, convolution, GEMM)

### I. AI Chip Architecture (Weeks 5–11)
- GEMM & convolution workloads
- Data reuse & memory hierarchy design
- Dataflow strategies: weight stationary, output stationary, row stationary
- Systolic array, tiling, NoC communication

### II. Dataflow Modeling & RTL Design (Weeks 12–18)
- DAG construction and scheduling (ASAP/ALAP)
- RTL pipeline modeling and token control
- FIFO design and function-level parallelism using HLS

### III. Compiler Mapping & Optimization (Weeks 19–24)
- IR design and schedule representation (TVM/XLA/Halide)
- Operator fusion, memory planning
- Mapping IR to RTL with tools like CIRCT

---

## 🗂️ Weekly Structure

Each week will contain:
- 🎯 Learning objectives
- 📚 Recommended readings or videos
- ✅ Practical tasks
- 📝 Notes in `/week_xx_*.md`

---

## 🛠️ Tools & Frameworks

This plan may include examples or references using:
- Xilinx Vivado HLS
- TVM / MLIR / CIRCT
- Verilog / SystemVerilog / Python
- AI frameworks like PyTorch or TensorFlow (for workload analysis)

---

## 🚀 Getting Started

Start from [`week_01_intro.md`](./week_01_intro.md) once it’s uploaded. New content will be added every Friday.  
If you’d like to follow along, feel free to **watch** this repo and check back weekly.

---

## 🙋 About

This learning plan is personally maintained and tailored for part-time weekend learning, especially for professionals involved in ASIC/FPGA design who wish to gain full-stack understanding of AI accelerator development.
