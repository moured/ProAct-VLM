<div align="center">

# ProAct-VLM

**Pre-Failure Vision-Language Task Replanning with Continuous Perception Feedback**

Ahmed Nader Ahmed<sup>1</sup> · Omar Moured<sup>2</sup> · Mughni Irfan Mohammed Abdul<sup>1</sup> · Muhayy Ud Din<sup>1</sup> · Irfan Hussain<sup>1</sup>

<sup>1</sup>Khalifa University, Abu Dhabi, UAE · <sup>2</sup>Sereact GmbH, Stuttgart, Germany

*IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2026*

[![Paper](https://img.shields.io/badge/Paper-PDF-blue)](https://arxiv.org/pdf/2609.37681)
[![arXiv](https://img.shields.io/badge/arXiv-2609.37681-b31b1b)](https://arxiv.org/abs/2609.37681)
[![Project Page](https://img.shields.io/badge/Project-Page-lightgrey)](#)
[![Video](https://img.shields.io/badge/Video-Coming%20Soon-lightgrey)](#)

</div>

![ProAct-VLM framework](assets/framework.webp)

## About

VLM task planners replan *after* failure. **ProAct-VLM replans before it.**

- **Continuous perception feedback** — scene monitored in real time during execution.
- **Pre-failure replanning** — plan updated as soon as a task-relevant change is detected.
- **Physically grounded VLM planning** — unified visual–text reasoning over the live scene.
- **Backbone-agnostic** — higher SR and efficiency across multiple VLMs on dynamic, long-horizon manipulation.

## Disturbance Scenarios

Seven sorting scenarios covering **(a)** object added, **(b)** object removed, **(c)** goal changed.

![Disturbance scenarios](assets/scenarios.webp)

## Citation

```bibtex
@InProceedings{ahmed2026proactvlm,
  author    = {Ahmed, Ahmed Nader and Moured, Omar and Mohammed Abdul, Mughni Irfan and Ud Din, Muhayy and Hussain, Irfan},
  title     = {ProAct-VLM: Pre-Failure Vision-Language Task Replanning with Continuous Perception Feedback},
  booktitle = {IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year      = {2026}
}
```
