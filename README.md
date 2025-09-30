## Denoising Images by Deep Learning Models

Introduction: The goal of this project is to denoise the corrupted MNIST images by diffusion model combined with simple U-Net architecture, and integrated with a transformer for feature refinement.

Dataset: MNIST database of handwritten digits from Kaggle

Objective:
- Implement forward diffusion model by progressively adding Gaussian noise
- Reverse denoising process with a simple U-Net architecture and transformer in the bottleneckfor noise prediction
- Train the combined model (diffusion process + transformer) on the noisy MNIST dataset
- Evaluate with MSE and SSIM
- Compare the performance and visualise the attention maps

Skills:
- Python: PyTorch, torchvision, matplotlib, seaborn, tqdm, skimage
- Deep Learning Models: Diffusion, U-Net, transformer
- Evaluation: Mean Squared Error (MSE), Structural Similarity Index Measure (SSIM)
