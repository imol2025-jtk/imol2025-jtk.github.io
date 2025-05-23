---
layout: page
title: Papers
subtitle: 
---



<p style='font-size: 11pt;'>
Here is the list of accepted papers. It is split into submissions of 4 pages (Full Track) and 1 page submission aimed at fostering discussion during the workshop (Tiny Papers). 
Note that this workshop venue is **not** archival. We believe these contributions will lead to interesting discussions at the workshop and recognize some of these contributions may be work in progress.
</p>

<hr>

## Full track
<hr>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Dreaming Learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Alessandro Londei, Matteo Benati, Denise Lanzieri, Vittorio Loreto
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=yR6U57TjvZ" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Incorporating novelties into deep learning systems remains a challenging problem. Introducing new information to a machine learning system can interfere with previously stored data and potentially alter the global model paradigm, especially when dealing with non-stationary sources. In such cases, traditional approaches based on validation error minimization offer limited advantages. To address this, we propose a training algorithm inspired by Stuart Kauffman’s notion of the Adjacent Possible. This novel training methodology explores new data spaces during the learning phase. It predisposes the neural network to smoothly accept and integrate data sequences with different statistical characteristics than expected. The maximum distance compatible with such inclusion depends on a specific parameter: the sampling temperature used in the explorative phase of the present method. This algorithm, called Dreaming Learning, anticipates potential paradigm shifts over time, enhancing the neural network’s responsiveness to non-stationary events that alter statistical properties. To assess the advantages of this approach, we apply this methodology to paradigm shift events in Markov chains and non-stationary textual sequences. We demonstrated its ability to improve the auto-correlation of generated textual sequences by $\sim$  29\% and enhance the velocity of loss convergence by $\sim$ 100\% in the case of a paradigm shift in Markov chains.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Quality-Diversity Self-Play: Open-Ended Strategy Innovation via Foundation Models
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Aaron Dharna, Cong Lu, Jeff Clune
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=xPWZTvdobm" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Multi-agent dynamics have powered innovation from time immemorial, such as scientific innovations during the space race or predator-prey dynamics in the natural world.
The resulting landscape of interacting agents is a continually changing, interconnected, and complex mosaic of opportunities for innovation.
Yet, training innovative and adaptive artificial agents remains challenging.
Self-Play algorithms bootstrap the complexity of their solutions by automatically generating a curriculum.
Recent work has demonstrated the power of foundation models (FMs) as intelligent and efficient search operators.
In this paper, we investigate whether combining the human-like priors and extensive knowledge embedded in FMs with multi-agent race dynamics can lead to rapid policy innovation in open-ended Self-Play algorithms.
We propose a novel algorithm, Quality-Diversity Self-Play (QDSP) that explores diverse and high-performing strategies in interacting (here, competing) populations.
We evaluate QDSP in a two-player asymmetric pursuer-evader simulation with code-based policies and show that QDSP surpasses high-performing human-designed policies.
Furthermore, QDSP discovers better policies than those from quality-only or diversity-only Self-Play algorithms.
Since QDSP explores new code-based strategies, the discovered policies come from many distinct subfields of computer science and control, including reinforcement learning, heuristic search, model predictive control, tree search, and machine learning approaches.
Combining multi-agent dynamics with the knowledge of FMs demonstrates a powerful new approach to efficiently create a Cambrian explosion of diverse, performant, and complex strategies in multi-agent settings.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  CONCLAD: COntinuous Novel CLAss Detector
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Amanda Sofie Rios, Ibrahima Jacques Ndiour, Parual Datta, Omesh Tickoo, Nilesh Ahuja
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=qfjo1ML9K3" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            In the field of continual learning, relying on so-called oracles for novelty detection is commonplace albeit unrealistic. This paper introduces CONCLAD ("COntinuous Novel CLAss Detector"), a comprehensive solution to the under-explored problem of continual novel class detection in post-deployment data. At each new task, our approach employs an iterative uncertainty estimation algorithm to differentiate between known and novel class(es) samples, and to further discriminate between the different novel classes themselves. Samples predicted to be from a novel class with high-confidence are automatically pseudo-labeled and used to update our model. Simultaneously, a tiny supervision budget is used to iteratively query ambiguous novel class predictions, which are also used during update. Evaluation across multiple datasets, ablations and experimental settings demonstrate our method's effectiveness at separating novel and old class samples continuously. We will release our code upon acceptance.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Local Ridge Regression Resets Mitigate Plasticity Loss
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Nitin Jain, Georg Martius, Marin Vlastelica
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=qVhap8tywY" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Plasticity loss refers to a neural network's diminishing ability to learn in non-stationary environments. In Reinforcement Learning (RL), existing plasticity loss mitigation methods like full network resets, Plasticity Injection, and ReDo offer partial solutions to this problem, but are limited by issues such as catastrophic performance collapse and computational inefficiency. This paper introduces Ridge Regression Reset (R3), a novel approach that maintains output stability while restoring plasticity through an optimization framework. Our experiments show that R3 effectively mitigates plasticity loss, avoids catastrophic performance collapses, and provides better sample efficiency.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  InfiniteKitchen: Cross-environment Cooperation for Zero-shot Multi-agent Coordination
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Kunal Jha, Natasha Jaques, Max Kleiman-Weiner
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=q9krBJHzVS" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Zero-shot coordination (ZSC) is an important challenge for developing adaptable AI systems that are capable of collaborating with humans in unfamiliar tasks. While prior work has mainly focused on adapting to new partners, generalizing cooperation across different environments is equally important. This paper investigates training AI agents in self-play (SP) to achieve zero-shot collaboration with novel partners in novel tasks. We introduce a new Jax-based, procedurally generated environment for multi-agent reinforcement learning, Infinite Kitchen. Our rule-based generator creates billions of solvable kitchen configurations that enable the training of a single, generalizable agent that can adapt to new levels. Our results show that exposure to diverse levels in self-play consistently improves generalization to new partners, with graph neural network (GNN) based architectures achieving the highest performance across many layouts. Our findings suggest that learning to collaborate across a multitude of unique scenarios encourages agents to develop maximally general norms, which prove highly effective for collaboration with different partners when combined with appropriate inductive biases.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Diversity Progress for Goal Selection in Discriminability-Motivated RL
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Erik M. Lintunen, Nadia M. Ady, Christian Guckelsberger
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=nz9iquQEJF" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Non-uniform goal selection has the potential to improve the reinforcement learning (RL) of skills over uniform-random selection. In this paper, we introduce a method for learning a goal-selection policy in intrinsically-motivated goal-conditioned RL: "Diversity Progress" (DP). The learner forms a curriculum based on observed improvement in discriminability over its set of goals. Our proposed method is applicable to the class of discriminability-motivated agents, where the intrinsic reward is computed as a function of the agent's certainty of following the true goal being pursued. This reward can motivate the agent to learn a set of diverse skills without extrinsic rewards. We demonstrate empirically that a DP-motivated agent can learn a set of distinguishable skills faster than previous approaches, and do so without suffering from a collapse of the goal distribution---a known issue with some prior approaches. We end with plans to take this proof-of-concept forward.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Implementing Human Information-Seeking Behaviour with Action-Agnostic Bayesian Surprise
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Emmanuel Daucé, Hamza O.K. El Hallaoui, Andrea Brovelli
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=nawwf6ooaK" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            In this paper, we aim to establish a link between model learning and the mechanism of curiosity.
The main hypothesis developed is that exploration bonuses, as proposed in the reinforcement learning literature, are linked to Bayesian estimation principles through the construction of a parametric model of the causal relationships between actions and observations. At odd with the classic action-conditional Bayesian surprise widely used in the "curiosity" literature,  action is here treated as an external variable, unknowingly of the agent's own control policy. It is thus called the "agnostic" Bayesian surprise (ABS), interpreted as an estimate of the information transfer between the observed data (including observations and motor commands) and the model parameters. 
We present here the general guidelines of this approach, and show results suggesting that action selection guided by information transfer can account for certain experimental, behavioral, and neurological data in humans.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Autotelic LLM-based exploration for goal-conditioned RL
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Guillaume Pourcel, Thomas Carta, Grgur Kovač, Pierre-Yves Oudeyer
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=n2OINaKF1e" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Autotelic agents, capable of autonomously generating and pursuing their own goals, a represent promising approach to open-ended learning and skill acquisition in reinforcement learning. Such agents learn to set and pursue their own goals. This challenge is even more difficult in open worlds that require inventing new previously unobserved goals. In this work, we propose an architecture where a single generalist autotelic agent is trained on an automatic curriculum of goals. We leverage a large language models (LLMs) to generate goals as code for reward functions based on learnability and difficulty estimates. The goal-conditioned RL agent is trained on those goals sampled based on learning progress. We compare our method to an adaptation of OMNI-EPIC to goal-conditioned RL. Our preliminary experiments imply that our method generates a higher proportion of learnable goals, suggesting better adaptation to the goal-conditioned learner.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  A Multi-agent Reinforcement Learning Study of Evolution of Communication and Teaching under Libertarian and Utilitarian Governing Systems
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Aslan Satary Dizaji
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=mTdxjUoA1n" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Laboratory experiments have shown that communication plays an important role in solving social dilemmas. Here, by extending the AI-Economist, a mixed motive multi-agent reinforcement learning environment, we intend to find an answer to the following descriptive question: which governing system does facilitate the emergence and evolution of communication and teaching among agents? To answer this question, the AI-Economist is extended by a voting mechanism to simulate three different governing systems across individualistic-collectivistic axis, from Full-Libertarian to Full-Utilitarian governing systems. In the original framework of the AI-Economist, agents are able to build houses individually by collecting material resources from their environment. Here, the AI-Economist is further extended to include communication with possible misalignment - a variant of signalling game - by letting agents to build houses together if they are able to name mutually complement material resources by the same letter. Moreover, another extension is made to the AI-Economist to include teaching with possible misalignment - again a variant of signalling game - by letting half the agents as teachers who know how to use mutually complement material resources to build houses but are not capable of building actual houses, and the other half as students who do not have this information but are able to actually build those houses if teachers teach them. The result shows that collectivistic environment such as Full-Utilitarian system is more favourable for the emergence of communication and teaching, or more precisely, evolution of language alignment. Finally, a discussion is provided to justify this result in the simulation environment of this paper.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  SAC-GLAM: Improving Online RL for LLM agents with Soft Actor-Critic and Hindsight Relabeling
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Loris Gaven, Thomas Carta, Clément ROMAC, Olivier Sigaud, sylvain lamprier, Pierre-Yves Oudeyer
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=lP1UWqBYhs" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            The past years have seen Large Language Models (LLMs) strive not only as generative models but also as agents solving textual sequential decision-making tasks. When facing complex environments where their zero-shot abilities are insufficient, recent work showed online Reinforcement Learning (RL) could be used for the LLM agent to discover and learn efficient strategies interactively. However, most prior work sticks to on-policy algorithms, which greatly reduces the scope of methods such agents could use for both exploration and exploitation, such as experience replay and hindsight relabeling. Yet, such methods may be key for LLM learning agents, and in particular when designing autonomous intrinsically motivated agents sampling and pursuing their own goals (i.e. autotelic agents). This paper presents and studies an adaptation of Soft Actor-Critic and hindsight relabeling to LLM agents. Our method not only paves the path towards autotelic LLM agents that learn online but can also outperform on-policy methods in more classic multi-goal RL environments.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Episodic Novelty Through Temporal Distance
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Yuhua Jiang, Qihan Liu, Yiqin Yang, Xiaoteng Ma, Dianyu Zhong, Bo XU, Jun Yang, Bin Liang, Chongjie Zhang, Qianchuan Zhao
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=j34tTSHLDy" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Exploration in sparse reward environments remains a significant challenge in reinforcement learning, particularly in Contextual Markov Decision Processes (CMDPs), where environments differ across episodes. Existing episodic intrinsic motivation methods for CMDPs primarily rely on count-based approaches, which are ineffective in large state spaces, or on similarity-based methods that lack appropriate metrics for state comparison. To address these shortcomings, we propose Episodic Novelty Through Temporal Distance (ETD), a novel approach that introduces temporal distance as a robust metric for state similarity and intrinsic reward computation. By employing contrastive learning, ETD accurately estimates temporal distances and derives intrinsic rewards based on the novelty of states within the current episode. Experiments on challenging MiniGrid tasks demonstrate that ETD significantly outperforms state-of-the-art methods, highlighting its effectiveness in enhancing exploration and generalization in sparse reward CMDPs.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Knowledge Retention in Continual Model-Based Reinforcement Learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Haotian Fu, Yixiang Sun, Michael Littman, George Konidaris
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=j1hgRWmsu6" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            We propose DRAGO, a novel approach for continual model-based reinforcement learning aimed at improving the incremental development of world models across a sequence of tasks that differ in their reward functions but not the state space or dynamics. DRAGO comprises two key components: $\textit{Synthetic Experience Rehearsal}$, which leverages generative models to create synthetic experiences from past tasks, allowing the agent to reinforce previously learned dynamics without storing data, and $\textit{Regaining Memories Through Exploration}$, which introduces an intrinsic reward mechanism to guide the agent toward revisiting relevant states from prior tasks. Together, these components enable the agent to maintain a comprehensive and continually developing world model, facilitating more effective learning and adaptation across diverse environments. Empirical evaluations demonstrate that DRAGO is able to preserve knowledge across tasks, achieving superior performance in various continual learning scenarios.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Can a MISL Fly? Analysis and Ingredients for Mutual Information Skill Learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Chongyi Zheng, Jens Tuyls, Joanne Peng, Benjamin Eysenbach
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=ixCeDph6Bd" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Self-supervised learning has the potential of lifting several of the key challenges in reinforcement learning today, such as exploration, representation learning, and reward design. Recent work (METRA) has effectively argued that moving away from mutual information and instead optimizing a certain Wasserstein distance is important for good performance. In this paper, we argue that the benefits seen in that paper can largely be explained within the existing framework of mutual information skill learning (MISL). Our analysis suggests a new MISL method (contrastive successor features) that retains the excellent performance of METRA with fewer moving parts, and highlights connections between skill learning, contrastive representation learning, and successor features. Finally, through careful ablation studies, we provide further insight into some of the key ingredients for both our method and METRA.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Empathic Coupling of Homeostatic States for Intrinsic Prosociality
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Naoto Yoshida, Kingson Man
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=efXcvMnqEl" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            When regarding the suffering of others, we often experience personal distress and feel compelled to help. Inspired by living systems, we investigate the emergence of prosocial behavior among autonomous agents that are motivated by homeostatic self-regulation. We perform multi-agent reinforcement learning, treating each agent as a vulnerable homeostat charged with maintaining its own well-being. We introduce an empathy-like mechanism to share homeostatic states between agents: an agent can either observe their partner’s internal state (cognitive empathy) or the agent’s internal state can be directly coupled to that of their partner’s (affective empathy). In three simple multi-agent environments, we show that prosocial behavior arises only under homeostatic coupling – when the distress of a partner can affect one’s own well-being. Our findings specify the type and role of empathy in artificial agents capable of prosocial behavior.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Safe Multi-Agent Navigation guided by Goal-Conditioned Safe Reinforcement Learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Meng Feng, Viraj Parimi, Brian C. Williams
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=c3wBh3IByv" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Safe navigation is essential for autonomous systems operating in hazardous environments. Traditional planning methods are effective for solving long-horizon tasks but depend on the availability of a graph representation with predefined distance metrics. In contrast, safe Reinforcement Learning (RL) is capable of learning complex behaviors without relying on manual heuristics but fails to solve long-horizon tasks, particularly in goal-conditioned and multi-agent scenarios.

