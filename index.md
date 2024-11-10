---
layout: project_page
permalink: /

title: "Free$^2$Guide: Enhancing Video Generation Through Training-free & Gradient-free Reward-based Guidance"
authors:
    Anonymous
code: https://free2guide.github.io/
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Diffusion models have achieved impressive results in generative tasks like text-to-image (T2I) and text-to-video (T2V) synthesis. However, achieving accurate text alignment in T2V generation remains challenging due to the complex nature of maintaining temporal consistency across frames. In this paper, we propose <strong>Free$^2$Guide</strong>, a novel gradient-free framework for aligning generated videos with text prompts without requiring additional model training. Free$^2$Guide leverages path integral control to approximate guidance, adapting pre-trained image reward models—trained on large-scale image-text data—to steer video generation in alignment with text prompts. This design eliminates the need for differentiable reward functions, allowing the use of black-box vision-large language models (LVLMs) such as GPT-4o, as well as ensembling reward models for enhanced alignment. Our method significantly improves T2V generation performance in text-video alignment and video quality.
        </div>
    </div>
</div>

---

> **TL; DR** : Free$^2$Guide, a gradient-free framework that aligns generated videos with text prompts without extra model training.

## Qualitative Results

![Turing Machine](/static/image/c-A cute happy Corgi playing in park, sunset, Van Gogh style-0.gif)


<!-- citation -->
