# AI Project: Image Segmentation and Reinforcement Learning

This repository contains the code for a two-phase AI project.

## Phase 1: Image Segmentation with UNet Architectures

In this phase, we tackle the problem of road segmentation in satellite imagery from the Massachusetts Roads Dataset. We implement and train three deep learning models from scratch using PyTorch:
-   **UNet:** A classic and effective architecture for semantic segmentation.
-   **Attention UNet:** An extension of UNet that uses attention gates to focus on more relevant features.
-   **Residual Attention UNet:** A further enhancement that incorporates residual blocks to improve gradient flow and training stability.

The goal is to compare their performance based on metrics like IoU and Dice Score.

Video:
**https://drive.google.com/file/d/1uAh-22HMqb5YPePZ-D8QXwUMM-Yn0YKi/view?usp=sharing**

## Phase 2: Soft Actor-Critic (SAC) for Continuous Control

In the second phase, we delve into Reinforcement Learning. We implement the Soft Actor-Critic (SAC) algorithm to train an agent for the `HalfCheetah-v4` continuous control environment.

SAC is an off-policy, maximum entropy algorithm designed to learn complex policies efficiently and robustly. Our implementation includes the core components: Actor (policy), Critic (Q-value), and automated entropy tuning.

**[Link to Phase 2 Video Presentation]**
