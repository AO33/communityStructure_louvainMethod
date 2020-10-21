# communityStructure_louvainMethod
This repository is a python implementation of the Lovain Method for fast unfolding of community structure in large networks (a rewording of the original paper https://arxiv.org/abs/0803.0476)

Similarly structured to the code https://python-louvain.readthedocs.io/en/latest/, but without all the bells and whistles. Instead, this implementation is built for speed by utilizing a "pre-compute" dictionary structure and forgoes copying the input network at the very beginning

