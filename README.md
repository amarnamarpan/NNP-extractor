# NNP-extractor - a highly customisable noun phrase extraction module
This is a noun phrase extractor that when given a text snippet, extracts the noun phrases out of it.
Import the module and call the start function with the text given as the argument. [Please ensure that the nltk package is installed]

Example code for using the library is shown in test_code.py

```python
import NNP_extractor as npe
text = '''
A gnarble left his cozy bed along the ocean floor. He dreamt about a place that he had never seen before! He headed to the surface for a glimpse of sun and sky. A trip so long and perilous, he'd be the first to try!
'''
NNP_list = npe.start(text)
print('::'.join(NNP_list))
```
If using this method, please cite the following. The extractor was used in the following paper.
## Reference
[Automatic Catchphrase Identification from Legal Court Case Documents, by A Mandal, K Ghosh, A Pal, S Ghosh at CIKM, 2017](https://dl.acm.org/doi/10.1145/3132847.3133102)
