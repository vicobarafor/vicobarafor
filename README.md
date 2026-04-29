# Victor Obarafor

Researcher in Federated Learning and Trustworthy AI (PhD)  
https://victor-website-one.vercel.app/

---

## Research Focus

- Federated learning under non-IID data  
- Training instability and failure modes  
- Robust aggregation and optimization  
- Personalization under heterogeneity  
- Geometry of distributed updates  

---

## Research Direction

Federated learning systems are typically developed under idealized assumptions.

In practice, **heterogeneity, drift, and conflicting client updates introduce instability** that standard methods do not address.

My work focuses on a central question:

> **When and why does federated learning fail under real-world conditions?**

The goal is to understand these failure modes and design methods that remain stable, reliable, and scalable in realistic distributed environments.

---

## Research Program

This research is organized around three connected directions.

### Robust Federated Learning under Non-IID Data
Study of aggregation methods under distribution shift, drift, and heterogeneous client behavior.

### Personalization under Heterogeneity
Analysis of how much individual clients should adapt shared models, and when personalization improves or harms global performance.

### Geometry and Instability in Federated LoRA
Investigation of training dynamics through update geometry, including alignment, conflict, and early predictors of failure.

---

## Selected Work

- **[robust-federated-learning-noniid](https://github.com/vicobarafor/robust-federated-learning-noniid)**  
  Drift-aware aggregation methods for federated learning under heterogeneous client partitions.

- **[federated-personalization-depth](https://github.com/vicobarafor/federated-personalization-depth)**  
  Client-specific adaptation depth in federated systems.

- **[federated-lora-geometry](https://github.com/vicobarafor/federated-lora-geometry)**  
  Geometry, instability, and early predictors in federated LoRA.

---

## Perspective

Many current federated learning methods focus on average-case performance.

However, in realistic settings, systems often fail due to:
- conflicting client updates  
- distributional imbalance  
- unstable optimization dynamics  

Understanding and addressing these issues requires moving beyond standard benchmarks toward **robust, failure-aware system design**.

---

## Ongoing Work

- Stability-aware aggregation methods  
- Early indicators of training collapse  
- Scaling behavior under increasing heterogeneity  
- Geometry-informed optimization strategies  

---

## Notes

This profile represents an ongoing research program on **stability, robustness, and failure modes in federated learning under non-IID data**.
