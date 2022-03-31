# Batch_contrained_RL
Data gathering can be the most limiting part of reinforcement learning. A solution for this is to collect data
on state-action pairs in exploratory setting, after which algorithms learn in an offline setting. This setup has
paved the way for standard off-policy deep reinforcement learning algorithms such as DDPG and DQN. However,
these algorithms are faced with a phenomenon known as the extrapolation error. This phenomenon can cause
significant performance deterioration in cases of proposals for state-action pairs not contained in the available data.
Hence, algorithms proposing constraining of the state-action space to the known regions are introduced. This
literature review focuses on addressing this extrapolation error and evaluates the batch-constrained algorithms
which intend to combat it. Batch-constrained Q-learning is evaluated first, after which three competing
methods (BEAR, BRAC & MORel) are introduced and evaluated. Ultimately, a comparison proposes a
qualitative ranking of these algorithms and shows all competing methods outperform their predecessor BCRL.
Further comparison between these methods shows MORel narrowly dominates, closely contending with BRAC.
