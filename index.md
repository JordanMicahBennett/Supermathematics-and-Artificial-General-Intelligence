


This thread concerns attempts to construct artificial general intelligence, which I often underline [may likely be mankind's last invention.](https://www.youtube.com/watch?v=9snY7lhJA4c)

I am asking anybody that knows [supermathematics](https://en.wikipedia.org/wiki/Supermathematics) and machine learning to pitch in the discussion below.



<h1>Part A - Babies know physics</h1>
Back in 2016, I [read somewhere that babies know some physics intuitively](https://www.washingtonpost.com/news/speaking-of-science/wp/2015/04/02/new-study-reveals-the-shockingly-complex-thought-processes-of-infants/?utm_term=.dd0b9545030b). 
Also, it is empirically observable that babies use that intuition to develop abstractions of knowledge, [in a reinforcement learning like manner](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3490621/).



<h1>Part B - Algorithms for reinforcement learning and physics</h1>
Now, I knew beforehand of two types of major deep learning models, that:

(1) used reinforcement learning. ([Deepmind Atari q](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf))
(2) learn laws of physics. ([Uetorch](https://github.com/facebook/UETorch))

**However**:

(a) Object detectors like [(2)](https://github.com/facebook/UETorch) use something called [pooling](http://iamaaditya.github.io/2016/03/one-by-one-convolution/) to gain translation invariance over objects, so that the model learns regardless of where the object in the image is positioned.
(b) Instead, [(1)](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)  excludes pooling, because [(1)](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)  requires translation variance, in order for Q learning to apply on the changing positions of the objects in pixels.


<h1>Part C - I sought to create...</h1>
As a result I sought a model that could deliver both translation invariance and variance at the same time, and reasonably, **part of the solution** was models that disentangled factors of variation, i.e. [manifold learning frameworks](https://arxiv.org/abs/1611.03383).

I didn't stop my scientific thinking at [manifold learning](http://scikit-learn.org/stable/modules/manifold.html) though.

Given that cognitive science may be used to constrain machine learning models ([similar to how firms like Deepmind often use cognitive science as a boundary on the deep learning models they produce](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)) I sought to create a disentanglable model that was as constrained by cognitive science, as far as algebra would permit.



<h1>Part D - What I did to approach the problem...</h1>
As a result I created something called the [supermanifold hypothesis in deep learning](https://www.academia.edu/31926696/Supermanifold_Hypothesis_via_Deep_Learning_) (a component in another description called ['thought curvature'](https://www.academia.edu/25733790/Thought_Curvature_An_underivative_hypothesis)). 

This was due to [evidence of supersymmetry in cognitive science](https://arxiv.org/abs/0705.1134); I compacted machine learning related algebra for disentangling, in the regime of [supermanifolds](https://en.wikipedia.org/wiki/Supermanifold). This could be seen as an extension of [manifold learning in artificial intelligence](http://scikit-learn.org/stable/modules/manifold.html).

**Given that the [supermanifold hypothesis](https://www.academia.edu/31926696/Supermanifold_Hypothesis_via_Deep_Learning_) compounds** ϕ(x,θ,https://i.imgur.com/ncrjUdkm.png)<SUP>T</SUP>w, **here is an annotation of the hypothesis:**


1. [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning) entails ϕ(x;θ)<SUP>T</SUP>w, that denotes the input space x, and learnt representations θ.
2. [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning) underlines that coordinates or latent spaces in the [manifold](https://en.wikipedia.org/wiki/Manifold) framework, are learnt features/representations, or directions that are sparse configurations of coordinates.
3. [Supermathematics](https://en.wikipedia.org/wiki/Supermathematicsg) entails (x,t,https://i.imgur.com/ncrjUdkm.png), that denotes some x valued coordinate distribution, and by extension, directions that compact coordinates via θ,¯<sub>θ</sub>
4.  As such, the aforesaid (x,θ,https://i.imgur.com/ncrjUdkm.png), is subject to coordinate transformation.
5. Thereafter 1, 2, 3, 4 and [supersymmetry in cognitive science](https://arxiv.org/abs/0705.1134), within the generalizable nature of [euclidean space](https://en.wikipedia.org/wiki/Euclidean_space), reasonably effectuate ϕ(x,θ,https://i.imgur.com/ncrjUdkm.png)<SUP>T</SUP>w.


<H1>QUESTIONS</H1>

Does anybody here have good knowledge of [supermathematics](https://en.wikipedia.org/wiki/Supermathematics) or related field, to give any input on the above?

If so is it feasible to pursue the model I present in [supermanifold hypothesis paper](https://www.academia.edu/31926696/Supermanifold_Hypothesis_via_Deep_Learning_)?

And if so,  apart from the ones discussed in the [paper](https://www.academia.edu/31926696/Supermanifold_Hypothesis_via_Deep_Learning_), what type of pˆdata (training samples) do you garner warrants reasonable experiments in the regime of the [model I presented](https://www.academia.edu/31926696/Supermanifold_Hypothesis_via_Deep_Learning_)?
