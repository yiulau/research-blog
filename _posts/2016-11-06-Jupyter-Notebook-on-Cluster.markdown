---
layout: post
title:  "How to set up Jupyter notebook on cluster and connect to it"
categories: jekyll update
---
Go to the cluster (stat12 in this case) and set up an Ipython notebook with

`
ipython notebook --no-browser --port=8889
`

or a Jupyter notebook with 

`
jupyter notebook --no-browser --port=8889
`

The choice of port 8889 is arbitary.

Now on your local computer connect to the notebook running on the cluster with

~~~~
ssh -t -t -L8888:localhost:9999 yiulau@gate.math.mcgill.ca ssh -t -t -L9999:localhost:8889 -N stat12
~~~~ 

Now you can type in `localhost:8888` in your internet browser to use the notebook. 
