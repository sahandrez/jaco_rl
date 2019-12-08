# RL on Jaco Arm in DeepMind Control Suite
This repository implements [TD3](https://arxiv.org/abs/1802.09477) and 
[DDPG](https://arxiv.org/abs/1509.02971) on DeepMind Control Suite tasks. 

* This repository needs the `jaco_arm` branch of `dm_control` forked 
[here](https://github.com/sahandrez/dm_control/tree/jaco_arm). 
* The agent implementations are taken from the [Official TD3 repository](https://github.com/sfujim/TD3).

## Usage
You can train an agent for the reaching task on Jaco arm by running:
```
python main.py --task jaco --domain easy
```
