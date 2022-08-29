# BEP035_example
BEP035 example data: Resting state fMRI studies of pain from OpenNeuro (n=212)

Install dataset with DataLad:

```
export WEBDAV_USERNAME=XXXX
export WEBDAV_PASSWORD=XXXX-XXXX-XXXX-XXXX
datalad install -s git@github.com:pni-data/BEP035_example.git
datalad siblings -d BEP035_example enable -s sciebo.sfb289
datalad get <file>
```
