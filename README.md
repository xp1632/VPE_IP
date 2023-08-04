# VPE_IP
Content
1. High-Level Semantic Image Type
2. Automatic Low-Level Type Conversation using a knowledge graph
3. Typical execution prototype instances in the computation notebook including Fiji Kernel

## Todo
- [ ] better topic? image processing, quick and easy pipeline building(type conversion), increasing the pipline scope (support many backends)?

## Data type convertion thoughts:

Data preprocessing between nodes

image low-level expression: ndarray, fiji, pil, tensor

- 4 dimensions
- batches size
- Intensity range
- Vanilla image type format and extend for domain

## Two parts of implementation for data type convertion
The work for a thesis is mainly defined in two parts:

1. In high level, build jupyter kernel protocol
		- Binding codes/other libraries API  through jupyterlab to our front-end
		- there's a mature class already defined in jupyterlab  as tunnel to use other libraries
		- but we need to know how to use this class
		- and solving the problems when we use it in different cases
		
2. Translating Data
		-we'll have data from feiji
		-and we'll have a data graph where several data forms are in the data graph

- we need to find the fastest way to translate date from form red to form green
- 关于data 转换 这个 可以是我们构建一个data knowledge graph
- ”知识图谱“ 
