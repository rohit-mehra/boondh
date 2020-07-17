# boondh
A Personal Library
- Encapsulate boilerplate code
- Data processing code
- ML Frameworks (NLP tasks - SeqClassification, Entity Extractions etc.)

# install
```bash
git clone https://github.com/rohit-mehra/boondh.git
cd boondh
pip install .
```

# sample use
```python
from boondh import mp_func

def base_func(value, sq=True):
    if sq: return value ** 2
    return value

data = [0, 1, 2, 3, 4]
results = mp_func(base_func, 'value', data, sq=True)
```