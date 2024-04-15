# DeProt
Code for DeProt. A protein language model with quantizied structure and disentangled attention

## Structure quantizer

![Structure quantizer](images/structure_quantizer.png)

```python
from deprot.structure.quantizer import PdbQuantizer
processor = PdbQuantizer()
result = processor("example_data/p1.pdb", return_residue_seq=True)
print(result)
```