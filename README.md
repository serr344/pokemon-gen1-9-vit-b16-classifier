# Pokémon Gen 1–9 Classifier (ViT-B/16)

An ImageNet-pretrained Vision Transformer (ViT-B/16) fine-tuned to classify **1,027 Pokémon classes** across Generations 1–9 using PyTorch and Torchvision.

## Model & Dataset

- **Architecture:** ViT-B/16
- **Dataset:** [JJMack/pokemon-classification-gen1-9](https://huggingface.co/datasets/JJMack/pokemon-classification-gen1-9)
- **Training:** Feature extraction followed by fine-tuning the last 2 transformer blocks
- **Input:** 224×224 RGB images
- **Fine-tuned model:** [Hugging Face](https://huggingface.co/servetkara/pokemon-gen1-9-vit-b16-classifier)

## Performance

| Metric | Accuracy |
|---|---|
| Best Validation | **87.67%** |
| Test | **86.32%** |


## Limitations

Optimized primarily for Pokémon artwork and sprites. Performance may decrease on realistic or AI-generated images with complex backgrounds.

This is an unofficial project. Pokémon and related characters belong to their respective rights holders.
