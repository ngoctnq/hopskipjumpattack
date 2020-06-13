# HopSkipJumpAttack
A barebone implementation based on [this paper](https://arxiv.org/pdf/1904.02144.pdf) by Chen *et. al*.

Another writeup is written (in Vietnamese) by me [here](https://viblo.asia/p/b5-hopskipjumpattack-a-query-efficient-decision-based-attack-L4x5xLGm5BM).

## How to use
Documentation is written neatly in docstrings, so it can be easily exported if needed.

Also, one can open the notebook and export it as a `.py` file for ease of import.

## Notes
- Currently only supports L2 norm, but L-infinity support should be straightforward.
- This repo is mostly a learning experience. There are already (probably better) implementations of this:
  - [@Jianbo-Lab](https://github.com/Jianbo-Lab)/[HJSA](https://github.com/Jianbo-Lab/HSJA) (this is the paper's author's repo)
  - [@tensorflow](https://github.com/tensorflow)/[cleverhans](https://github.com/tensorflow/cleverhans) (install the edge version on GitHub, the one in `pip` still does not have HSJA.)
  - [@bethgelab](https://github.com/bethgelab)/[foolbox](https://github.com/bethgelab/foolbox) (HSJA was removed in some commit I didn't track, but it used to be there.)
