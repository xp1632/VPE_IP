# VPE_IP: Simplify and Enlarge (?? enhancement)
## Seamless Image Data Transitions via a Configurable State Machine

An example：
We create semantic Image type and build the knowledge graph compositing of different low-level images data format(ndarray, fiji image, pil image, tensor) and data schema ([B, C, H W] VS [C, H, W] VS [H, W], intensity range [0, 255] vs [0, 1], rgb vs gbr) and conversion rules.
![image](https://github.com/Max-ChenFei/VPE_IP/assets/28513798/a1ae9628-f355-44fb-bb23-d39875eb1e1b)

Another example is Path, string, relative path, absolute path

## Break the single language execution in the visual programming environment and ??? increase the scope of expression of visual programming???
Previously, in visual programming there are only generate one language, In order to enlarge the visual programming scope???, we create a mechanism that allows mixing the language execution, that is kernel protocol instances in the computation notebook including Fiji Kernel


## Todo
- [ ] better topic? image processing, quick and easy pipeline building(type conversion), increasing the pipline scope (support many backends)?
