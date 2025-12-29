This repository provides lerobot-diffusion-policy checkpoints for inference.

We use SO-ARM101 to sample 50 episodes with two external cameras from different views.

The task is to grab the green cube from three cubes. We set up five environments, each with randomly shuffled blocks in order and position, and collected ten episodes from each environment.

We used the default parameters, and the entire training process took approximately 2–3 hours (1 A800 GPU).
