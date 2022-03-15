# Structure Incorporation into Evolutionary Search Operators 

Contains code to replicate studies for structure incorporation of continuous optimization problems into search operators.

## Introduction

The code we provide within our repository is derivative of our paper nomination [Representing Experience in Continuous Evolutionary Optimisation through Problem-tailored Search Operators](https://ieeexplore.ieee.org/document/9185687) (Friess, Tiňo, Menzel, Sendhoff & Yao, 2020) at IEEE CEC 2020. It can also be used to replicate the experiments of our papers submitted to SSCI 2019 and PPSN 2020. However, we caution that the proposed self-adpation mechanism in the latter publication is erroneous. 

The code is implemented in Python 3.0 and the required libraries are elaborated in the following up technical requirements part. 
(Describe repository structure)

In the following, we will give a more in-depth description on the technical requirements and how to use our scripts accordingly.

## Technical Requirements

To obtain structured data formats using search space partition methods, we use a k-means implementation from the Scikit-Learn software package. For the construction of Delaunay graphs, the SciPy software package can be used. Further, optimized implementations of the self-organized map and growing neural gas are contained within the NeuPy library. For implementing the neural network architectures we use Keras with a TensorFlow backend.  

All required libraries can be installed by executing `pip install -r requirements.txt` from the main directory via the command line. 


| Library       | Description |
| ------------- |:-------------|
| DEAP        | Provides different implementations of EAs. |
| GPyOpt      | Library for hyperparameter tuning. | 
| Scikit-Learn       | Implements the k-Means clustering.  |

The following sections elaborate on how to replicate the steps and experiments presented within our paper.

## Running Experiments

Please mail s.friess(AT)bham.ac.uk and ask for password to access preliminary files. 

## How to Cite

Please when using any code provided in the repository cite the following paper.

### Paper Reference
* Friess, S., Tiňo, P., Menzel, S., Sendhoff, B. and Yao, X., 2020, July. Representing Experience in Continuous Evolutionary Optimisation through Problem-tailored Search Operators. In 2020 IEEE Congress on Evolutionary Computation (CEC) (pp. 1-7). IEEE.

### BibTeX Reference
```
@inproceedings{friess2020representing,
  title={Representing Experience in Continuous Evolutionary Optimisation through Problem-tailored Search Operators},
  author={Friess, Stephen and Ti{\v{n}}o, Peter and Menzel, Stefan and Sendhoff, Bernhard and Yao, Xin},
  booktitle={2020 IEEE Congress on Evolutionary Computation (CEC)},
  pages={1--7},
  year={2020},
  organization={IEEE}
}
```

## Acknowledgements

This research has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement number 766186 (ECOLE). It was also supported by the Program for Guangdong Introducing Innovative and Enterpreneurial Teams (Grant No. 2017ZT07X386), Shenzhen Science and Technology Program (Grant No. KQTD2016112514355531), and the Program for University Key Laboratory of Guangdong Province (Grant No. 2017KSYS008).
