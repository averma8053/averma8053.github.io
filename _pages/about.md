---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
driveId1: 1s1pGcYUavpjBirwwwJnngkizuLkkAcL3/preview
driveId2: 1QVjGP_mquJu0unb4OU_zUFJKy50DS_FR/preview
driveId3: 1BRROPVoPmygeVGgj9KcO25ZhPRsHvtLC/preview
driveId4: 1jxbCfPbw1FU2HDy_4v1Z0uwGWoHGqlSV/preview
redirect_from: 
  - /about/
  - /about.html
---

I am a Hartz Family Career Development Assistant Professor in the [Department of Computer Science and Engineering](https://www.eecs.psu.edu) at The Pennsylvania State University. Previously, I was a postdoc at the Institute of Science and Technology (IST) Austria in the [Henzinger Group](http://pub.ist.ac.at/group_henzinger/). Before joining IST, I completed my PhD from the University of Texas at Austin advised by [Prof. Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/). My research lies at the intersection of machine learning and formal methods, with a focus on building intelligent systems that are reliable, transparent, and secure. This work builds connections between the symbolic reasoning and inductive learning paradigms of artificial intelligence.

# Research Overview

My research combines ideas from formal methods and machine learning to efficiently build models that are reliable, transparent, and secure. This means that such a system can be expected to learn desirable behaviors with limited data, while provably maintaining some essential correctness invariant and generating models whose decisions can be understood by humans. I believe that we can achieve these goals via Neurosymbolic learning.

<details>

<summary>[Read More]</summary>


Current machine learning models are dominated by Deep Neural Networks, because they are capable of leveraging gradient-based algorithms to optimize a specific objective. However, neural models are considered “black-boxes” and are often considered untrustworthy due to the following drawbacks:

<ol>
<li> Hard to interpret: this makes these models hard to audit and debug.</li>
<li> Hard to formally verify: due to the lack of abstractions in neural models they are often too large to verify for desirable behavior using automated reasoning tools.</li>
<li> Unreliable: neural models have notoriously high levels of variability, to the extent that the random initialization of the weights can determine whether the learner finds a useful model.</li>
<li> Lack of domain awareness: neural models lack the ability to bias the learner with commonsense knowledge about the task or environment.</li>
</ol>

My research focuses on addressing these four drawbacks simultaneously, and provides a promising path to discovering new algorithmic techniques leading to Trustworthy Artificial Intelligence.

</details>

<br>

# Publications

- **RetroMoE: A Mixture-of-Experts Latent Translation Framework for Single-step Retrosynthesis**\
Xinjie Li, Abhinav Verma \
International Joint Conference on Artificial Intelligence (IJCAI), 2025.


- **LTL-Constrained Policy Optimization with Cycle Experience Replay**\
[Ameesh Shah](https://ameesh-shah.github.io), [Cameron Voloshin](https://www.clvoloshin.com), [Chenxi Yang](https://chenxi-yang.github.io), Abhinav Verma, [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/), [Sanjit A. Seshia](https://people.eecs.berkeley.edu/~sseshia/) \
Transactions on Machine Learning Research (TMLR), 2025.\
[ArXiv](https://arxiv.org/abs/2404.11578) 


- **Compositional Policy Learning in Stochastic Control Systems with Formal Guarantees**\
Đorđe Žikelić, Mathias Lechner, Abhinav Verma, Krishnendu Chatterjee, Thomas Henzinger\
Advances in Neural Information Processing Systems (NeurIPS), 2023.\
[ArXiv](https://arxiv.org/abs/2312.01456) 


- **Eventual Discounting Temporal Logic Counterfactual Experience Replay**\
[Cameron Voloshin](https://www.clvoloshin.com), Abhinav Verma, [Yisong Yue](http://www.yisongyue.com) \
International Conference on Machine Learning (ICML), 2023.\
[ArXiv](https://arxiv.org/abs/2303.02135) 


- **Neurosymbolic Reinforcement Learning with Formally Verified Exploration**\
[Greg Anderson](https://gavlegoat.github.io), Abhinav Verma, [Isil Dillig](https://www.cs.utexas.edu/~isil/), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/) \
Conference on Neural Information Processing Systems (NeurIPS), 2020.\
[ArXiv](https://arxiv.org/abs/2009.12612) &nbsp; &nbsp; [Code](https://github.com/averma8053/safe-learning)


- **Learning Differentiable Programs with Admissible Neural Heuristics**\
[Ameesh Shah](https://ameesh-shah.github.io), [Eric Zhan](https://ezhan94.github.io), [Jennifer J Sun](http://jenjsun.com), Abhinav Verma, [Yisong Yue](http://www.yisongyue.com), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/) \
Conference on Neural Information Processing Systems (NeurIPS), 2020.\
[ArXiv](https://arxiv.org/abs/2007.12101) &nbsp; &nbsp; [Code](https://github.com/averma8053/near) &nbsp; &nbsp;  [Video](https://drive.google.com/file/d/1jxbCfPbw1FU2HDy_4v1Z0uwGWoHGqlSV/view?usp=sharing)
{% include googleDrivePlayer.html id=page.driveId4 %}


- **Imitation-Projected Programmatic Reinforcement Learning**\
Abhinav Verma, [Hoang M. Le](http://hoangle.info), [Yisong Yue](http://www.yisongyue.com), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/) \
Conference on Neural Information Processing Systems (NeurIPS), 2019.\
[ArXiv](https://arxiv.org/abs/1907.05431) &nbsp; &nbsp; [Code](https://bitbucket.org/averma8053/propel) &nbsp; &nbsp;  [Video](https://drive.google.com/file/d/1BRROPVoPmygeVGgj9KcO25ZhPRsHvtLC/view?usp=sharing)
{% include googleDrivePlayer.html id=page.driveId3 %}


- **Control Regularization for Reduced Variance Reinforcement Learning**\
[Richard Cheng](https://rcheng805.github.io), Abhinav Verma, [Gabor Orosz](http://www-personal.umich.edu/~orosz/), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/), [Yisong Yue](http://www.yisongyue.com), [Joel W. Burdick](http://robotics.caltech.edu/wiki/index.php/JoelBurdick) \
International Conference on Machine Learning (ICML), 2019.\
[ArXiv](https://arxiv.org/abs/1905.05380) &nbsp; &nbsp; [Code](https://github.com/averma8053/CORE-RL) &nbsp; &nbsp; [Video](https://drive.google.com/file/d/1QVjGP_mquJu0unb4OU_zUFJKy50DS_FR/view?usp=sharing)
{% include googleDrivePlayer.html id=page.driveId2 %}


- **Representing Formal Languages: A Comparison Between Finite Automata and Recurrent Neural Networks**\
Joshua J. Michalenko, [Ameesh Shah](https://ameesh-shah.github.io), Abhinav Verma, [Richard G. Baraniuk](http://richb.blogs.rice.edu), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/), [Ankit B. Patel](https://ankitlab.co) \
International Conference on Learning Representations(ICLR), 2019.\
[ArXiv](https://arxiv.org/abs/1902.10297)


- **Programmatically Interpretable Reinforcement Learning**\
Abhinav Verma, [Vijayaraghavan Murali](https://research.fb.com/people/murali-vijayaraghavan/), [Rishabh Singh](https://rishabhmit.bitbucket.io), [Pushmeet Kohli](https://sites.google.com/site/pushmeet/), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/) \
International Conference on Machine Learning (ICML), 2018.\
[ArXiv](https://arxiv.org/abs/1804.02477) &nbsp; &nbsp;  [Video](https://goo.gl/Z2X5x6) {% include googleDrivePlayer.html id=page.driveId1 %}

&nbsp;

# PhD Thesis
[Programmatic Reinforcement Learning](/files/AbhinavVermaThesis.pdf)


# Teaching

- (Fall 2022) CSE 597: Neurosymbolic Learning
- (Spring 2023) CMPSC 448: Machine Learning and Algorithmic AI