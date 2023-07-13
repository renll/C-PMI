<h1 align="center">C-PMI: Conditional Pointwise Mutual Information for Turn-level Dialogue Evaluation</h1>
<div align="center">
  <span class="author-block">
    <a href="https://renll.github.io/">Liliang Ren</a>,</span>
  <span class="author-block">
    <a href="https://mankeerat.github.io/">Mankeerat Sidhu</a>,</span>
  <span class="author-block">
    <a href="https://vickizeng.com/">Qi Zeng</a>,
  </span>
  <span class="author-block">
    <a href="https://gangiswag.github.io/">Revanth Gangi Reddy</a>,
  </span>
  <span class="author-block">
    <a href="https://blender.cs.illinois.edu/hengji.html">Heng Ji</a>,
  </span>
    <span class="author-block">
    <a href="http://czhai.cs.illinois.edu/">ChengXiang Zhai</a>
  </span>
</div>
<div align="center">
  <span class="author-block">University of Illinois at Urbana-Champaign</span>
</div>

[![arXiv](https://img.shields.io/badge/arXiv-2306.15245-brightgreen.svg?style=flat-square)](https://arxiv.org/abs/2306.15245)  [![slides](https://img.shields.io/badge/slides-blue)](https://drive.google.com/file/d/1ArAFG2MU0ek5bIqYiWUiJ4x3msieo04g/view?usp=sharing)  

## Abstract 

We propose a novel model-agnostic approach that
leverages Conditional Pointwise Mutual Information (C-PMI) to measure the turn-level interaction between the system and the user based
on a given evaluation dimension. Experimental
results on the widely used FED dialogue evaluation dataset demonstrate that our approach
significantly improves the correlation with human judgment compared with existing evaluation systems. By replacing the negative loglikelihood-based scorer with our proposed CPMI scorer, we achieve a relative 60.5% higher
Spearman correlation on average for the FED
evaluation metric. 

## Code Structure

The implementation of C-PMI is quite simple and only needs a few lines of code. Running the jupyter notebook, [c-pmi.ipynb](c-pmi.ipynb), will reproduce the experiment results in our paper. Our C-PMI and C-PMI-SYM scorer are defined as the function `MI_score_turn_pmi` and the function `MI_score_turn_sympmi` respectively in the notebook.




## Citation

If you find our work useful, please consider citing:
```
@article{ren2023cpmi,
  title   = {C-PMI: Conditional Pointwise Mutual Information for Turn-level Dialogue Evaluation},
  author  = {Liliang Ren and Mankeerat Sidhu and Qi Zeng and Revanth Gangi Reddy and Heng Ji and ChengXiang Zhai},
  year    = {2023},
  journal = {arXiv preprint arXiv: 2306.15245}
}
```

## Contact

Liliang Ren (liliang3@illinois.edu)