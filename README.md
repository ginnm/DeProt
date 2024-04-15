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
See notebook [Zero-shot mutant effect prediction](zero_shot/score_mutant.ipynb)

## Run ProteinGYM Benchmark

Download dataset from [Google Driver](https://drive.google.com/file/d/1-HB5be-pMiuVc-4S2S4sH0Yf7b6u5tno/view)


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