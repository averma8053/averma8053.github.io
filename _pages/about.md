---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
driveId1: 1s1pGcYUavpjBirwwwJnngkizuLkkAcL3/preview
driveId2: 1QVjGP_mquJu0unb4OU_zUFJKy50DS_FR/preview
driveId3: 1BRROPVoPmygeVGgj9KcO25ZhPRsHvtLC/preview
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD Candidate in the Computer Science Department at the University of Texas at Austin. I am advised by [Prof. Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/). I am generously supported by a [J.P. Morgan AI Research PhD Fellowship](https://www.jpmorgan.com/global/technology/ai/awards/phd-fellowship-award-recipients-2020).

# Research Overview

My research combines ideas from formal methods and machine learning to efficiently build models that are reliable, transparent, and secure. This means that such a system can be expected to learn desirable behaviors with limited data, while provably maintaining some essential correctness invariant and generating models whose decisions can be understood by humans. I believe that we can achieve these goals via Neurosymbolic learning, which establishes connections between the symbolic reasoning and inductive learning paradigms of artificial intelligence.


Current machine learning models are dominated by Deep Neural Networks, because they are capable of leveraging gradient-based algorithms to optimize a specific objective. However, neural models are considered “black-boxes” and are often considered untrustworthy due to the following drawbacks:


1. Hard to interpret: this makes these models hard to audit and debug.
2. Hard to formally verify: due to the lack of abstractions in neural models they are often too large to verify for desirable behavior using automated reasoning tools.
3. Unreliable: neural models have notoriously high levels of variability, to the extent that the random initialization of the weights can determine whether the learner finds a useful model.
4. Lack of domain awareness: neural models lack the ability to bias the learner with commonsense knowledge about the task or environment.

My research focuses on addressing these four drawbacks simultaneously, and provides a promising path to discovering new algorithmic techniques leading to Trustworthy Artificial Intelligence.



# Publications

1. *Neurosymbolic Reinforcement Learning with Formally Verified Exploration*\
Greg Anderson, Abhinav Verma, [Isil Dillig](https://www.cs.utexas.edu/~isil/), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/) \
Conference on Neural Information Processing Systems (NeurIPS), 2020.\
[ArXiv](https://arxiv.org/abs/2009.12612)

2. *Learning Differentiable Programs with Admissible Neural Heuristics*\
Ameesh Shah, Eric Zhan, [Jennifer J Sun](http://jenjsun.com), Abhinav Verma, [Yisong Yue](http://www.yisongyue.com), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/) \
Conference on Neural Information Processing Systems (NeurIPS), 2020.\
[ArXiv](https://arxiv.org/abs/2007.12101)

3. *Imitation-Projected Programmatic Reinforcement Learning* {% include googleDrivePlayer.html id=page.driveId3 %}
\
Abhinav Verma, [Hoang M. Le](http://hoangle.info), [Yisong Yue](http://www.yisongyue.com), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/) \
Conference on Neural Information Processing Systems (NeurIPS), 2019.\
[ArXiv](https://arxiv.org/abs/1907.05431)  &nbsp; &nbsp;  [Video](https://drive.google.com/file/d/1BRROPVoPmygeVGgj9KcO25ZhPRsHvtLC/view?usp=sharing)

4. *Control Regularization for Reduced Variance Reinforcement Learning* {% include googleDrivePlayer.html id=page.driveId2 %}\
[Richard Cheng](https://rcheng805.github.io), Abhinav Verma, [Gabor Orosz](http://www-personal.umich.edu/~orosz/), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/), [Yisong Yue](http://www.yisongyue.com), [Joel W. Burdick](http://robotics.caltech.edu/wiki/index.php/JoelBurdick) \
International Conference on Machine Learning (ICML), 2019.\
[ArXiv](https://arxiv.org/abs/1905.05380) &nbsp; &nbsp;  [Video](https://drive.google.com/file/d/1QVjGP_mquJu0unb4OU_zUFJKy50DS_FR/view?usp=sharing)

5. *Representing Formal Languages: A Comparison Between Finite Automata and Recurrent Neural Networks*\
Joshua J. Michalenko, Ameesh Shah, Abhinav Verma, [Richard G. Baraniuk](http://richb.blogs.rice.edu), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/), [Ankit B. Patel](https://ankitlab.co) \
International Conference on Learning Representations(ICLR), 2019.\
[ArXiv](https://arxiv.org/abs/1902.10297)

6. *Programmatically Interpretable Reinforcement Learning* {% include googleDrivePlayer.html id=page.driveId1 %}\
Abhinav Verma, [Vijayaraghavan Murali](https://research.fb.com/people/murali-vijayaraghavan/), [Rishabh Singh](https://rishabhmit.bitbucket.io), [Pushmeet Kohli](https://sites.google.com/site/pushmeet/), [Swarat Chaudhuri](https://www.cs.utexas.edu/~swarat/) \
International Conference on Machine Learning (ICML), 2018.\
[ArXiv](https://arxiv.org/abs/1804.02477) &nbsp; &nbsp;  [Video](https://goo.gl/Z2X5x6)


# Teaching

### Standalone Instructor
* Math 105: University Mathematics.\
        Introduction to logic, combinatorics, and probability. Core requirement for BS degree.

- Math 111: College Algebra.\
Foundational course in algebra, functions, and mathematical modeling. Calculus preparation course, prerequisite for higher-level math courses.

- Math 112: Elementary Functions.\
Focus on mathematical induction and trigonometric functions. Precalculus designed for math, biology, physiology, and CS majors.






### Teaching Assistant

- COMP 539: Software Engineering Methodology.\
Project based graduate course on software engineering.

- COMP 503: Reasoning About Software.\
Graduate course on formal methods and automated reasoning.

- COMP 310: Advanced Object-Oriented Programming and Design.\
Senior undergraduate course on OOP.

- Math 243: Introduction to Probability and Statistics.\
Undergraduate course on statistical reasoning.

- M01: Introduction to Mathematical Thinking.\
First course on abstract mathematics.