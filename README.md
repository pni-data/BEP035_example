# BEP035_example
BEP035 example data: Resting state fMRI studies of pain from OpenNeuro (n=212)

Install dataset with DataLad:

```
export WEBDAV_USERNAME=XXXX
export WEBDAV_PASSWORD=XXXX-XXXX-XXXX-XXXX
datalad install -s git@github.com:pni-data/hcp-connectivity.git hcp_data
datalad siblings -d hcp_data enable -s sciebo.sfb289
datalad get hcp_data
```
