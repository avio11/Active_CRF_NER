# Active_NER
Active learning based algorithm for named entity recognition using CRF model on CoNLL03 dataset.

### Sampling strategies implemented thus far: 

1) Uncertainty-based
  - Least confidence
  - ~Margin confidence~ (Coming soon!!)
  - ~Entropy~ (Coming soon!!)
  
2) Random sampling (used as a comparative baseline)

### Simple example comparing LC (Least Confidence) and RAND (Random sampling) sampling functions </h3>

![Compare LC and RAND sampling functions](https://github.com/avio11/Active_NER/blob/master/images/first_result.png)

Note: At first the code is presented as an ipython notebook, which should later be converted into python files for ease of use for different datasets.
