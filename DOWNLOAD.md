Dataset **Makerere University Cassava** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzMzNzZfTWFrZXJlcmUgVW5pdmVyc2l0eSBDYXNzYXZhL21ha2VyZXJlLXVuaXZlcnNpdHktY2Fzc2F2YS1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICJkYzdqSC9qOEVZcktOb01RWmpZZGp1L0c3THk0akJDSTJ5bVErYkF4QnVvPSJ9)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Makerere University Cassava', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/T4RB0B#).