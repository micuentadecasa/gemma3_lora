https://medium.com/tutorial-by-winston-wang/beginners-guide-to-fine-tuning-models-using-mlx-on-apple-silicon-1a21ebb70aed


# hugginface login
pip install -U "huggingface_hub[cli]"

huggingface-cli login   

# mlx 1b
working - about 2 minutes for 10 iterations

# win 4b


# hugginface 
https://huggingface.co/docs/trl/grpo_trainer

https://github.com/huggingface/smol-course

Parameter-Efficient Fine-Tuning (PEFT)
Methods like LoRA (Low-Rank Adaptation) allow you to efficiently adapt pre-trained models to new datasets by:

Freezing the original model weights

Adding small trainable adapter modules to specific layers

Training only these new parameters on your dataset

This approach is more memory-efficient than full fine-tuning while still effectively transferring knowledge.

Retrieval-Augmented G
