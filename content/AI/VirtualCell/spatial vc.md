# Ref
[OCTO-vc](https://www.noetik.ai/octo-vc)

[Celleporter | Powered by Noetik](https://celleporter.noetik.ai/)

# Static stimulation
mimic a case, and check every cells gene expression:
![Pasted image 20250706121755](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706121755.png)

drop the cells in different location, and check its expression:
![Pasted image 20250706121838](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706121838.png)

also measure along the path to see the markers variation.

check the different cell distribution:
![Pasted image 20250706122249](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706122249.png)

# Dynamic
还有环境互作层面的perturbation：
![Pasted image 20250706123221](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706123221.png)

Increase the expression in a specific type of cell, then see the targets genes in neighbor cells:
![Pasted image 20250706123358](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706123358.png)

also investigate the effects of gene mutation:
![Pasted image 20250706123813](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706123813.png)

# Perturbation
![Pasted image 20250706125252](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706125252.png)
knockout the tumor cells gene to see the effect on cd8T genes expression variation. 

and Modality connection, perturbation a gene, see the target protein change:
![Pasted image 20250706154707](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706154707.png)

IFNG and HLA, obey their biological definition:
![Pasted image 20250706154927](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706154927.png)

# Other works
![Pasted image 20250706154227](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706154227.png)
capture the whole image, from little data.

牛逼啊，some zero-shot ability like:
![Pasted image 20250706154329](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706154329.png)
根据核特点就来推断哪些是癌症哪些是正常的免疫细胞。

what is the `structured masking strategy`, that:
> The structured masking strategy used to train OCTO is critical. This is because models learn different representations of the data depending on what is masked out and what is revealed during training. Models trained via standard masked image modeling, in which the same ~75% of patches are masked across all channels, do not learn high-level biological relationships; instead, they make predictions based on low-level image statistics.

![Pasted image 20250706155045](https://raw.githubusercontent.com/mugpeng/mugpeng-my-gallery-02/main/imgPasted%20image%2020250706155045.png)