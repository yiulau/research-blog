---
layout: post
title:  "Generate from the Wishart Distribution"
categories: jekyll update
---
$$\frac{d}{d\mathbf{X}}\log \det(\mathbf{X}) = \frac{1}{\det (\mathbf{X})} \det (\mathbf{X}) (\mathbf{X}^{-1})^T  $$

which comes from the fact that 

$$\frac{d}{d\mathbf{X}} \det(\mathbf{X}) =  \det (\mathbf{X}) (\mathbf{X}^{-1})^T  $$

Equation 49 from the reference.

The other important derivative is 

$$ \frac{d}{d \mathbf{X}} tr(A\mathbf{X}) = A^T $$

Equation 100, plus cylical invariance of the trace. 

References: 
[The Matrix Cookbook](http://www2.imm.dtu.dk/pubdb/views/edoc_download.php/3274/pdf/imm3274.pdf)



