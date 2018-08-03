# community_detection
## Introduction
Differnt algorithm to do community_detection.
## Operation Environment
- python-igraph
- xlrd
## DataInput
- Data
> g1 g2 v1 <br>
> g2 g1 v2 <br>
> g1 g3 v3 <br>
> ... <br>
- Label
> id1 label1 <br>
> id2 label2 <br>
> id3 label3 <br>
> id4 label4 <br>
You have to alter value `matrix_file` and `label_file` in the code.Also you have to choose the algorithm you need.
- Algorithm
> LPA,BGLL,walktrap,fastgreedy
## DataOutput
Modularity and the Graph
![imgae](https://github.com/TerenceLiu2/community_detection/blob/master/1.png)
