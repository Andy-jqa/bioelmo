# bioelmo
BioELMo is a biomedical version of embeddings from language model (ELMo), pre-trained on PubMed abstracts. Pre-training uses 10M recent PubMed abstracts (2.46B tokens in total), and BioELMo achieves an averaged forward and backward perplexity of 31.37 on a held-out test set. BioELMo encodes biomedical entity-type and relational information pretty well, as shown in [our paper](https://arxiv.org/abs/1904.02181).

## Download
- [BioELMo weights](https://drive.google.com/file/d/1CHRd5YQrt3ys64WfJkJR1KX72-2CaT4I/view?usp=sharing)
- [options](https://drive.google.com/file/d/19sLZ1NhUtD_bMgTstSRWoVDx6Vm-T8Qt/view?usp=sharing)
- [vocabulary file](https://drive.google.com/file/d/15cXEVoRhUQ9oBnHVFP3nx6GQozczgxgP/view?usp=sharing) (1M most frequenty tokens from the pre-training corpus. For downstream tasks, you can use your own vocabulary.)

## Usage
Please visit https://github.com/allenai/bilm-tf. Basically, you use BioELMo the same way you use ELMo.

## Probing Experiments
Please visit https://github.com/Andy-jqa/probing_biomed_embeddings (currently under construction) for codes of probing experiments described in our paper.

## Citation
Please cite the following paper if you use BioELMo:
```
@article{jin2019probing,
  title={Probing Biomedical Embeddings from Language Models},
  author={Jin, Qiao and Dhingra, Bhuwan and Cohen, William W and Lu, Xinghua},
  journal={arXiv preprint arXiv:1904.02181},
  year={2019}
}
```
