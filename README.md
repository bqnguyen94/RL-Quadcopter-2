# Deep RL Quadcopter Controller

This project is part of Udacity's Reinforcement Learning chapter in the Machine Learning Engineer Nanodegree Program and the Deep Learning Nanodegree Program.

The original repository can be found [here](https://github.com/bqnguyen94/RL-Quadcopter-2.git).

## Goal

This project aims to derive an agent that controls a quadcopter drone to perform take off task with maximized accuracy.

## Algorithm

The algorithm used in the final design of the agent is the Deep Deterministic Policy Gradients (DDPG). The agent consists of an actor and a critic, both used deep neural networks as the learning engine.

## Result

The results can be found in the project's [notebook](Quadcopter_Project.html).

## Project Instructions

1. Clone the repository and navigate to the downloaded folder.

```
git clone https://github.com/bqnguyen94/RL-Quadcopter-2.git
cd RL-Quadcopter-2
```

2. Create and activate a new environment.

```
conda create -n quadcop python=3.6 matplotlib numpy pandas
source activate quadcop
```

3. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `quadcop` environment.
```
python -m ipykernel install --user --name quadcop --display-name "quadcop"
```

4. You will need to install Keras and a backend package to train the actor and critic. It is recommended to use Keras + Tensorflow. Installation of these packages on Unix systems should be straightforward; on Windows, you can follow [these steps.](http://inmachineswetrust.com/posts/deep-learning-setup/). Note that you can opt for the GPU-supported version of Tensorflow for better performance; to do so, follow [this guide](https://blog.paperspace.com/running-tensorflow-on-windows/).

5. Now that everything is set, you can open the notebook.
```
jupyter notebook Quadcopter_Project.ipynb
```
