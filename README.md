# ReNAS
Neural Architecture Search (NAS) is a collection of methods to craft the way neural networks are built. Current NAS methods are far from ab initio and automatic, as they use manual backbone architectures or micro building blocks (cells), which have had minor breakthroughs in performance compared to random baselines. They also involve a significant manual expert effort in various components of the NAS pipeline. This raises a natural question - Are the current NAS methods still heavily dependent on manual effort in the search space design and wiring like it was done when building models before the advent of NAS? In this work, instead of merely chasing slight improvements over state-of-the-art (SOTA) performance, we revisit the fundamental approach to NAS and propose a novel approach called ReNAS that can search for the complete neural network without much human effort and is a step closer towards AutoML-nirvana. Our method starts from a complete graph mapped to a neural network and searches for the connections and operations by balancing the exploration and exploitation of the search space. The results are on-par with the SOTA performance with methods that leverage handcrafted blocks. We believe that this approach may lead to newer NAS strategies for a variety of network types.

##

The paper can be found at https://arxiv.org/abs/2010.05719
