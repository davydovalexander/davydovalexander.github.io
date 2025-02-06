---
layout: archive
title: "Research"
permalink: /projects/
author_profile: true
---

My research interests are broadly in the stability and safety of complex engineering systems, especially those equipped with optimization- or learning-based controllers. I am interested in mathematically formalizing unifying principles within engineering design and endowing control systems with strong stability and
safety guarantees. My major thrusts can be categorized as: 1) design principles for engineering systems, 2) robust machine learning, and 3) reliable control of complex systems. I have also worked on optimal multi-robot coverage control and tracking problems for multi-robot teams.

***
# Design principles for engineering systems

Modern engineering systems are often described by complex dynamics and have intricate environmental interactions. Given these challenges, how should we design systems so they are endowed strong stability and safety guarantees? In this line of work, I have used tools from contraction theory, monotone operator theory, and convex optimization as frameworks to provide rigorous guarantees for systems. I have provided necessary and sufficient conditions for contraction and have proved novel desirable properties arising from contracting systems including (i) discretization algorithms for maintaining contraction properties, (ii) tracking error bounds for contracting dynamics following a time-varying reference, and (iii) novel feedforward control design for exact tracking guarantees.

<ul>
  <li>Non-Euclidean Contraction Theory [<a href="https://arxiv.org/abs/2103.12263">URL</a>] </li>
  <li>Non-Euclidean Monotone Operator Theory [<a href="https://arxiv.org/abs/2303.11273">URL</a>] </li>
  <li>Monotone and Positive Systems [<a href="https://arxiv.org/abs/2104.01321">URL</a>] </li>
  <li>Non-Euclidean S-Lemma [<a href="https://arxiv.org/abs/2207.14579">URL</a>] </li>
</ul>

***
# Robust machine learning

Machine learning and optimization methods are increasingly being used for safety-critical applications. Motivated by these applications, how can we ensure that methods based upon machine learning and optimization are behaving as expected? To tackle this challenge, I have studied input-output properties of classes of neural networks including recurrent neural networks (RNNs), deep equilibrium networks (DEQs), and neural ODEs. For each of these architectures, I have studied explicit estimates for the Lipschitz constant and designed novel, scalable algorithms to train them to be robust to adversarial perturbations. For optimizers, I have studied online algorithms to solve time-varying convex optimization problems and have shown how we can use contracting dynamical systems based on time-varying convex optimization to design novel optimization-based controllers for safety-critical tasks.

<ul>
  <li>Well-posedness of DEQs and Lipschitz Constants [<a href="https://arxiv.org/abs/2106.03194">URL</a>] </li>
  <li>Training of Robust DEQs [<a href="https://arxiv.org/abs/2204.00187">URL</a>] </li>
  <li>Time-Varying Convex Optimization [<a href="https://arxiv.org/abs/2305.15595">URL</a>] </li>
</ul>
    
***
# Reliable control of complex systems

In this line of research, I am to address the following question: how should we leverage data and online computation to enable more reliable control of engineering systems? For many engineering systems, classical control methods such as PID control require extensive amounts of tuning and still struggle to compensate for model mismatch and the inherent instability of some tasks. In addressing this challenge, I have designed a novel imitation learning algorithm with global stability and robustness guarantees, even away from training data. Moreover, in Summer 2024, as part of my summer internship at Toyota Research Institute, I demonstrated that a combination of a learned dynamics model together with a nonlinear MPC strategy can enable strong empirical performance in unstable drifting tasks. I am actively working on learning robust controllers from data for unstable control tasks like car drifting.

<ul>
  <li>Contractive dynamics for imitation learning [<a href="https://arxiv.org/abs/2402.08090">PDF</a>] </li>
  <li>Reliable data-driven car drifting [Under NDA]</li>
  <li>Multi-robot coverage control [<a href="https://davydovalexander.github.io/files/AD-YDM19.pdf">PDF</a>] </li>
</ul> 
    
## Research on sparsity structure and optimality of multi-robot coverage control
<iframe src="https://www.youtube.com/embed/Zpz-Co44Zyg" width="480" height="270" ></iframe>

<!-- <img src= "/images/foo-bar-identity-th.jpg" alt = "sample image"> -->

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->
