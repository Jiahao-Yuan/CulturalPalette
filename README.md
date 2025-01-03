<div align="center" style="font-size:25px;text-align:center"><img src="./asset/logo.png" width="30" style="margin-bottom: 0.2;"/>
 <strong>Cultural Palette: Pluralising Culture Alignment via Multi-Agent Palette</strong></div>
Datasets of the paper "Cultural Palette: Pluralising Culture Alignment via Multi-Agent Palette".

## Model Architecture
<img src="./asset/model.png" align="center">

## News
* ```2024.12.15``` 🎉🎉🎉 We source the Pentachromatic Cultural Palette Dataset.
## Dataset
### Download
We provide an example for downloading our datasets via HuggingFace.
```python
from datasets import load_dataset
dataset = load_dataset("CulturalPalette/CulturalPalette")
```
### Format Explanation
```json
{
  "query": "You are a knowledgeable chatbot about {Continent A}, including its culture, history, and nuances, providing insightful and context-aware responses. {Query from PRISM}",
  "response": "{Continent A Preferred Response}",
  "rejected_response": "{Other Continents Preferred Responses}"
}
```

### Semantic representation (PCA) on PRISM and Pentachromatic Cultural Patette Dataset 
<img src="./asset/dataset.png" align="center" width="25%">


## Citation
If you find our work useful for your research, please kindly cite our paper as follows:
```bibtex
@article{yuan2024cultural,
  title={Cultural Palette: Pluralising Culture Alignment via Multi-agent Palette},
  author={Yuan, Jiahao and Di, Zixiang and Zhao, Shangzixin and Naseem, Usman},
  journal={arXiv preprint arXiv:2412.11167},
  year={2024}
}
```
## Acknowledge
We gratefully acknowledge [PRISM](https://github.com/HannahKirk/prism-alignment) for invaluable contribution to our dataset.

