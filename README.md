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

## Using DeProt with huggingface transformers
```python
from transformers import AutoModelForMaskedLM
model = AutoModelForMaskedLM.from_pretrianed("AI4Protein/DeProt-2048")
```

## Zero-shot mutant effect prediction
```

```

## Representation
```

```

## Transfer-Learning
```

```

## Citation

If you use DeProt in your research, please cite the following paper:

```

```