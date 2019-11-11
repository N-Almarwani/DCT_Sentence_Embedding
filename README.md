# Efficient Sentence Embedding using Discrete Cosine Transform

**Dependencies**

- Download SentEval from [this link ](https://github.com/facebookresearch/SentEval) and follow their instructions to download datasets and Dependencies.

- Add DCT.py to examples directory.



**How to use this code**

1- To reproduce the results for DCT, run (in examples/):
```
python DCT.py 'k'
```
where k is the number of cofficents to keep.

2- For parameeters tuning please follow the instructions from SentEval. 




**References**

Please considering citing [1] and [2] if using this code for evaluating DCT sentence embedding methods using Senteval tool.

**Efficient Sentence Embedding using Discrete Cosine Transform**

[1] Almarwani, Nada, Hanan Aldarmaki, and Mona Diab. "Efficient Sentence Embedding using Discrete Cosine Transform." 
```
@inproceedings{almarwani2019efficient,
  title={Efficient Sentence Embedding using Discrete Cosine Transform},
  author={Almarwani, Nada and Aldarmaki, Hanan and Diab, Mona},
  booktitle={Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)},
  pages={3663--3669},
  year={2019}
}
```
**SentEval: An Evaluation Toolkit for Universal Sentence Representations**

[2] A. Conneau, D. Kiela, SentEval: An Evaluation Toolkit for Universal Sentence Representations
```
@article{conneau2018senteval,
  title={SentEval: An Evaluation Toolkit for Universal Sentence Representations},
  author={Conneau, Alexis and Kiela, Douwe},
  journal={arXiv preprint arXiv:1803.05449},
  year={2018}
}
```
