---
layout: post
title:  "InstantIR: Blind Image Restoration with Instant Generative Reference"
date:   2024-10-02 19:53:59 +08:00
image: /images/instantir.png
categories: research
author: "Jen-Yuan Huang"
authors: "<strong>Jen-Yuan Huang</strong>, Haofan Wang, Qixun Wang, Xu Bai, Hao Ai, Peng Xing, Tong Lin"
venue: "submit to ICLR"
# arxiv: https://arxiv.org/abs/2308.14737
# code: https://github.com/leonidk/fmb-plus
# website: https://leonidk.github.io/fmb-plus
---
InstantIR is a novel blind image restoration model based on Stable Diffusion. At each denoising step, we generate a restoration reference from current diffusion latent, which is used to align the low-quality image encoding and condition the generation process.