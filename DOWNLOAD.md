Dataset **Utility Pole Label** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/u/p/Ni/hgIyVYPciW9OHmIC3Uct3bB4h0kqEGjom1APtktSUCiaMGcZrCgfj0Sa1Zz3yMmEsejkpzTiUYyhru4N2IlCy1NsUVFBynWWBk3gh91CaBlJS43bRiy30ZoNidwi.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Utility Pole Label', dst_path='~/dtools/datasets/Utility Pole Label.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/new-workspace-en1on/utility-pole-label/dataset/4/download)