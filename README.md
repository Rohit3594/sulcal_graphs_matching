This repository contains the source code and data corresponding to PLOS 2023 publication:

## Population-wise Labeling of Sulcal Graphs using Multi-graph Matching.

The graph matching methods used in this work were implemented using authors implementation and can be found in their corresponding repositories:
#### [Kernelized graph matching](https://proceedings.neurips.cc/paper_files/paper/2019/file/cd63a3eec3319fd9c84c942a08316e00-Paper.pdf) ([Code](https://github.com/ZhenZhang19920330/KerGM_Code))

#### [Multi-image matching via fast alternating minimization](https://arxiv.org/pdf/1505.04845.pdf) ([Code](https://github.com/zju-3dv/multiway))
#### [Multi-Graph Matching via Affinity Optimization with Graduated Consistency Regularization](https://faculty.cc.gatech.edu/~zha/papers/TPAMI2477832_V2.pdf) ([Code](https://github.com/Thinklab-SJTU/pygmtools))
#### [Solving the multi-way matching problem by permutation synchronization](https://pages.cs.wisc.edu/~pachauri/perm-sync/assignmentsync.pdf) ([Code](https://pages.cs.wisc.edu/~pachauri/perm-sync))

----------------------------------------------------------------------------------------------------------

### Dependencies:

These dependencies are mandatory for the implementation of scripts provided:

#### 1. [SLAM](https://github.com/gauzias/slam)
#### 2. [VISBRAIN](https://github.com/EtienneCmb/visbrain)


### To generate a population of simulated graph(specify the parameters in script):
`python script_generation_graphs_with_edges_permutation_updated.py`


### Cite Bibtex
@article{yadav2023population,
  title={Population-wise labeling of sulcal graphs using multi-graph matching},
  author={Yadav, Rohit and Dup{\'e}, Fran{\c{c}}ois-Xavier and Takerkart, Sylvain and Auzias, Guillaume},
  journal={Plos one},
  volume={18},
  number={11},
  pages={e0293886},
  year={2023},
  publisher={Public Library of Science San Francisco, CA USA}
}
