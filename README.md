# Rice Image Classification with VGG19

A notebook-based computer-vision experiment using transfer learning with VGG19 to classify rice images.

## Project file

- `Rice image classification CNN.ipynb`: data preparation, augmentation, model construction, training, and evaluation

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

The image dataset is not committed. Update the notebook's data path to a locally obtained dataset and document its source and license before training.

## Skills demonstrated

- Image directory pipelines and augmentation
- Transfer learning with a pretrained convolutional backbone
- Multiclass training and validation
- Learning-curve and confusion-matrix interpretation

## Limitations

No trained weights or independently verified metrics are published here. A credible evaluation needs a fixed label map, deduplication, grower/location-aware splits where available, a truly held-out test set, per-class metrics, error analysis, and checks for background or acquisition shortcuts.

## License

Code is available under the [MIT License](LICENSE). Dataset and pretrained-model licenses apply separately.
