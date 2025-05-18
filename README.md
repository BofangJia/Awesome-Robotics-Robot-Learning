# Awesome-Robotics-Robot-Learning

## ✨ About 
This repo contains a curated list of papers relating to Robotics and Robot Learning domain. This section is divided into categories according to robot configuration, reinforcement learning and multimodal methods, hierarchical systems and downstream policies.

On the other hand, we also try to include some open source courses and talks as much as possible, hoping to build a comprehensive open source learning resource.

In many cases, due to limited level, some recommendations or comments may contain errors. Please point them out and we will correct them in time. Email---> jiabofang@outlook.com

If you find this repository useful, please consider [citing](#Citation) and STARing this list. Feel free to share this list with others!

<!-- ******* 0-Content Table ******* -->
## 🏠 Table of Contents

- [Awesome Papers](#awesome-papers)
  - [Awesome Robotic Arm](#awesome-Robotic-Arm—papers)
    - [Awesome DRL](#awesome-DRL)
    - [Awesome MLLM](#awesome-MLLM)
      - [Vision Language Action Models](#vision-language-action-models)
    - [Awesome Visuomotor Policies](#awesome-Visuomotor-Policies)
      - [Affordance Learning](#affordance-learning)
      - [Latent Action Learning](#latent-action-learning)
      - [Visuomotor Learning](#visuomotor-learning)
      - [Visuomotor Inference Acceleration](#visuomotor-inference-acceleration)
      - [Dexterous Manipulation](#dexterous-manipulation)
    - [Awesome Tactile Manipulation](#awesome-tactile-manipulation)
  - [Awesome Humanoid Robot & Mobile Arms](#awesome-Humanoid-Robot-&-Mobile-Arms—papers)
    - [Awesome DRL](#awesome-DRL)
    - [Awesome MLLM](#awesome-MLLM)
    - [Awesome Visuomotor Policies](#awesome-Visuomotor-Policies)
      - [Visuomotor Learning](#visuomotor-learning)
  - [Awesome Quadruped Robot](#awesome-Quadruped-Robot—papers)
    - [Awesome DRL](#awesome-DRL)
    - [Awesome MLLM](#awesome-MLLM)
    - [Awesome Visuomotor Policies](#awesome-Visuomotor-Policies)
- [Awesome Benchmarks](#awesome-datasets)
  - [Awesome Robotic Arm](#awesome-Robotic-Arm-datasets)
  - [Awesome Humanoid Robot & Mobile Arms](#awesome-Humanoid-Robot-&-Mobile-Arms-datasets)
  - [Awesome Quadruped Robot](#awesome-Quadruped-Robot-datasets)
- [Awesome Survey](#awesome-survey)
  - [Awesome Robotic Arm](#awesome-Robotic-Arm-survey)
  - [Awesome Humanoid Robot & Mobile Arms](#awesome-Humanoid-Robot-&-Mobile-Arms-survey)
  - [Awesome Quadruped Robot](#awesome-Quadruped-Robot-survey)
- [Awesome Control & Learning](#awesome-control-and-learning)
- [Awesome Talk](#awesome-talk)
- [Awesome Course](#awesome-course)





<!-- ******* 1-Papers ******* -->
## 📝 Awesome Papers

<!-- ******* 1.1-Robotic Arm ******* -->
### 📄 Robotic Arm


<!-- ******* 1.1.2-MLLM ******* -->
### 📄 MLLM

<!-- ******* 1.1.2.1-Vision Language Action Models ******* -->
#### Vision Language Action Models








<!-- ******* 1.1.3-Visuomotor Policies ******* -->
### 📄 Visuomotor Policies


<!-- ******* 1.1.3.1-Affordance Learning ******* -->
#### Affordance Learning





<!-- ******* 1.1.3.2-Latent Action Learning ******* -->
#### Latent Action Learning




<!-- ******* 1.1.3.3-Visuomotor Learning ******* -->
#### Visuomotor Learning

| Title | Link | Source | Short Abstract | Web Page | Code Page | Date |
|:------|:------:|:------:|:------|:------:|:------:|:-----:|
| Diffusion Policy: Visuomotor Policy Learning via Action Diffusion | [Link](https://arxiv.org/abs/2303.04137)| RSS 2023 | Policies based on diffusion models, which mainly include CNN-based and Transformer-based, have pioneering contributions. | [Web](https://diffusion-policy.cs.columbia.edu/) | [Code](https://github.com/real-stanford/diffusion_policy) | 7 Mar 2023 |
| 3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations | [Link](https://arxiv.org/abs/2403.03954)| RSS 2024 | Diffusion Policy in 3D scenes. The experiments mainly include dexterous hands and grippers, using point clouds as input. | [Web](https://3d-diffusion-policy.github.io/) | [Code](https://github.com/YanjieZe/3D-Diffusion-Policy) | 6 Mar 2024 |



<p align=right>(<a href=#Awesome-Robotics-Robot-Learning>back to top</a>)</p>

<!-- ******* 1.1.3.4-Visuomotor Inference Acceleration ******* -->
#### Visuomotor Inference Acceleration

| Title | Link | Source | Short Abstract | Web Page | Code Page | Date |
|:------|:------:|:------:|:------|:------:|:------:|:-----:|
| Consistency Policy: Accelerated Visuomotor Policies via Consistency Distillation | [Link](https://arxiv.org/abs/2405.07503)| RSS 2024 | Distillation based on CTM, one-step generation. The teacher model is the Diffusion Policy in 2D scene | [Web](https://consistency-policy.github.io/) | [Code](https://github.com/Aaditya-Prasad/Consistency-Policy/) | 13 May 2024 |
| ManiCM: Real-time 3D Diffusion Policy via Consistency Model for Robotic Manipulation | [Link](https://arxiv.org/abs/2406.01586)| Preprint | Distillation based on LCM, one-step generation. The teacher model is the Diffusion Policy in 3D scene (DP3) | [Web](https://manicm-fast.github.io/) | [Code](https://github.com/ManiCM-fast/ManiCM) | 3 Jun 2024 |
| Score and Distribution Matching Policy: Advanced Accelerated Visuomotor Policies via Matched Distillation | [Link](https://arxiv.org/abs/2412.09265)| Preprint | Distillation based on the dual teacher model, one-step generation. The teacher model is the Diffusion Policy in the 3D scene (DP3) | [Web](https://sdm-policy.github.io/) | [Code](https://github.com/BofangJia/SDM-Policy) | 12 Dec 2024 |


<p align=right>(<a href=#Awesome-Robotics-Robot-Learning>back to top</a>)</p>

<!-- ******* 1.2-Humanoid Robot******* -->
### 📄 Humanoid Robot

<!-- ******* 1.2.3-Visuomotor Policies ******* -->
### 📄 Visuomotor Policies

<!-- ******* 1.2.3.1-Visuomotor Learning ******* -->
#### Visuomotor Learning

| Title | Link | Source | Short Abstract | Web Page | Code Page | Date |
|:------|:------:|:------:|:------|:------:|:------:|:-----:|
| Generalizable Humanoid Manipulation with 3D Diffusion Policies | [Link](https://arxiv.org/abs/2410.10803)| Preprint | Improved version of 3D Diffusion Policy. Experiments are mainly conducted on humanoid robots.| [Web](https://humanoid-manipulation.github.io/) | [Code](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy) | 14 Oct 2024 |

<p align=right>(<a href=#Awesome-Robotics-Robot-Learning>back to top</a>)</p>






<!-- ******* 1.3-Quadruped Robot ******* -->
### 📄 Quadruped Robot


<!-- ******* 2-Benchmarks ******* -->
## 📝 Awesome Benchmarks

<!-- ******* 2.1-Robotic Arm ******* -->
### 📄 Robotic Arm


| Title | Link | Source | Short Abstract | Web Page | Code Page | Date |
|:------|:------:|:------:|:------|:------:|:------:|:-----:|
| RLBench: The Robot Learning Benchmark & Learning Environment | [Link](https://arxiv.org/abs/1909.12271)| RAL 2020 | RLBench.| [Web](https://sites.google.com/view/rlbench) | [Code](https://github.com/stepjam/RLBench) | 26 Sep 2019 |
| Meta-World: A Benchmark and Evaluation for Multi-Task and Meta Reinforcement Learning | [Link](https://arxiv.org/abs/1910.10897)| CoRL 2019 | Meta-World.| [Web](https://meta-world.github.io/) | [Code](https://github.com/Farama-Foundation/Metaworld) | 24 Oct 2019 |
| CALVIN: A Benchmark for Language-Conditioned Policy Learning for Long-Horizon Robot Manipulation Tasks | [Link](https://arxiv.org/abs/2112.03227)| RAL 2022 | CALVIN.| [Web](http://calvin.cs.uni-freiburg.de/) | [Code](https://github.com/mees/calvin) | 6 Dec 2021 |
| LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning | [Link](https://arxiv.org/abs/2306.03310)| NeurIPS 2023 | LIBERO.| [Web](https://libero-project.github.io/main.html) | [Code](https://github.com/Lifelong-Robot-Learning/LIBERO) | 5 Jun 2023 |
| Open X-Embodiment: Robotic Learning Datasets and RT-X Models | [Link](https://arxiv.org/abs/2310.08864)| ICRA 2024 | Open X-Embodiment.| [Web](https://robotics-transformer-x.github.io/) | [Code](https://github.com/google-deepmind/open_x_embodiment) | 13 Oct 2023 |

<p align=right>(<a href=#Awesome-Robotics-Robot-Learning>back to top</a>)</p>



<!-- ******* 2.2-Humanoid Robot ******* -->
### 📄 Humanoid Robot


<!-- ******* 2.3-Quadruped Robot ******* -->
### 📄 Quadruped Robot


<!-- ******* 3-Survey ******* -->
## 📝 Awesome Survey



<!-- ******* 3.1-Robotic Arm ******* -->
### 📄 Robotic Arm

| Title | Link | Source | Short Abstract | Date |
|:------|:------:|:------:|:------|:------:|
| Bridging Language and Action: A Survey of Language-Conditioned Robot Manipulation | [Link](https://arxiv.org/abs/2312.10807)| Preprint | Manipulation | 17 Dec 2023 |
| A Survey on Vision-Language-Action Models for Embodied AI | [Link](https://arxiv.org/abs/2405.14093)| Preprint | VLA Model | 23 May 2024 |
| Towards Generalist Robot Policies: What Matters in Building Vision-Language-Action Models | [Link](https://arxiv.org/abs/2412.14058)| Preprint | VLA Model | 18 Dec 2024 |
| Generative Artificial Intelligence in Robotic Manipulation: A Survey | [Link](https://arxiv.org/abs/2410.10803)| Preprint | Generative Model | 5 Mar 2025 |
| Diffusion Models for Robotic Manipulation: A Survey | [Link](https://arxiv.org/abs/2504.08438)| Preprint | Diffusion Policy | 11 Apr 2025 |
| Vision-Language-Action Models: Concepts, Progress, Applications and Challenges | [Link](https://www.arxiv.org/abs/2505.04769)| Preprint | VLA Model| 7 May 2025 |

<p align=right>(<a href=#Awesome-Robotics-Robot-Learning>back to top</a>)</p>


<!-- ******* 3.2-Humanoid Robot ******* -->
### 📄 Humanoid Robot


<!-- ******* 3.3-Quadruped Robot ******* -->
### 📄 Quadruped Robot


<!-- ******* 4-Control and Learning ******* -->
## 📝 Awesome Control and Learning







<!-- ******* 5-Talk ******* -->
## 📝 Awesome Talk

| Talk | Link | Lecturer | Date |
|:------|:------:|:------:|:-----:|




<p align=right>(<a href=#Awesome-Robotics-Robot-Learning>back to top</a>)</p>

<!-- ******* 6-Course ******* -->
## 📝 Awesome Course

| Course | Link | School |
|:------|:------:|:------:|
|CS 294-277, Robots That Learn|[Link](https://robots-that-learn.github.io/)|UC Berkeley|


<p align=right>(<a href=#Awesome-Robotics-Robot-Learning>back to top</a>)</p>

## ✨ Citation
If you find this repository useful, please consider citing this list:
```
@misc{jia2025roboticsandrobotlearning,
    title = {Awesome-Robotics-Robot-Learning},
    author = {Jia, Bofang},
    journal = {GitHub repository},
    url = {https://github.com/BofangJia/Awesome-Robotics-Robot-Learning},
    year = {2025},
}
```



