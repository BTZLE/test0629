## ControlNet 是什么？它的作用是什么？[](https://comfyui-wiki.com/zh/resource/controlnet-models#controlnet-%E6%98%AF%E4%BB%80%E4%B9%88%E5%AE%83%E7%9A%84%E4%BD%9C%E7%94%A8%E6%98%AF%E4%BB%80%E4%B9%88)

ControlNet 是 Stable Diffusion 模型的一个扩展，增强了对图像生成过程的控制。它允许根据用户规格提供更精确和定制化的图像输出。

## ControlNet 的功能和特点[](https://comfyui-wiki.com/zh/resource/controlnet-models#controlnet-%E7%9A%84%E5%8A%9F%E8%83%BD%E5%92%8C%E7%89%B9%E7%82%B9)

1. **增强控制**
    
    - ControlNet 提供额外的输入，如草图、遮罩或特定条件，以指导图像生成过程。这就像给艺术家一个粗略的草图，并要求他们基于此创作一幅画，同时允许他们有创造性的自由。
2. **提高准确性**
    
    - 没有 ControlNet，生成的图像可能会偏离用户的期望。通过提供额外的控制信号，ControlNet 帮助模型更准确地理解用户的意图，从而生成更符合描述的图像。
3. **多样化的应用**
    
    - ControlNet 可以应用于多种场景，例如协助艺术家提炼他们的创意想法，或帮助设计师快速迭代和优化设计草稿。

## 易于理解的类比[](https://comfyui-wiki.com/zh/resource/controlnet-models#%E6%98%93%E4%BA%8E%E7%90%86%E8%A7%A3%E7%9A%84%E7%B1%BB%E6%AF%94)

想象 Stable Diffusion 是一位有才华但有些不可预测的画家。它可以根据你的描述（例如，“阳光明媚的海滩场景”）创作一幅画。然而，有时画家可能会包括一些意想不到的细节，比如海滩上的一只巨大的蓝色大象。

ControlNet 就像一个细致的艺术指导，给画家提供了一个更详细的蓝图，指定了要包括什么和避免什么。例如，指导者可能会说：“海滩上不要有大象，但要包括一把伞和一些沙滩椅。”这样，画家就可以创作出一个更符合你期望的海滩场景。

有了 ControlNet，Stable Diffusion 不仅捕捉到了用户描述的精髓，而且在用户的指导下生成了更精确和预期的结果。