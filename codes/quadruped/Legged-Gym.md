# Legged Gym

|         | Links                                        |
| ------- | -------------------------------------------- |
| Project | https://leggedrobotics.github.io/legged_gym/ |
| Code    | https://github.com/leggedrobotics/legged_gym |



## Requirement

- nvidia-driver-525-server
- Cuda 11.3
- PyTorch 1.10
- IsaacGym
- rsl_rl v1.0.2
- setuptools 59.5.0



## Usage

- `python legged_gym/scripts/train.py --task=anymal_c_flat --sim_device=cuda --rl_device=cuda --headless `

- `python legged_gym/scripts/train.py --task=anymal_c_flat --sim_device=cuda --rl_device=cuda --pipeline=cpu --num_envs=1024  `