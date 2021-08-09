### Tranlation App Using Google API

Packages used:

```
Django==3.2.6
googletrans==3.1.0a0
```

Usage:
```python
>>> from googletrans import Translator
>>> translator = Translator()
>>> tr = translator.translate('Bonjour je suis Elias.')
>>> tr.text
"Hello i'm Elias."
```