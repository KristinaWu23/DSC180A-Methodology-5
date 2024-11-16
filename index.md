# Kristina Wu
**Email:** mew013@ucsd.edu

**Section:** B04
**Mentor:** Professor Hao Zhang

## Prompts

**What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic covered this quarter was aligning scaling laws with computational budgets for training large language models(eg.LLaMA). It was fascinating to see how theoretical concepts like scaling laws directly influence practical decisions, such as determining model size, the number of tokens, and epochs. This topic demonstrated the importance of balancing resource constraints with model performance, which is crucial for efficient training.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For Quarter 2, I’d like to investigate how transformer-based models can be applied to quantitative finance, such as forecasting market trends or optimizing portfolio strategies. This project could involve fine-tuning a pretrained LLM on financial datasets, such as stock price movements, news sentiment, or economic indicators, to identify patterns and predict future outcomes. Given that many of my groupmates are interested in business or finance, this investigation aligns well with our collective interests while also exploring the innovative applications of cutting-edge machine learning models in the financial domain. 

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
A potential change would be implementing an on-the-fly data loading process combined with parallelism to utilize all GPUs effectively. This could address the issue of handling our very large dataset, which is currently limited by memory constraints and slower iteration speeds. By loading data dynamically during training and distributing it across GPUs, we can minimize preprocessing bottlenecks and improve overall training efficiency.

**What other techniques would you be interested in using in your project?**  
I’d like to explore techniques like Flash Attention and sequence packing to optimize the training process for large language models. Flash Attention could significantly improve training efficiency by reducing memory usage and speeding up computation, making it particularly valuable for models with long sequences. Sequence packing, on the other hand, would allow us to maximize GPU utilization by efficiently organizing input data to minimize padding, which is crucial for reducing computational waste. Both techniques could enhance the overall efficiency of the training pipeline while ensuring that we make the most of the available computational resources.
