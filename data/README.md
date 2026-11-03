# Données — Flickr30k

Le dataset **n'est pas versionné** (trop volumineux). Source indiquée dans le rapport :
<https://www.kaggle.com/datasets/adityajn105/flickr30k>

```
data/
├── Images/         # ~31 783 images .jpg
└── captions.txt    # 5 légendes par image (format CSV : image,caption)
```

Télécharger via l'interface Kaggle, ou :

```bash
pip install kaggle
kaggle datasets download -d adityajn105/flickr30k -p data --unzip
```

Les notebooks contiennent des chemins locaux (`C:/Users/.../data1/Images`) à adapter vers `data/Images` et `data/captions.txt`.
