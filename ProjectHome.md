# What is pytensor? #

Provides a python implementation of the tensor toolkit. Implements tensor, sptensor and ttensor classes. The algorithm is being used to mine for spatio-temporal patterns in Molecular Dynamics (MD) simulations by looking at how distance fluctuations or any indicator of collective behavior in proteins change over time. For more details on its application to protein data, please refer to:

  * Arvind Ramanathan, Ji Oh Yoo, Christopher J. Langmead, On-the-fly identification of conformational substates from molecular dynamics simulations. J. Chem. Theo. Comput. (2011, in press) [Paper](http://pubs.acs.org/doi/abs/10.1021/ct100531j)

  * Arvind Ramanathan, Ji Oh Yoo, Christopher J. Langmead, PyTensor: A Python based Tensor Library. CMU-CS-10-102 [Tech-Report](http://www.cs.cmu.edu/~cjl/papers/CMU-CS-10-102.pdf)

  * Arvind Ramanathan, Pratul K. Agarwal, Maria G. Kurnikova, Christopher J. Langmead, An Online Approach for Mining Collective Behaviors from Molecular Dynamics Simulations, RECOMB 2009, Tuscon, AZ. [Conference](http://www.cs.cmu.edu/~cjl/papers/RAKLRECOMB09.pdf) [Journal](http://www.cs.cmu.edu/~cjl/papers/RAKLRECOMB09.pdf)

  * Arvind Ramanathan, Pratul K. Agarwal and Christopher J. Langmead, Using Tensor Analysis to Characterize Contact-Map Dynamics of Proteins, [Tech-Report](http://reports-archive.adm.cs.cmu.edu/anon/2008/CMU-CS-08-109.pdf).


---


This implementation of tensor libraries are based on [Tensor Tool-box](http://csmr.ca.sandia.gov/~tgkolda/TensorToolbox/), a freely licensed MATLAB toolbox from Sandia National Laboratory. For more details refer to:

  * Brett W. Bader and Tamara G. Kolda, Efficient MATLAB computations with sparse and factored tensors, Technical Report SAND2006-7592, Sandia National Laboratories, Albuquerque, NM and Livermore, CA, 2006.
  * Brett W. Bader and Tamara G. Kolda, Algorithm 862: MATLAB Tensor Classes for Fast Algorithm Prototyping, ACM Transactions on Mathematical Software, 32(4), December 2006.

  * Brett W. Bader and Tamara G. Kolda, MATLAB Tensor Toolbox Version 2.3 http://csmr.ca.sandia.gov/~tgkolda/TensorToolbox/, July 2009.


Apart from implementing the basic classes in tensor tool-box, pytensor also provides an implementation of Dynamic Tensor Analysis (DTA), which is an efficient algorithm that mines both spatial and temporal patterns from data. For more details refer to:

  * Jimeng Sun, Dacheng Tao, Christos Faloutsos, Beyond Streams and Graphs: Dynamic Tensor Analysis, KDD' 06. [Paper](http://www.cs.cmu.edu/~christos/PUBLICATIONS/kdd06DTA.pdf)
