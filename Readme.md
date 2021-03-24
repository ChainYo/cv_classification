## Installation

Git clone this repository

```bash
git clone https://github.com/ChainYo/cv_classification
```

You must install all the packages in `requirements.txt`:

```bash
cd cv_classification
pip install -r requirements.txt
```

## Classification 

The model and all the process to get it is in the notebook.   
Open `code.ipynb` with jupyter notebook extension or with vscode:

```bash
# jupyter
jupyter notebook

# vscode
code .
```

If you want to reuse my model, you can import `model.bin` directly in your notebook or your python file.

```python
# Add this to your python file to use my model
from gensim.models import Word2Vec

model = Word2Vec.load("model.bin")
```

---

Feel free to star this repository if you find it usefull.  
You can also fork it to modify it by your own.  
Cheers!