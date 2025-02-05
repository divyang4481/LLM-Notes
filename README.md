# LLM-Notes


# Mobile-Optimized Large Language Models

As the demand for on-device natural language processing grows, several models have been developed or adapted to operate efficiently on mobile and embedded hardware. Below is a curated list of such models, highlighting their key features and suitability for mobile deployment.

## Sub-3B Models for On-Device Deployment

| Name | Year | Sizes | Primary Group/Affiliation | Publication | Code Repository | HF Repository (Hugging Face) |
|------|------|-------|---------------------------|-------------|-----------------|-----------------------------|
| [BlueLM-V](https://huggingface.co/vivo-ai-lab/BlueLM-V) | 2024 | 2.7B | CUHK, Vivo AI Lab | [paper](https://arxiv.org/abs/2411.10640) | [code](https://github.com/vivo-ai-lab/BlueLM) | - |
| [PhoneLM](https://huggingface.co/mllmTeam/PhoneLM-0.5B) | 2024 | 0.5B, 1.5B | BUPT | [paper](https://arxiv.org/abs/2411.05046) | [code](https://github.com/UbiquitousLearning/PhoneLM) | [Hugging Face](https://huggingface.co/mllmTeam/PhoneLM-0.5B) |
| [AMD-Llama-135m](https://huggingface.co/amd/AMD-Llama-135m) | 2024 | 135M | AMD | [blog](https://community.amd.com/t5/ai/amd-unveils-its-first-small-language-model-amd-135m/ba-p/711368) | [code](https://github.com/AMD-AIG-AIMA/AMD-LLM) | [Hugging Face](https://huggingface.co/amd/AMD-Llama-135m) |
| [SmolLM2](https://huggingface.co/collections/HuggingFaceTB/smollm2-6723884218bcda64b34d7db9) | 2024 | 135M, 360M, 1.7B | Huggingface | - | - | [Hugging Face](https://huggingface.co/collections/HuggingFaceTB/smollm2-6723884218bcda64b34d7db9) |
| [Ministral](https://huggingface.co/mistralai/Ministral-8B-Instruct-2410) | 2024 | 3B, ... | Mistral | [blog](https://mistral.ai/news/ministraux/) | - | [Hugging Face](https://huggingface.co/mistralai/Ministral-8B-Instruct-2410) |
| [Llama 3.2](https://huggingface.co/meta-llama/Llama-3.2-1B) | 2024 | 1B, 3B | Meta | [blog](https://ai.meta.com/blog/llama-3-2-connect-2024-vision-edge-mobile-devices/) | [code](https://github.com/meta-llama/llama-models) | [Hugging Face](https://huggingface.co/meta-llama/Llama-3.2-1B) |

---

## Considerations for Deployment

- **Hardware Requirements**: Performance can vary based on the device's hardware capabilities. High-end smartphones are more likely to run these models efficiently.
- **Optimization Techniques**: Techniques such as quantization and pruning are often employed to reduce model size and improve inference speed on mobile hardware.
- **Use Cases**: Tasks like text summarization, sentiment analysis, and personalized content delivery can benefit from on-device LLMs, enhancing privacy and reducing latency.

By selecting and optimizing the appropriate model, it's possible to integrate advanced language understanding capabilities directly into mobile applications, providing users with enhanced experiences without the need for constant internet connectivity.

