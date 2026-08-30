# Rice Image Classification with VGG19 Transfer Learning

A computer-vision notebook exploring transfer learning for rice-image classification with an ImageNet-pretrained VGG19 backbone.

## Modeling approach

- Resize images to a consistent input shape
- Load VGG19 without its original classification head
- Freeze pretrained convolutional layers
- Add flattening and dense classification layers
- Train with image augmentation
- Evaluate classification behavior on held-out images

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook "Rice image classification CNN.ipynb"
```

The image dataset is not stored in this repository. Update the notebook's training and validation paths to point to a locally obtained, properly licensed dataset.

## Evaluation status

The committed notebook contains a partial training run, so this README does not claim a final accuracy. A complete version should include dataset provenance, class counts, patient/source-independent splitting where applicable, per-class precision and recall, a confusion matrix, and saved inference examples.

## Skills demonstrated

Transfer learning, Keras functional models, image augmentation, and CNN-based classification.

## Author

**Purnendu Kale** · [LinkedIn](https://www.linkedin.com/in/purnendukale/)
