Dataset **Makerere University Cassava** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMzM3Nl9NYWtlcmVyZSBVbml2ZXJzaXR5IENhc3NhdmEvbWFrZXJlcmUtdW5pdmVyc2l0eS1jYXNzYXZhLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIkZlZ25FOStldDVGM1dWR2UyeVQrMk95bFlHalJJQXBKWWlSUVpwdnRVSUE9In0=?response-content-disposition=attachment%3B%20filename%3D%22makerere-university-cassava-DatasetNinja.tar%22)

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