# Dataset — Flickr30k

The **dataset is not included in the repository** due to its large size. Source referenced in the project report:

[https://www.kaggle.com/datasets/adityajn105/flickr30k](https://www.kaggle.com/datasets/adityajn105/flickr30k)

Expected directory structure:

```text
data/
├── Images/          # ~31,783 JPG images
└── captions.txt     # 5 captions per image (CSV format: image,caption)
```

### Download the dataset

Download it directly from Kaggle or use the Kaggle API:

```bash
pip install kaggle
kaggle datasets download -d adityajn105/flickr30k -p data --unzip
```
