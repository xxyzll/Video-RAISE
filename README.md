# Video-RAISE

## Abstract 
Chain-of-Thought (CoT) is a key technique for enhancing the reasoning capabilities of Vision Language Models (VLMs). Existing methods often employ Reinforcement Learning (RL) with external constraints to align the model's reasoning process with human cognitive patterns. However, we argue that the model's intrinsic reasoning paths may differ from human cognition, and that forcing such alignment can constrain the model's potential and even degrade its performance. To address this, we propose leveraging the model's intrinsic self-evaluation to guide its optimization. We hypothesize that a model's self-generated confidence scores are effective indicators of its reasoning quality. Based on this evaluation metric, we design two novel reward functions: (1) Sequential Confidence Rigorous Evaluation (SCRE) for challenging problems that demand strict logical reasoning, and (2) Intra-group Score Re-ranking (IGSR) for general-purpose, open-ended scenarios. We name our method Video-RAISE (Reasoning Alignment through Intrinsic Self-Evaluation). Comprehensive experiments on six video understanding benchmarks demonstrate that Video-RAISE achieves state-of-the-art (SOTA) performance, significantly outperforming previous methods. For instance, on the VideoMMMU benchmark, our Video-Sraise achieves a new SOTA accuracy of 52.8\%, outperforming the previous best model by a significant 3.0\%. In addition, our method achieves a reasoning path consistency of 90\%, which is double that of the Qwen2.5-VL-Instruct and even surpasses the performance of supervised fine-tuning. 

## Performance
### SOTA 
<img width="666" height="449" alt="image" src="https://github.com/user-attachments/assets/535cc1c6-b9bd-4a47-9114-5b451c7e7b30" />

### Path Consistency
<img width="675" height="146" alt="image" src="https://github.com/user-attachments/assets/03ea9eab-d4f6-4fc8-9d19-b93b7778c959" />


