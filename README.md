# evalsone
A Tiny Python client for EvalsOne API

## Installation
```bash
pip install evalsone
```

## Example usage:
```python
from evalsone import EvalsOne
# api_key and sample_list_id should be replaced with your own
eo_client = EvalsOne(api_key='your_api_key', sid='your_dataset_id')
sample_data = {'messages': [{"role": "user", "content": "What's the capital of France?"}], 'ideal': ['Paris']}
response = eo_client.add_sample(sample_data)
```
