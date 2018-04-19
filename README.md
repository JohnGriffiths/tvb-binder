# tvb-binder
Run tvb notebooks live in the cloud using Binder

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/JohnGriffiths/tvb-binder/master)



Currently you need to add the following to the top of any tutorial or demo notebooks

```python
import sys
sys.path.append('/home/jovyan/tvb-library')
sys.path.append('/home/jovyan/tvb-data')
```

Trying to figure out how to tell binder + the docker/python instances to do this automatically. Haven't cracked that yet. 

