# Paper Reading Notes

## LLM

### Implicit CoT

| Date | Title | Link | Mark |
| ---- | ----- | ---- | ---- |
| 202505 | Stop Overthinking: A Survey on Efficient Reasoning for Large Language Models | [Blog](https://zhuanlan.zhihu.com/p/1888902868641244612) | Survey 1 |
| 202505 | A Survey of Efficient Reasoning for Large Reasoning Models: Language, Multimodality, and Beyond | [Blog](https://blog.csdn.net/yul1024/article/details/147125726) | Survey 2 |
| 202505 | Efficient Reasoning Models: A Survey | [Blog](https://zhuanlan.zhihu.com/p/1895887731894228718) | Survey 3 |
| 202505 | Efficient Inference for Large Reasoning Models: A Survey | - | Survey 4 |
| 202505 | Training Large Language Models to Reason in a Continuous Latent Space | [Github](https://github.com/facebookresearch/coconut) | Coconut (Curriculum learning) |
| 202505 | CODI: Compressing Chain-of-Thought into Continuous Space via Self-Distillation | - | CODI (Curriculum learning) |
| 202505 | Efficient Reasoning with Hidden Thinking | [Github](https://github.com/shawnricecake/Heima) | Heima (Curriculum learning) (MLLM) |
| 202505 | SoftCoT: Soft Chain-of-Thought for Efficient Reasoning with LLMs | [Github](https://github.com/xuyige/SoftCoT) | SoftCoT (Special token) |
| 202505 | Compressed Chain of Thought: Efficient Reasoning through Dense Representations | - | CCoT (Compressed CoT) |
| 202505 | Token Assorted: Mixing Latent and Text Tokens for Improved Language Model Reasoning | [Github](https://github.com/lblankl/Token-Assorted) | Token Assorted (Compressed CoT) |
| 20250606 | Reasoning Beyond Language: A Comprehensive Survey on Latent Chain-of-Thought Reasoning | [Blog](https://mp.weixin.qq.com/s/jZ3bmuHpg4_XTmsW-S0jBA) | Survey 5 |
| 20250611 | Beyond Words: A Latent Memory Approach to Internal Reasoning in LLMs | - | - |
| 20250611 | Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach | - | - |
| 20250611 | LightThinker: Thinking Step-by-Step Compression | - | - |






### Efficient Reasoning

| Date | Title | Link | Mark |
| ---- | ----- | ---- | ---- |
| 202505 | AdaptThink: Reasoning Models Can Learn When to Think | [Blog](https://zhuanlan.zhihu.com/p/1909543282897313853) [Github](https://github.com/THU-KEG/AdaptThink) | AdaptThink (Think/Nothink) |
| 202505 | Prolonged Reasoning Is Not All You Need: Certainty-Based Adaptive Routing for Efficient LLM/MLLM Reasoning | - | CAR (Think/Nothink) |
| 202505 | Reasoning Models Can Be Effective Without Thinking | - | - |
| 202505 | The Danger of Overthinking: Examining the Reasoning-Action Dilemma in Agentic Tasks | [Blog](https://www.linkresearcher.com/theses/21271ce1-d44f-4fc3-a0a0-1899d51829e5) | - |
| 202505 | Think or Not? Exploring Thinking Efficiency in Large Reasoning Models via an Information-Theoretic Lens | [Github](https://github.com/chicosirius/think-or-not) | (Adaptive thinking) |
| 202505 | Token-Budget-Aware LLM Reasoning | [Github](https://github.com/GeniusHTX/TALE) | (Adaptive thinking) |
| 202505 | Think or Not? Exploring Thinking Efficiency in Large Reasoning Models via an Information-Theoretic Lens | - | (Adaptive thinking) |
| 20250606 | Adaptive Inference-Time Compute: LLMs Can Predict if They Can Do Better, Even Mid-Generation | [Blog](https://www.themoonlight.io/zh/review/adaptive-inference-time-compute-llms-can-predict-if-they-can-do-better-even-mid-generation) [Blog](https://blog.csdn.net/weixin_46739757/article/details/142925403) | Adaptive sampling |
| 20250606 | ALPHAONE: Reasoning Models Thinking Slow and Fast at Test Time | [Blog](https://mp.weixin.qq.com/s/EIJHZ9yPlDrR3DVlT2pgYg) | Adaptive thinking (引导LRMs先进行充分的慢速思考，然后再快速生成答案，能取得更好的性能) |
| 20250606 | Inner Thinking Transformer: Leveraging Dynamic Depth Scaling to Foster Adaptive Internal Thinking | [Blog](https://blog.csdn.net/weixin_46739757/article/details/145908557) | Inner Adaptive thinking, Model extension |
| 20250607 | DAST: Difficulty-Adaptive Slow Thinking for Large Reasoning Models | - | Autonomously adjust the length of Chain-of-Thought (CoT) based on problem difficulty |
| 20250608 | Thinkless: LLM Learns When to Think | [Blog](https://mp.weixin.qq.com/s/sWPzf-rpWPTH3QVY2COBVg) | Think/Nothink |
| 20250610 | ARM: Adaptive Reasoning Model | [Blog](https://mp.weixin.qq.com/s/zz-a0rxDrCrC4eQ5J9HGvQ) | Adaptive thinking |
| 20250610 | AdaCoT: Pareto-Optimal Adaptive Chain-of-Thought Triggering via Reinforcement Learning | [Blog](https://mp.weixin.qq.com/s/aJyWOjyvX3dYIu-K83lGBw) | Similar to AdaptThink |
| 20250611 | Harnessing the Reasoning Economy A Survey of Efficient Reasoning for Large Language Models | - | Survey |


### Looped Transformer [Blog](https://www.zhihu.com/question/1904728228213548260/answer/1904737712256296340)
| Date | Title | Link | Mark |
| ---- | ----- | ---- | ---- |
| 20250612 | Looped Transformers for Length Generalization | - | - |
| 20250612 | Reasoning with Latent Thoughts: On the Power of Looped Transformers | [Blog](https://zhuanlan.zhihu.com/p/1906684588606064483) | - |
| 20250612 | To CoT or To Loop? A Formal Comparison Between Chain-of-Thought and Looped Transformers | - | - |
| 20250612 | Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach | - | - |
| 20250612 | Inner Thinking Transformer: Leveraging Dynamic Depth Scaling to Foster Adaptive Internal Thinking | - | - |




### Test Time Scaling

| Date | Title | Link | Mark |
| ---- | ----- | ---- | ---- |
| 20250607 | Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters | [Blog](https://zhuanlan.zhihu.com/p/18709529446) | - |
| 20250607 | Test-Time Preference Optimization: On-the-Fly Alignment via Iterative Textual Feedback | [Blog](https://mp.weixin.qq.com/s/hi1jXnNS3mASJUd8FxLCdA) [Blog](https://zhuanlan.zhihu.com/p/24597691981) | TPO (Test-Time Preference Optimization) |




### Hallucination

| Date | Title | Link | Mark |
| ---- | ----- | ---- | ---- |
| 20250608 | Auditing Meta-Cognitive Hallucinations in Reasoning Large Language Models | - | - |
| 20250610 | On the Fundamental Impossibility of Hallucination Control in Large Language Models | - | - |
| 20250612 | Do I Know This Entity? Knowledge Awareness and Hallucinations in Language Models | - | 还没看 |



### Interpretiblity of LLM

| Date | Title | Link | Mark |
| ---- | ----- | ---- | ---- |
| 20250615 | On the Role of Attention Heads in Large Language Model Safety | - | safety相关 |
| 20250615 | Spot Risks Before Speaking! Unraveling Safety Attention Heads in Large Vision-Language Models | [Blog](https://www.themoonlight.io/zh/review/spot-risks-before-speaking-unraveling-safety-attention-heads-in-large-vision-language-models) | safety相关 (VLM) |









### MLLM

| Date | Title | Link | Mark |
| ---- | ----- | ---- | ---- |
| -    | -     | -    | -    |






## AI4Phys

| Date | Title | Link | Mark |
| ---- | ----- | ---- | ---- |
| -    | -     | -    | -    |



## Foundation Models

| Date | Title | Link | Mark |
| ---- | ----- | ---- | ---- |
| -    | -     | -    | -    |



