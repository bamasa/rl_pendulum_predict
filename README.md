# Using RL to predict the next state of a pendulum

### Идея:

Есть два маятника. Хочется помощью маятника 1 предсказывать положение маятника 2. На маятник 2 оказывается воздействие, параметры которого частично известны. Параметры маятника 1 настраиваются. Для настройки параметров маятника 1 используется нейронная сеть, обучаемая с помощью Reinforcement Learning.

### Результаты:

Последние результаты для [8 шагов](https://github.com/bamasa/rl_pendulum_predict/blob/master/motion_4-hist-stable-n_steps%3D8.ipynb) и [для 20 шагов](https://github.com/bamasa/rl_pendulum_predict/blob/master/motion_4-hist-n_steps%3D20.ipynb).

### Models

CE and DDPG. The DDPG model is taken from [here](https://github.com/udacity/deep-reinforcement-learning/tree/master/ddpg-pendulum).
