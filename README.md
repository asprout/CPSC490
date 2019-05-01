# CPSC490
Final code for CPS490 senior project

### Abstract
The human brain is a highly complex processing system, and analysis of brain imaging data has proven to be difficult and prone to issues introduced by noise and the curse of dimensionality. However, advances in mathematics and the computational sciences provide a means through which we can better investigate brain activity to identify meaningful signals. In this paper, we take advantage of several recent developments in computational methods, focusing on the uses of the dimensionality reduction and feature extraction techniques of shared response modeling and diffusion mapping, in order to explore the neural mechanisms underlying attention and memory. In particular, using the public Sherlock fMRI dataset, we investigate: (1) the similarities and differences in bottom-up and top-down attentional processing among different subjects, (2) the structure of our neural representations of the environment, (3) how later memory of an event can be predicted solely by patterns of brain activity evoked during the experience of the event, and (4) what information is preserved following applications of dimensionality reduction to brain imaging data. Notably, we find support for a shared low-dimensional representation of event features among participants that may govern bottom-up attention, and individual-specific higher-dimensional feature representations that may play an important role in top-down attention, such that both sources of information can be used to reliably predict later recall.  We conclude by demonstrating the usefulness of advanced computational techniques in neuroscience research, and suggest future directions of research that may lead to future solutions to current computational challenges, highlighting the mutual benefits of open collaboration and interdisciplinary work in the computational and cognitive sciences.

### Notes
The final report is available upon request.

The data necessary to run the code were obtained from the following sources:

Original data from Chen et al. (2017):
Chen, J., Leong, Y.C., Honey, C.J., Yong, C.H., Norman, K.A., & Hasson, U. (2017). Shared memories reveal shared structure in neural activity across individuals. Nature Neuroscience 20(1), 115–125. https://doi.org/10.1038/nn.4450

Whole brain mask from Vodrahalli (2016):
Vodrahalli, K., Chen, P.-H., Liang, Y., Baldassano, C., Chen, J., Yong, E., Honey, C., Hasson, U., Ramadge, P., Norman, K., & Arora, S. (2016). Mapping between natural movie fMRI responses and word-sequence representations. Preprint at https://arxiv.org/abs/1610.03914.