In this paper, we introduce a novel method that integrates the strengths of both planning and safe RL. Our method leverages goal-conditioned RL and safe RL to learn a goal-conditioned policy for navigation while concurrently estimating cumulative distance and safety levels using learned value functions via an automated self-training algorithm. By constructing a graph with states from the replay buffer, our method prunes unsafe edges and generates a waypoint-based plan that the agent then executes by following those waypoints sequentially until their goal locations are reached. This graph pruning and planning approach via the learned value functions allows our approach to flexibly balance the trade-off between faster and safer routes especially over extended horizons.

Utilizing this unified high-level graph and a shared low-level goal-conditioned safe RL policy, we extend this approach to address the multi-agent safe navigation problem. In particular, we leverage Conflict-Based Search (CBS) to create waypoint-based plans for multiple agents allowing for their safe navigation over extended horizons. This integration enhances the scalability of goal-conditioned safe RL in multi-agent scenarios, enabling efficient coordination among agents. Extensive benchmarking against state-of-the-art baselines demonstrates the effectiveness of our method in achieving distance goals safely for multiple agents in complex and hazardous environments.
</p>
</div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  A role for phasic serotonergic signaling in regulating augmentations during open-ended learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Caroline Haimerl, Daniel C McNamee
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=bciFaq9EKp" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Humans and animals need to rapidly adapt to dynamically changing environments given only few experiences while high-performance artificial systems require large datasets. In order to bridge this gap, we consider data augmentations, which have been shown to substantially improve the data-efficiency and generalization capabilities of many machine learning models including reinforcement learning agents. However, how augmentation should be coordinated online during open-ended interactions with the world is unclear. We take inspiration from the brain in addressing this issue. Encountering unexpected environment states (signaled by state prediction errors, SPEs) has been associated with the phasic release of serotonin, a neurotransmitter known to mediate cognitive flexibility in humans. We hypothesize that serotonin triggers augmentations and that this facilitates adaptation to novel environments. In our agent-based simulations, learning from augmentations improves state-prediction in unfamiliar contexts within a minimal circular environment and in gridworlds. Furthermore, we find that augmentations timed to high SPEs are particularly effective. These preliminary results are consistent with a functional role for serotonergic neuromodulation in open-ended adaptation of natural and artificial systems based on regulating the augmentation of experience.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  First-Explore, then Exploit: Meta-Learning to Solve Hard Exploration-Exploitation Trade-Offs
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Ben Norman, Jeff Clune
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=YauxlQOlQa" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Standard reinforcement learning (RL) agents never intelligently explore like a human (i.e. taking into account complex domain priors and adapting quickly to previous explorations). Across episodes, RL agents struggle to perform even simple exploration strategies, for example, systematic search that avoids exploring the same location multiple times. Meta-RL is a potential solution, as unlike standard-RL, meta-RL can *learn* to explore. We identify a new challenge with meta-RL that aims to maximize the cumulative reward of an episode sequence (cumulative-reward meta-RL). When the optimal behavior is to sacrifice reward in early episodes for better exploration (and thus enable higher later-episode rewards), existing cumulative-reward meta-RL methods become stuck on the local optima of failing to explore.
We introduce a new method, First-Explore, which overcomes this limitation by learning two policies: one to solely explore, and one to solely exploit. When exploring and thus forgoing early-episode reward is required, First-Explore significantly outperforms existing cumulative meta-RL methods. By identifying and solving the previously unrecognized problem of forgoing reward in early episodes, First-Explore represents a significant step towards developing meta-RL algorithms capable of more human-like exploration on a broader range of domains. In complex or open-ended environments, this approach could allow the agent to develop sophisticated exploration heuristics that mimic intrinsic motivations (e.g., prioritizing seeking novel observations).
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Representing Positional Information in Generative World Models for Object Manipulation
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Stefano Ferraro, Pietro Mazzaglia, Tim Verbelen, Bart Dhoedt, Sai Rajeswar
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=YFT0vje0Fl" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            The ability to predict outcomes of interactions between embodied agents and objects is paramount in the robotic setting. While model-based control methods have started to be employed for tackling manipulation tasks, they have faced challenges in accurately manipulating objects. As we analyze the causes of this limitation, we identify the cause of underperformance in the way current world models represent crucial positional information, especially about the target's goal specification for object positioning tasks. 
We propose two solutions for generative world models: position-conditioned (PCP) and latent-conditioned (LCP) policy learning. In particular, LCP employs object-centric latent representations that explicitly capture object positional information for goal specification. This naturally leads to the emergence of multimodal capabilities.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Fostering Intrinsic Motivation in Reinforcement Learning with Pretrained Foundation Models
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Alain Andres, Javier Del Ser
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=XWxTiTFDxE" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Exploration remains a significant challenge in reinforcement learning, especially in environments where extrinsic rewards are sparse or non-existent. The recent rise of foundation models, such as CLIP, offers an opportunity to leverage pretrained, semantically rich embeddings that encapsulate broad and reusable knowledge. In this work we explore the potential of these foundation models not just to drive exploration, but also to analyze the critical role of the episodic novelty term in enhancing exploration effectiveness of the agent. We also investigate whether providing the intrinsic module with complete state information -- rather than just partial observations -- can improve exploration,
despite the difficulties in handling small variations within large state spaces. Our experiments in the MiniGrid domain reveal that intrinsic modules can effectively utilize full state information, significantly increasing sample efficiency while learning an optimal policy. Moreover, we show that the embeddings provided by foundation models are sometimes even better than those constructed by the agent during training, further accelerating the learning process, especially when coupled with the episodic novelty term to enhance exploration.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  A meta unit for co-constructing a computational scaffold model to guide human motor learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Alexandra Moringen, Sascha Fleer, Kristina Yordanova
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=Tx6nIfIkLH" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Learning of e.g. a dexterous motor skill, which is common in medical training,
sports, or playing a musical instrument, is time-costly and needs supervision from a
teacher, to avoid injury and to progress. Importantly, learning a motor skill requires
active practice, and adjusting one’s own individual embodiment to perform the
target movement. We introduce a meta unit for co-constructing a computational
scaffold for learning. It targets to optimize the learning process of a student, as
well as the intervention of their teacher. This approach aims to enable the student
to discover their own optimal learning policy while being guided by the teacher on
demand, with the ultimate goal of improving beyond the capacity of the teacher.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Playful and Exploratory Behavior from the Maximum Occupancy Principle
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Chiara Mastrogiuseppe, Rubén Moreno-Bote
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=SzeK0ZVkgE" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            We build on the Maximum Occupancy Principle (MOP) and show complex and playful behavior emerging from intrinsic motivation to occupy action space. Relevantly, the drive to occupy action space as uniformly as possible in the long run, while avoiding terminal states, leads to interesting behaviors, such as non-trivial interaction with external objects. We show that MOP agents in navigation tasks are inherently curious, as they are attracted by the possibility of playing with available objects or using them as tools to visit larger regions of space. This principle is then extended to neural activity (NeuroMOP). We introduce a more complex continuous navigation problem where the motor output of the agent is defined by two units of a recurrent neural network of fixed weights. We show that a MOP controller can drive the network's activity and lead the motor output units to occupy the whole available space. This example highlights the potential of MOP as a principle not only for behavior but also for neural activity.
All together, these results indicate MOP as a possible principle underlying various aspects of natural behavior, reconciling multiple perspectives of intrinsic motivation, such as curiosity and exploration.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Bayesian Online Non-Stationary Detection for Robust Reinforcement Learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Alexander Shmakov, Pankaj Rajak, Yuhao Feng, Wojciech Kowalinski, Fei Wang
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=SYlfJ52pWr" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Reinforcement Learning (RL) has achieved state-of-the-art performance in stationary environments with effective simulators. However, lifelong and open-world RL applications, such as robotics, stock trading, and recommendation systems, change over time in adversarial ways. Non-stationary environments pose challenges for RL agents due to constant distribution shifts from the training data, leading to deteriorating performance. We propose using a robust Bayesian online detector, which tracks agent performance to detect non-stationarities in the environment. Additionally, we propose a new metric called hindsight approximate reward (HAR) that solely relies on state and action information to detect adversarial changes in the environment, making it well-suited for real-world settings with missing or delayed feedback. We demonstrate that the proposed Bayesian detector, combined with HAR or expected reward as a metric, can detect a range of non-stationary changes in dynamic control tasks more effectively compared to baseline non-stationary tests.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  The Creative Act: Effective Exploration by Seeking Surprise
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Julia Minarik
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=RbpDC5sOJi" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            That \textit{c} creates \textit{p} is a generative relation, resulting from exploration, between a creator \textit{c} and a possible generative action \textit{p} where \textit{c} generates by exploring then recognizing and revealing the possible action \textit{p} that is surprising, and that we can learn something about the space of possible actions from. This focus on creativity as action allows me to emphasize it's relational nature, rather than trying to separately define what a creative product is or what the creative mental process is independently.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Enhanced Exploration via Variational Learned Priors
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Jessica Nicholson, Joseph S Goodier, Akshil Patel, Özgür Şimşek
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=R395UgreTH" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Efficient exploration in reinforcement learning is challenging, especially in sparse-reward environments. Intrinsic motivation, such as rewarding state novelty, can enhance exploration. We propose an intrinsic motivation approach, called Variational Learned Priors, that uses variational state encoding to estimate novelty via the Kullback-Leibler divergence between the posterior distribution and a learned prior of a Variational Autoencoder. We assess this intrinsic reward with four different learned priors. Our results show that this method improves exploration efficiency and accelerates extrinsic reward accumulation across various domains.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  PreND: Enhancing Intrinsic Motivation in Reinforcement Learning through Pre-trained Network Distillation
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Amin Davoodabadi, Negin Hashemi Dijujin, Mahdieh Soleymani Baghshah
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=NDjJ2MB97U" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Intrinsic motivation, inspired by the psychology of developmental learning in infants, stimulates exploration in agents without relying solely on sparse external rewards. Existing methods in reinforcement learning like Random Network Distillation (RND) face significant limitations, including (1) relying on raw visual inputs, leading to a lack of meaningful representations, (2) the inability to build a robust latent space, (3) poor target network initialization and (4) rapid degradation of intrinsic rewards. In this paper, we introduce ***Pre**-trained **N**etwork **D**istillation* (**PreND**), a novel approach to enhance intrinsic motivation in reinforcement learning (RL) by improving upon the widely used prediction-based method, RND. **PreND** addresses these challenges by incorporating pre-trained representation models into both the target and predictor networks, resulting in more meaningful and stable intrinsic rewards, while enhancing the representation learned by the model. We also tried simple but effective variants of the predictor network optimization by controlling the learning rate.
Through experiments on the Atari domain, we demonstrate that **PreND** significantly outperforms RND, offering a more robust intrinsic motivation signal that leads to better exploration, improving overall performance and sample efficiency. This research highlights the importance of target and predictor networks representation in prediction-based intrinsic motivation, setting a new direction for improving RL agents' learning efficiency in sparse reward environments.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Incentivizing Exploration With Causal Curiosity as Intrinsic Motivation
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Elias AOUN DURAND, Mehdi Khamassi
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=LZI8EFLoFD" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Reinforcement learning (RL) has demonstrated remarkable success in decision-making tasks, yet often lacks the ability to decipher and leverage causal relationships in complex environments. This paper introduces a novel ``causal model-based reinforcement learning agent'' that integrates causal inference with model-based RL to enhance exploration and decision-making. Our approach incorporates an intrinsic motivation mechanism based on causal curiosity, quantified by the changes in the agent's internal causal model. We present an algorithm that maintains separate value functions for extrinsic rewards and intrinsic causal discovery, allowing for a balanced exploration of both task-oriented goals and causal structures. Theoretical analysis suggests convergence properties under certain conditions, while empirical results on a blackjack task and structural causal model environments demonstrate improved learning efficiency and strategic decision-making compared to standard RL. This work contributes to bridging the gap between reinforcement learning and causal inference.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Skill Disentanglement in Reproducing Kernel Hilbert Space
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Vedant Dave, Elmar Rueckert
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=KXLTpALvJh" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Unsupervised Skill Discovery aims to learn diverse skills without extrinsic rewards, using them as priors for downstream tasks. Existing methods focus on empowerment or entropy maximization but often result in static or non-discriminable skills. Instead, our method, Hilbert Unsupervised Skill Discovery (HUSD), combines $f$-divergence with Integral Probability Metrics to promote behavioral diversity and disentanglement. HUSD maximizes the Maximum Mean Discrepancy between the joint distribution of skills and states and their marginals in Reproducing Kernel Hilbert Space, leading to better exploration and skill separability. Our results on Unsupervised RL Benchmarks show HUSD outperforms previous exploration algorithms on state-based tasks.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  A Single Goal is All You Need
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Grace Liu, Michael Tang, Benjamin Eysenbach
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=KTt7pJq2up" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            In this paper, we present empirical evidence of skills and directed exploration emerging from a simple RL algorithm long before any successful trials are observed. For example, in a manipulation task, the agent is given a single observation of the goal state and learns skills, first moving its end-effector, then pushing the block, and finally lifting and placing the block. These skills emerge before the agent has ever successfully placed the block at the goal location and without the aid of any reward functions, demonstrations, or manually-specified distance metrics. Implementing our method involves a simple modification of prior work and does not require density estimates, ensembles, or any additional hyperparameters. We lack a clear theoretical understanding of why the method works so effectively, though our experiments provide some hints.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  OMNI-EPIC: Open-endedness via Models of human Notions of Interestingness with Environments Programmed in Code
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Maxence Faldor, Jenny Zhang, Antoine Cully, Jeff Clune
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=IWEMnQ2mOB" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Open-ended and AI-generating algorithms aim to continuously generate and solve increasingly complex tasks indefinitely, offering a promising path toward more general intelligence. To accomplish this grand vision, learning must occur within a vast array of potential tasks. Existing approaches to automatically generating environments are constrained within manually predefined, often narrow distributions of environment, limiting their ability to create any learning environment. To address this limitation, we introduce a novel framework, OMNI-EPIC, that augments previous work in Open-endedness via Models of human Notions of Interestingness (OMNI) with Environments Programmed in Code (EPIC). OMNI-EPIC leverages foundation models to autonomously generate code specifying the next learnable (i.e., not too easy or difficult for the agent’s current skill set) and interesting (e.g., worthwhile and novel) tasks. OMNI-EPIC generates both environments (e.g., an obstacle course) and reward functions (e.g., progress through the obstacle course quickly without touching red objects), enabling it, in principle, to create any simulatable learning task. We showcase the explosive creativity of OMNI-EPIC, which continuously innovates to suggest new, interesting learning challenges. We also highlight how OMNI-EPIC can adapt to reinforcement learning agents’ learning progress, generating tasks that are of suitable difficulty. Overall, OMNI-EPIC can endlessly create learnable and interesting environments, further propelling the development of self-improving AI systems and AI-Generating Algorithms.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Bridging Natural Language and Emergent Representation in Hierarchical Reinforcement Learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Zihe Ji, Sao Mai Nguyen, Mehdi Zadem
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=HMJJ10SAFy" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Hierarchical Reinforcement Learning (HRL) breaks down complex tasks into manageable subtasks, but faces challenges with efficiency and generalization in high-dimensional, open-ended environments. Human In The Loop approaches offer a potential solution to these limitations. In this work, we propose the integration of large language models (LLMs) with HRL, leveraging LLMs' natural language and reasoning capabilities and study how to bridge the gap between human instructions and HRL's learned abstract representations. By translating human demonstrations into actionable reinforcement learning signals, LLMs can improve task abstraction and planning within HRL. Our approach builds upon the Spatial-Temporal Abstraction via Reachability (STAR) algorithm, using a LLM to optimize the hierarchical planning process. Empirical results obtained on continuous control tasks illustrate the potential of LLMs to enhance HRL particularly in environments requiring spatial reasoning and hierarchical control.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Modeling Goal Selection with Program Synthesis
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> J. Branson Byers, Bonan Zhao, Yael Niv
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=DfFE7hfnEb" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            People can autonomously select and achieve novel goals to shape their own learning.
But goal selection can involve selecting goals from large spaces, where repeated
planning becomes computationally intractable. We propose program induction
as an inductive bias for defining human-like priors to make goal selection easier.
We demonstrate this tractable, semi-autonomous method for goal selection on a
novel ShapeWorld task using a handcrafted grammar that maps states to reward
functions.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  We Urgently Need Intrinsically Kind Machines
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Joshua Tomas Sealth Hewson
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=DHWceMYbz0" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Artificial Intelligence systems are rapidly evolving, integrating extrinsic and intrinsic motivations. While these frameworks offer benefits, they risk misalignment at the algorithmic level while appearing superficially aligned with human values. In this paper, we argue that an intrinsic motivation for kindness is crucial for making sure these models are intrinsically aligned with human values. We argue that kindness, defined as the motivation to maximize the reward of others, can counteract any intrinsic motivations that might lead the model to prioritize itself over human well-being. Our approach introduces a framework and algorithm for embedding kindness into foundation models by simulating conversations. Limitations and future research directions for scalable implementation are discussed.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  From Laws to Motivation: Guiding Exploration through Law-Based Reasoning and Rewards
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Ziyu Chen, Zhiqing Xiao, Xinbei Jiang, Junbo Zhao
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=8pq9QH3eRx" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Large Language Models (LLMs) and Reinforcement Learning (RL) are two powerful approaches for building autonomous agents. However, due to limited understanding of the game environment, agents often resort to inefficient exploration and trial-and-error, struggling to develop long-term strategies or make decisions. We propose a method that extracts experience from interaction records to model the underlying laws of the game environment, using these experience as internal motivation to guide agents. These experience, expressed in language, are highly flexible and can either assist agents in reasoning directly or be transformed into rewards for guiding training. Our evaluation results in $\texttt{Crafter}$ demonstrate that both RL and LLM agents benefit from these experience, leading to improved overall performance.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Modeling Cognitive Strategies in Teaching
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Sevan K Harootonian, Yael Niv, Thomas L. Griffiths, Mark K Ho
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=7bbQ7Nrddr" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Teaching is a complex social behavior that sometimes results from goal-directed processing. However, goal-directed teaching is cognitively demanding since it requires actively assessing and correcting gaps in a learner's knowledge. When do people teach using such mentally effortful strategies versus falling back on more cognitively frugal ones? Here, we investigated this question using a combination of novel behavioral experiments and computational theory. We found robust individual differences in people's teaching strategies: some participants spontaneously teach using high-effort processing (e.g., Bayesian theory of mind and model-based planning) while others engage in low-effort processing (e.g., model-free heuristics). Our results and analyses provide a novel demonstration of how people engage in planning versus heuristics when teaching, as well as how people adapt processing to avoid mental effort in social interactions.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Using adaptive intrinsic motivation in RL to model learning across development
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Kai Jappe Sandbrink, Brian Christian, Linas Nasvytis, Christian Schroeder de Witt, Patrick Butlin
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=74kGs82M19" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Reinforcement learning is a powerful model of animal learning in brief, controlled experimental conditions, but does not readily explain the development of behavior over an animal's whole lifetime.  In this paper, we describe a framework to address this shortcoming by introducing the single-life reinforcement learning setting to cognitive science. We construct an agent with two learning systems: an extrinsic learner that learns within a single lifetime, and an intrinsic learner that learns across lifetimes, equipping the agent with intrinsic motivation. We show that this model outperforms heuristic benchmarks and recapitulates a transition from exploratory to habit-driven behavior, while allowing the agent to learn an interpretable value function. We formulate a precise definition of intrinsic motivation and discuss the philosophical implications of using reinforcement learning as a model of behavior in the real world.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  SENSEI: Semantic Exploration Guided by Foundation Models to Learn Versatile World Models
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Cansu Sancaktar, Christian Gumbsch, Andrii Zadaianchuk, Pavel Kolev, Georg Martius
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=5RbPZLNazK" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Exploring useful behavior is a keystone of reinforcement learning (RL). Existing approaches to intrinsic motivation, following general principles such as information gain, mostly uncover low-level interactions. In contrast, children’s play suggests that they engage in semantically meaningful high-level behavior by imitating or interacting with their caregivers. Recent work has focused on using foundation models to inject these semantic biases into exploration. However, these methods often rely on unrealistic assumptions, such as environments already embedded in language or access to high-level actions. To bridge this gap, we propose SEmaNtically Sensible ExploratIon (Sensei), a framework to equip model-based RL agents with intrinsic motivation for semantically meaningful behavior. To do so, we distill an intrinsic reward signal of interestingness from Vision Language Model (VLM) annotations. The agent learns to predict and maximize these intrinsic rewards using a world model learned directly from intrinsic rewards, image observations, and low-level actions. We show that in both robotic and video game-like simulations Sensei manages to discover a variety of meaningful behaviors. We believe Sensei provides a general tool for integrating feedback from foundation models into autonomous agents, a crucial research direction as openly available VLMs become more powerful.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Prioritizing Compression Explains Human Perceptual Preferences
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Francisco M. Lopez, Bertram E. Shi, Jochen Triesch
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=3mLfmGidUv" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            We present prioritized representation learning (PRL), a method to enhance unsupervised representation learning by drawing inspiration from active learning and intrinsic motivations. PRL re-weights training samples based on an intrinsic priority function embodying preferences for certain inputs. We show how common human perceptual biases across different sensory modalities emerge through a priority function promoting compression and demonstrate the effects of biased early exposure on individual preferences. Our results reveal that PRL can mimic the results of active unsupervised learning even in the absence of active control over the input.
          </p>
       </div>
  </div>
