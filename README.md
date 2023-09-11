# ML-archive
This is My Machine Learning Archive

## Install Requirements
```bash
pip install -r requirements.txt
```

or

```bash
pip install notebook tensorflow numpy pandas scikit-learn tabulate matplotlib bokeh plotly ipywidgets gym imageio pyvirtualdisplay
```

## Fix Issues
### Pickle5 error
You only need pickle on Python versions older than 3.8. And `pickle` is a native library from that version.
So the solution is replacing this:
```python
from pickle5 import pickle
```
with this:
```python
import pickle
```
### Pyvirtualdisplay error
Unfortunately this library won't work on windows. run it on `Linux`/`Colab`.
