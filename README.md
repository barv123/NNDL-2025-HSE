# HW5: Cat/Dog Image Reconstruction — U-Net Autoencoder + Grad-CAM

**Course:** Neural Networks and Deep Learning — Advanced CNN

## Task

1. Build a U-Net CNN autoencoder (encoder-decoder with skip connections) to reconstruct cat/dog images.
2. Train with MSE loss and compute PSNR on the validation set.
3. Visualize Grad-CAM on one intermediate encoder feature map.
4. Save and display: input, reconstruction, heatmap, and overlay.

## Dataset

[Cats and Dogs Mini Dataset (Kaggle)](https://www.kaggle.com/datasets/aleemaparakatta/cats-and-dogs-mini-dataset)

The notebook uses `kagglehub` to download the dataset automatically in Google Colab or in a properly configured local environment.

## How to Run

### Google Colab (recommended)

1. Upload `HW5_CatDog_Reconstruction_GradCAM.ipynb` to Google Colab.
2. Optionally select **Runtime → Change runtime type → T4 GPU**.
3. Run all cells from top to bottom.

### Local

```bash
pip install -r requirements.txt
jupyter notebook
```

Then open `HW5_CatDog_Reconstruction_GradCAM.ipynb`.