# Component Transfer Can Exceed Full Model Performance: Investigating Post-Trained Mixture-of-Experts

This repository contains the paper for our ACL GEM Workshop 2026 paper:

> **Component Transfer Can Exceed Full Model Performance: Investigating Post-Trained Mixture-of-Experts**
> Rabin Tiwari

## Overview

Post-training methods such as SFT, DPO, and RLVR substantially improve large language models, but it remains unclear how these improvements are distributed across architectural components.

In this work, we perform systematic component transfer between two post-trained OLMoE checkpoints and analyze the contribution of:

* **Routers**
* **Attention modules**
* **Expert networks**

across mathematical reasoning, reading comprehension, and science reasoning tasks under different prompting strategies.

## Key Findings

* Expert networks drive most gains on complex reasoning tasks.
* Attention modules provide more consistent improvements across tasks.
* Router transfer often introduces instability due to router–expert co-adaptation.
* Selective component composition can match or exceed the performance of either source model.

## License

This project is released under the MIT License.
