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

Federated learning systems are typically studied under idealized conditions.

In practice, **heterogeneity, drift, and conflicting client updates introduce instability** that standard methods do not address.

My work focuses on a central question:

> **When and why does federated learning fail under real-world conditions?**

The goal is to characterize these failure modes and design methods that remain stable in realistic distributed environments.

---

## Research Program

This work is organized around three directions:

**Robust Federated Learning (Non-IID)**  
Aggregation under distribution shift and client heterogeneity.

**Personalization under Heterogeneity**  
Client-specific adaptation and its effect on global performance.

**Geometry and Instability in Federated LoRA**  
Training dynamics through update alignment, conflict, and early predictors of failure.

---

## Selected Work

- **[robust-federated-learning-noniid](https://github.com/vicobarafor/robust-federated-learning-noniid)**  
  Robust aggregation under heterogeneous client distributions  

- **[federated-personalization-depth](https://github.com/vicobarafor/federated-personalization-depth)**  
  Client-specific adaptation in federated systems  

- **[federated-lora-geometry](https://github.com/vicobarafor/federated-lora-geometry)**  
  Geometry and instability in federated LoRA  

---

## Perspective

Many approaches optimize for average-case performance.

In realistic settings, systems fail due to:
- conflicting updates  
- distributional imbalance  
- unstable optimization dynamics  

Understanding these behaviors requires focusing on **failure modes, not just performance**.

---

## Ongoing Work

- Stability-aware aggregation  
- Early indicators of training collapse  
- Scaling under increasing heterogeneity  
- Geometry-informed optimization  

---

## Links

- Website: https://victor-website-one.vercel.app/  