</div>



## Tiny paper track
<hr>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Unlocking New Strategies: Intrinsic Exploration for Evolving Macro and Micro Actions
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Sourav Panda, Aviral Srivastava, Jonathan Dodge
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=yfAB7nWiFV" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            We propose combining intrinsic exploration with extrinsic motivations to inspire RL agents to develop strategies at both macro and micro levels, enhancing adaptability.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Self-Efficacy Update in Reinforcement Learning: Impact on Goal Selection for Q-learning Agents
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Jing Li, Angela Radulescu
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=oG4pgsoxNW" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            We introduce a dynamic self-efficacy learning rule and examine its impact on multi-goal selection in a grid-world. We model the Q-learning agent's self-efficacy as the integral of reward prediction errors (RPEs), allowing it to modulate the agent's expectation of achieving the best possible future outcome. Initial simulation results suggest that faster self-efficacy updates lead to higher overall reward accumulation, but with increased variability in reaching the optimal goal. These findings indicate that an optimal self-efficacy update rate, which can be learned through experience, may strike a balance between maximizing performance and maintaining stability.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Does Infantile Attachment Require Intrinsic Reward?
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Xi Jia Zhou, Logan Cross, Wanqiao Xu, Nick Haber
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=d9oY924MCJ" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Infant attachment behaviors, essential for cognitive and social development, are debated in terms of their origins—whether they arise from intrinsic drives or external reinforcement. This study uses a reinforcement learning (RL) framework to examine if infant attachment behaviors can be replicated in a simulated 1D grid world environment. Two groups of simulated infants were modeled: one with intrinsic rewards for staying close to a caregiver, and another relying solely on extrinsic rewards from both the caregiver and the environment. Preliminary results show that external reinforcement can generate infant-like attachment behaviors, though adding intrinsic attachment rewards made some overall infant behaviors more realistic while distorting subgroup patterns. These findings highlight the complex interaction between intrinsic and extrinsic factors in shaping attachment behaviors, suggesting more work is required to understand how they combine to reflect real-world patterns.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  The Agent-Environment Boundary
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Dhawal Gupta
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=cvKDeWRljj" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            This paper examines the agent-environment boundary in reinforcement learning (RL) from a new perspective. We suggest that the traditional distinction between actions and observations can evolve as the agent's control and understanding of its environment grow.  We illustrate these concepts with simple examples, showing how shifting boundaries allow us to define the notion of building knowledge and an interplay between RL and planning.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Empowerment and Causal Learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Annya Dahmani, Aly Lidayan, Alison Gopnik
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=clpsK2u5UN" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            In this work, we are interested in bridging causal learning in humans and reinforcement learning (RL) in agents. Earlier work in cognitive science on causal learning has found that both adults and children are strongly motivated to discover causal structure in their environment.  Meanwhile, research in RL has focused on learning to maximize rewards without explicitly attempting to discover causal structure. We hypothesize that the concept of “empowerment” in reinforcement learning can provide a bridge between reinforcement learning and causal learning. “Empowerment” is an intrinsic reward that involves maximizing the mutual information between an agent’s actions and outcomes in the world, and so maximizing the agent’s ability to control the environment, rather than maximizing particular external rewards. This ability to control the environment is also at the heart of “interventionist” accounts of causality and causal learning (e.g. Woodward, 2005; Pearl 2000, 2009). From the machine learning perspective Empowerment may thus be an especially  promising intrinsic motivation for RL agents to discover causal structure. From the cognitive science perspective we will explore whether human causal learning can be explained by a drive to maximize empowerment, compared to other forms of novelty-seeking drives.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Testing causal hypotheses through Hierarchical Reinforcement Learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Anthony GX-Chen, Dongyan Lin, Mandana Samiei
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=ZqNcJ8uuHT" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            A goal of AI research is to develop agentic systems capable of operating in open-ended environments with the autonomy and adaptability akin to a scientist in the world of research---generating hypothesis, empirically testing them, and drawing conclusions about how the world works. We propose Structural Causal Models (SCMs) as a formalization of the space of hypothesis, and hierarchical reinforcement learning (HRL) as a key ingredient to building agents that can systematically discover the correct SCM. This provides a framework towards constructing agent behavior that generates and tests hypothesis to enables transferable learning of the world. Finally, we discuss practical implementation strategies.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Model-Agnostic Meta-Learning with Open-Ended Reinforcement Learning
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Aya Shabbar
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=WJ6fSc4e9z" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            This paper is an in-progress research that builds on the Open-Ended Reinforcement Learning with Neural Reward Functions proposed by Meier and Mujika [1] which use reward functions encoded by neural networks. One key limitation of their paper is the necessity of re-learning for each new skill learned by the agent. Consequently, we propose integrating meta-learning algorithms to tackle this problem. We, therefore, study the use of MAML, Model-Agnostic Meta Learning that we believe could make policy learning more efficient. MAML operates by learning an initialization of the model parameters that can be fine-tuned with a small number of examples from a new task which allows for rapid adaptation to new tasks.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Emergence of Implicit World Models from Mortal Agents
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Kazuya Horibe, Naoto Yoshida
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=PMIB7D4ddy" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            In this paper, we discuss the possibility of world models and active exploration as emergent properties of open-ended behavior optimization in autonomous agents. In discussing the source of the open-endedness of living things, we start from the perspective of biological systems as understood by the mechanistic approach of theoretical biology and artificial life. From this perspective, we discuss the potential of homeostasis in particular as an open-ended objective for autonomous agents and as a general, integrative extrinsic motivation. We then discuss the possibility of implicitly acquiring a world model and active exploration through the internal dynamics of a network, and a hypothetical architecture for this, by combining meta-reinforcement learning, which assumes domain adaptation as a system that achieves robust homeostasis. The main points of our discussion are represented in the diagram in Figure1.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Hierarchical Orchestra of Policies
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Thomas P Cannon, Özgür Şimşek
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=Oc0x7csK0c" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            Continual reinforcement learning poses a major challenge due to the tendency of agents to experience catastrophic forgetting when learning sequential tasks. In this paper, we introduce a modularity-based approach, called Hierarchical Orchestra of Policies (HOP), designed to mitigate catastrophic forgetting in lifelong reinforcement learning. HOP dynamically forms a hierarchy of policies based on a similarity metric between the current observations and previously encountered observations in successful tasks. Unlike other state-of-the-art methods, HOP does not require task labelling, allowing for robust adaptation in environments where boundaries between tasks are ambiguous. Our experiments, conducted across multiple tasks in a procedurally generated suite of environments, demonstrate that HOP significantly outperforms baseline methods in retaining knowledge across tasks and performs comparably to state-of-the-art transfer methods that require task labelling. Moreover, HOP achieves this without compromising performance when tasks remain constant, highlighting its versatility.
          </p>
       </div>
  </div>
</div>

 <div class="card mb-3">
  <div class="card-header font-weight-bold">
  Toward Universal and Interpretable World Models for Open-ended Learning Agents
  </div>
  <div class="card-body">
    <div class="card-text">
        <div class="row">
           <div class="col-9">
              <b>Authors:</b> Lancelot Da Costa
           </div>
           <div class="col-3">
              <div class="right">
                 <a class="btn btn-primary" href="https://openreview.net/forum?id=BeTc2iBxCD" target="_blank" role="button">Paper Link</a>
             </div>
           </div>
        </div>
    </div>
      <button type="button" class="collapsible">Abstract</button>
       <div class="content">
          <p style='margin-top: 5pt;'>
            We introduce a generic, compositional and interpretable class of generative world models that supports open-ended learning agents. This is a sparse class of Bayesian networks capable of approximating a broad range of stochastic processes, which provide agents with the ability to learn world models in a manner that may be both interpretable and computationally scalable. This approach integrating Bayesian structure learning and intrinsically motivated (model-based) planning enables agents to actively develop and refine their world models, which may lead to developmental learning and more robust, adaptive behavior.
          </p>
       </div>
  </div>
</div>

