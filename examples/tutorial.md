## Using the RLlib CLI

```
pip install "ray[rllib]" tensorflow torch
rllib train --algo DQN --env CartPole-v1 --stop '{"training_iteration": 30}'
```
