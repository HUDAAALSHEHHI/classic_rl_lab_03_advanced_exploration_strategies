🧠 Comprehensive Experiment Description
This experiment demonstrates how intrinsic curiosity can be integrated into reinforcement learning agents to enhance exploration beyond traditional random strategies. The model learns by combining external rewards from the environment with internal rewards generated from prediction errors. Through this process, the agent not only optimizes its performance but also learns to seek out novel experiences that reduce uncertainty, mimicking human curiosity-driven behavior.

✏️ Objective
The goal of this experiment is to implement a curiosity-driven reinforcement learning agent in the CartPole environment, showing how the inclusion of internal motivation improves exploration efficiency and stability. The agent uses a dual-network structure:

A Policy Network that decides actions based on current states.

A Curiosity Model that predicts next states and computes intrinsic rewards based on prediction error.
The balance between intrinsic and extrinsic rewards enables more robust and self-sustaining learning.

📘 Results
The agent demonstrated a consistent improvement in performance, showing faster adaptation and increased stability compared to traditional ε-greedy strategies. Over time, the curiosity-driven reward encouraged exploration of states that the agent had not yet mastered, leading to more diverse experiences and generalizable learning outcomes. The training curve revealed smooth convergence with reduced variance, proving the efficiency of integrating curiosity into the learning process.

📒 Observations

Curiosity rewards can significantly enhance the agent’s motivation to explore, particularly in sparse-reward environments.

The intrinsic reward signal provides a continuous learning stimulus, preventing early stagnation.

A careful balance between external reward scaling and intrinsic curiosity coefficient is critical to maintain stability.

This approach mirrors cognitive models of human learning, where surprise and novelty serve as key drivers of adaptation and creativity.

True intelligence is not fueled by reward alone it thrives on the enduring desire to uncover the unknown.
