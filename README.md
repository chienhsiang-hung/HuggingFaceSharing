# Prerequisites
`pip install transformers`

# Issues
AttributeError: module 'jax.random' has no attribute 'KeyArray'

# Colab
[02_how_to_generate.ipynb](https://colab.research.google.com/github/huggingface/blog/blob/main/notebooks/02_how_to_generate.ipynb#scrollTo=XbzZ_IVTtoQe)

# Qdrant
```docker
docker pull qdrant/qdrant
docker run -p 6333:6333 qdrant/qdrant
```
## Make your own Env
```powershell
python -m venv venv
.\venv\Scripts\activate
pip install qdrant-client pandas numpy faker
pip install transformers datasets torch sentence-transformers
```
and run `pip freeze > requirements.txt` to export the config.

## How to Work with a requirements.txt File
`pip install -r requirements.txt`

## Get-ExecutionPolicy
```powershell
Get-ExecutionPolicy
powershell -ep bypass
```

# Ref
[isdaviddong/test_Qdrant](https://github.com/isdaviddong/test_Qdrant)