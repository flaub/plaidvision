# plaidvision
Vision network demos

To install (this will install [PlaidML](https://github.com/vertexai/plaidml)):

```
pip install -r requirements.txt
```

Run the webcam classifier demo like this:

`python plaidvision.py [--plaid|--no-plaid] MODEL`

The following Keras application models are supported:
- `inception_v3`
- `mobilenet`
- `resnet50`
- `vgg16`
- `vgg19`
- `xception`

By default, PlaidML is used as the backend. Specifying `--no-plaid` will utilize tensorflow,
if installed.

