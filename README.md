# Results

https://github.com/riensou/rl_drone/assets/90002238/b56220b4-e431-40de-b099-ae7f3650d1a1
https://github.com/riensou/rl_drone/assets/90002238/10f46ea1-41ff-4596-8c67-2c206ef303cc

# References

[PyFlyt environment](https://jjshoots.github.io/PyFlyt/documentation/gym_envs/quadx_waypoints_env.html
)


[stable baselines](https://stable-baselines3.readthedocs.io/en/master/index.html)

# Setup

1. Create a conda environment that will contain python 3:
```
conda create -n rl_drone python=3.9
```

2. activate the environment (do this every time you open a new terminal and want to run code):
```
source activate rl_drone
```

3. Install the requirements into this conda environment
```
cd src
pip install -r requirements.txt
```

4. Allow your code to be able to see 'acl'
```
$ pip install -e .
```

# Visualizing with Tensorboard

You can visualize your runs using tensorboard:
```
tensorboard --logdir data
```
