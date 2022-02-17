
## Gradient Based Activations for Accurate Bias-Free Learning
Pytorch code for our GBA model please refer the [[Paper](https://vinodkkurmi.github.io/GBA)]

Accepted at [[AAAI 2022](https://aaai.org/Conferences/AAAI-22/)]

#####  [[Project]](https://vinodkkurmi.github.io/GBA)     [[Paper Link (coming soon) ]](https://vinodkkurmi.github.io/GBA)

#### Abstract
Bias mitigation in machine learning models is imperative, yet challenging. While several approaches have been proposed, one view towards mitigating bias is through adversarial learning. A discriminator is used to identify the bias attributes such as gender, age or race in question. This discriminator is used adversarially to ensure that it cannot distinguish the bias attributes. The main drawback in such a model is that it directly introduces a trade-off with accuracy as the features that the discriminator deems to be sensitive for discrimination of bias could be correlated with classification. In this work we solve the problem. We show that a biased discriminator can actually be used to improve this bias-accuracy tradeoff. Specifically, this is achieved by using a feature masking approach using the discriminator’s gradients. We ensure that the features favoured for the bias discrimination are de-emphasized and the unbiased features are enhanced during classification. We show that this simple approach works well to reduce bias as well as improve accuracy significantly. We evaluate the proposed model on standard benchmarks. We improve the accuracy of the adversarial methods while maintaining or even improving the unbiasness and also outperform several other recent methods.

![Result](https://vinodkkurmi.github.io/GBA/img/model.jpg)


### Reference

If you use this code as part of any published research, please acknowledge the following paper

```
@InProceedings{Kurmi_2022_AAAI,
    author    = {K Kurmi, Vinod   and  Sharma, Rishabh and Sharma ,Yash Vardhan  and Namboodiri, Vinay P.},
    title     = {Gradient Based Activations for Accurate Bias-Free Learning},
    booktitle = {AAAI},
    month     = {Feb},
    year      = {2022},
   
```

## Contributors
* [Vinod K. Kurmi][1]   (vinodkumarkurmi@gmail.com)
* [Rishabh Sharma][2] (rsharma1@me.iitr.ac.in)
* [Yash Vardhan Sharma][3] (ysharma@me.iitr.ac.in)




[1]: https://github.com/vinodkkurmi
[2]: https://github.com/vinodkkurmi
[3]: https://github.com/vinodkkurmi

