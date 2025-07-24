Han Qi
=======
* Email at: `${last_name}${first_name}.dev+jobs` AT gmail
* LinkedIn: hanqihanqi
* X: @chch_gye

## Industry Experiences 

### Software Engineer, Google - Pytorch XLA
<p align="right"> May 2023 - Now</p>

At Google I am the tech lead and maintainer of the [PyTorch / XLA](https://github.com/pytorch/xla) OSS project. 
At Google Cloud, I am the go-to person for everything Pytorch related. My mission here is to make Pytorch users 
have a great experience on Google's TPUs, and drive TPU sales on Google Cloud .

My main achivements are:

1. Designed and lead the implementation of [torchax](https://github.com/pytorch/xla/tree/master/torchax). This is a library for runnig PyTorch programs on TPU by using Jax as an backend. This library also enable PyTorch users to use advanced Jax features, such as `shard_map` and `pallas` kernel DSL.

2.  Designed and lead the implementation of jetstream-pytorch (https://github.com/AI-Hypercomputer/jetstream-pytorch); a high-throughput, multi-device LLM inference engine targetting TPUs. This is lauched in Google Cloud next 2024.

3. Worked on `torch.export` and its integration of PyTorch with Google-AI-Edge (TFLite) acting as the main PoC for partners at On-device ML teams. This work is presented in [Pytorch Conference 2023](https://pytorch2023.sched.com/event/1R3c6/backends-poster-presentations-continued).

4. Optimized Llama 3 405b on CloudTPU (v6e-256) and achieved 35% MFU using `torchax`.

5. Optimized Llama 3 8B on jetstream-pytorch and achieved 8171 token/s on CloudTPU (on v5e-8 TPU, around 2024).

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

### Software Engineer, Meta - Marketplace Search 
<p align="right"> Mar 2020 - Aug 2021</p>
I worked mostly in improving Marketplace search’s retrieval ranking model, improving recall of the search without losing accuracy.

* Contributed significant portion of teams metric goals (NDCG, number of transactions, number of sessions).
* Technologies used: Pytorch, deep neural recommender systems, A/B testing, feature engineering.

### Software Engineer, Google - Search
<p align="right"> Jul 2017 - Mar 2020</p>
I worked on an internal interactive ML library called Ranklab. Ranklab 
is used by search engineer for analyzing different search signals and 
understand behavior of their models. Ranklab is also used to train 
light-weight, candidate generation models that powers Google search at the time,
 mostly [Generalized Additive Models](https://en.wikipedia.org/wiki/Generalized_additive_model), 
 as well as gradient boosted decision forests.

Notable achievements:

1. Reduced Google Search's resource spend (CPU-hours) for dataset  
   generation to a third of previous spend; by migrating old data pipelines
   from legacy MapReduce systems to flume (Spark like distributed processing framework)
2. Adopted [Capacitor](6https://cloud.google.com/blog/products/bigquery/inside-capacitor-bigquerys-next-generation-columnar-storage-format) as the 
   main file format for datasets; reducing data loading time for key workloads to one sixth of previous. 
 





## EDUCATION

### University of California - Berkeley
**Aug 2016 - May 2017**

**Master of Engineering in Computer Science**


Thesis: [BIDViz: Real-time Monitoring and Debugging of Machine Learning Training Processes](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2017/EECS-2017-99.htm)

under supervision of prof. [John Canny](https://en.wikipedia.org/wiki/John_Canny)


### University of Michigan - Ann Arbor
**Sep 2009 - May 2012**

**Double major in Mathematics and Computer Science**

Graduated with High Distinctions


## COMPETITONS and AWARDS

* 12th Place Regional - ACM ICPC Midwest Region - Grand Rapids, MI, 2011
  * (2nd Place on Grand Rapids Site)
  * This is classification round for ACM ICPC 2012, participated as part University of Michigan's team of 3.

* 157th Place - [William Lowell Putnam Competition](https://en.wikipedia.org/wiki/William_Lowell_Putnam_Mathematical_Competition), 2009
* Silver Medal - [Asian-Pacific Mathematical Olympiad](https://www.apmo-official.org/), 2008
* Bronze Medal - [International Mathematical Olympiad](https://www.imo-official.org/), 2007
