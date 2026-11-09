# Kentaro Sato | Independent Research

Independent researcher working across AI alignment, multi-agent systems, efficient model computation, and measurement theory.

My research focuses on a recurring question:

**When information or system states are transformed, compressed, updated, or passed between components, what remains reliable, what can fail, and how can we verify the difference?**

The projects below address this question in different technical domains. They are independent research efforts, not claims of a single unified theory.

## Independent Research: Three Research Tracks

### 1. AI Systems & Alignment

**How can long-horizon AI systems preserve information integrity, authority boundaries, and reliable coordination?**

- **[Boundary-Preserving Alignment](https://github.com/metaSATOKEN/Boundary-Preserving-Alignment)**  
  A position paper on governed artifact promotion, bounded authority, provenance, human oversight, and the conditions under which AI-generated information may legitimately influence consequential actions.  
  [Paper (Zenodo)](https://doi.org/10.5281/zenodo.23969376)

- **[MRSI: Memory, Records, and Multi-Agent Coordination](https://github.com/metaSATOKEN/MRSI)**  
  Four experimental papers and a technical synthesis examining provenance errors, memory repair, agreement quality, and approval boundaries in two- and three-role LLM systems.  
  [Collected Edition (Zenodo)](https://doi.org/10.5281/zenodo.23971186)

### 2. Efficient Model Computation

**How can we reduce the computational cost of language models while understanding and controlling the resulting errors?**

- **[NSN: Norm-Separated KV Cache Quantization](https://github.com/metaSATOKEN/nsn)**  
  Training-free low-bit KV-cache compression, including evaluations across model architectures, packed 3-bit caches for looped Transformers, and fused Triton execution.

- **[Norm-Separated Quantization](https://github.com/metaSATOKEN/norm-separated-quantization)**  
  Investigation of catastrophic INT4 quantization failures, separating magnitude and direction to identify and mitigate distinct failure mechanisms.

- **[LAB: Lyapunov-Aware Bit Allocation](https://github.com/metaSATOKEN/lab-ssm)**  
  State-space model quantization using error persistence, output sensitivity, and dynamic range to allocate precision across recurrent states.

### 3. Measurement & Auditable Decisions

**When a measurement, calibration, or model-derived score changes, under what conditions can its conclusions still be trusted?**

- **[First-Order Probes](https://github.com/metaSATOKEN/First-Order-Probes)**  
  Auditable sensor consistency checks and calibration updates under source shifts and contamination. Separates false-alarm evidence, fault-detection sensitivity, and decision coverage. Includes simulation code, Lean proofs, and original experimental data.

- **[Transformer Representation Geometry](https://github.com/metaSATOKEN/manifold_topology_experiment)**  
  Empirical analysis of hidden-state geometry, principal-component concentration, and transferable feature readouts, including controls that challenge misleading geometric interpretations.

---

## Where to Start

| Interested in… | Recommended starting point |
|---|---|
| AI alignment and agent governance | [Boundary-Preserving Alignment](https://github.com/metaSATOKEN/Boundary-Preserving-Alignment) |
| Multi-agent memory, provenance, and coordination | [MRSI](https://github.com/metaSATOKEN/MRSI) |
| Efficient LLM inference and quantization | [NSN](https://github.com/metaSATOKEN/nsn) |
| Statistical auditing and calibration reliability | [First-Order Probes](https://github.com/metaSATOKEN/First-Order-Probes) |
| Transformer internal representations | [Representation Geometry](https://github.com/metaSATOKEN/manifold_topology_experiment) |

## Research Approach

My work combines theoretical analysis, controlled experiments, implementation, and reproducible evaluation.

I aim to distinguish:

- **Observed results from theoretical guarantees**
- **Task success from system-level correctness**
- **Model capability from operational authority**
- **Detection performance from the reliability of the resulting decisions**
- **Supported findings from unresolved or exploratory results**

Where available, repositories include manuscripts, code, saved results, experimental protocols, and reproducibility instructions.

**Negative results, limitations, and unresolved comparisons are part of the research record.**

---

*Independent Research | Japan · 2026*
