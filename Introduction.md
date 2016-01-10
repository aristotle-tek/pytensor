# Introduction #

Tensors, also known as n-way arrays/ multi-dimensional arrays are widely used in various data-mining applications. Combined with the easy representation of multi-dimensional datta, tensor algebra offers a powerful means to organize, represent and visualize complex data. A detailed explanation of the tensor literature is beyond the scope of this document. However, we refer the users to look at the References section.

In this section, we provide a brief overview of how tensors can be used in the context of representing molecular dynamics trajectory data as well as how one can construct tensors out of them.

We envisage the MD trajectory as a collection of frames much like a movie which is a collection of images. In images, there are parts of that change often than others and in proteins, there are regions that show larger fluctuations than others. Therefore, we believe that looking at a MD trajectory as a time-evolving stream of molecular data will provide us with an ability to analyze simulations as they are progressing.