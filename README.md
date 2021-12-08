# Entropic Desired Dynamics for Intrinsic ConTrol (EDDICT), a self-contained JAX implementation

This is a simplified version of the code used in the EDDICT paper (to appear at NeurIPS 2021). In this stand-alone Google Colab, EDDICT is trained on a
continuous grid world with an uncontrollable distractor. The resulting latent representations can then be seen to yield an interpretable model of the
controllable aspects of the environment (i.e. the (x,y) coordinates) while being invariant to the uncontrollable aspects (i.e. the distractor (x,y) coordinates).

## Installation

Simply open the file in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deepmind/EDDICT/blob/master/colab_demo.ipynb)
and run the cells in order. Any runtime should work, but a GPU considerably speeds up training.


## Usage

Run the cells in order to train an EDDICT agent from scratch and visualize its representations.
You can also try modifying the environment (e.g. add walls), or ablate the agent (e.g. what if desired z = delta?), and rerun to see what happens.

## Citing this work

BibTex for citing the EDDICT paper:

```bibtex
@article{hansen2021entropic,
  title={Entropic Desired Dynamics for Intrinsic Control},
  author={Hansen, Steven and Desjardins, Guillaume and Baumli, Kate and Warde-Farley, David and Heess, Nicolas and Osindero, Simon and Mnih, Volodymyr},
  journal={Advances in Neural Information Processing Systems},
  volume={34},
  year={2021}
}
```

## Disclaimer

This is not an official Google product.
