# Deep-Q-Learning-for-Cartpole-env-in-gymnasium

This is a jupyter notebook for realizing the deep q learning for cartpole in gymnasium environment

The checkpoint for the model is provided in the folder __/checkpoints__  
The checkpoints should guarantee for a 280+ reward on average. 

## Set up environment

To set up the environment, run


```
sh make.sh
```

This should collect and install the packages required into a new env called cartpole_env.

After everything is installed, run

```
conda activate cartpole_env
jupyter notebook
```

And then you can open the jupyter notebook and run the code
