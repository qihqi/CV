Han Qi
=======

**qihan.dev@gmail.com · 6224 Shadygrove Dr. Cupertino, CA · 650 862 6616**


## Industry Experiences 

### Software Engineer, Google - Pytorch XLA
<p align="right"> May 2023 - Now</p>

At Google I am the tech lead and maintainer of the [PyTorch / XLA]() OSS project. I am the go-to person for everything Pytorch related. My mission here is to make Pytorch users have a great experience on TPUs, and drive Cloud TPU sales.

My main achivements are:

1. Designed and lead the implementation of [torchax](https://github.com/pytorch/xla/tree/master/torchax). This is a library for runnig PyTorch programs on TPU by using Jax as an backend. This library also enable PyTorch users to use advanced Jax features, such as `shard_map` and `pallas` kernel DSL.

2.  Designed and lead the implementation of jetstream-pytorch; a high-throughput, multi-device LLM inference engine targetting TPUs. This is lauched in Google Cloud next 2024.

3. Worked on `torch.export` and its integration of PyTorch with Google-AI-Edge (TFLite) acting as the main PoC for partners at On-device ML teams. This work is presented in [Pytorch Conference 2023](https://pytorch2023.sched.com/event/1R3c6/backends-poster-presentations-continued).

4. Optimized Llama 3 405b on CloudTPU (v6e-256) and achieved 35% MFU using `torchax`.

5. Optimized Llama 3 8B on jetstream-pytorch and achieved 8171 token/s on CloudTPU (v5e-8).

6. Supported vllm on TPU (sister team)'s Pytorch integration.

### Software Engineer, Meta - Pytorch Compilers 
<p align="right"> Aug 2021 - May 2023 </p>

At Meta I worked in Pytorch Compilers team. My role is to support the
usecases of running models on the edge (mobile and VR devices), collaborating with Pytorch edge runtime team and Reality labs. For this my work are concentrated in `torch.export` and `torchscript`.
My main achievements are:

* Authored the `torch.export`'s IR spec. This later become known as the [ATen dialect](https://docs.pytorch.org/executorch-overview)

* Participated on the design of [executorch](https://docs.pytorch.org/executorch-overview).

* Designed and led the implemention of a new serialization format for pytorch models based on flatbuffer. This speeds up the loading of pytorch models up to 4 times. Reducing cold-start ML inference time Meta's mobile apps as well as applications running on VR devices.

* Reduced Torchscript model's memory overhead which led to reduction of training jobs failing
with OOM by 84%.

## Software Engineer Meta - Marketplace Search 
<p align="right"> Mar 2020 - Aug 2021</p>

* Worked mostly in improving Marketplace search’s retrieval ranking model, improving recall of the search without losing accuracy.
* Contributed significant portion of teams metric goals (NDCG, number of transactions, number of sessions).
* Technologies used: Pytorch, deep neural recommender systems, A/B testing, feature engineering.

## EDUCATION

### University of California - Berkeley
Aug 2016 - May 2017
Master of Engineering in Computer Science
Project: Visualizing Deep Learning with prof. John Canny

### University of Michigan - Ann Arbor
Double major in Mathematics and Computer Science

## COMPETITONS and AWARDS

* University of Michigan Mathematics Merit Scholar, 2012
* 12th Place Regional - ACM ICPC Midwest Region - Grand Rapids, MI, 2011
  * (2nd Place on Grand Rapids Site)
  * This Classification for ACM ICPC 2012, participated as part University of Michigan's team of 3

* Evelyn O. Bychinsky Award, 2011
  * Awarded by Department of Mathematics to students who show promise in mathematics deserving of recognition and encouragement. $1000 Cash prize.
* 157th Place - William Lowell Putnam Competition, 2009
* Silver Medal - Asian-Pacific Mathematical Olympiad, 2008
* Bronze Medal - International Mathematical Olympiad, 2007
