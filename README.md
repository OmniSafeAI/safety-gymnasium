<div align="center">
<h1>
  Safety-Gymnasium
</h1>
</div>

<div align="center">

  <a>![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-brightgreen.svg)</a>
  <a href="https://pypi.org/project/safety-gymnasium">![PyPI](https://img.shields.io/pypi/v/safety-gymnasium?logo=pypi)</a>
  <a href="https://safety-gymnasium.readthedocs.io">![Documentation Status](https://img.shields.io/readthedocs/safety-gymnasium?logo=readthedocs)</a>
  <a href="https://pepy.tech/project/safety-gymnasium">![Downloads](https://static.pepy.tech/personalized-badge/safety-gymnasium?period=total&left_color=grey&right_color=blue&left_text=downloads)</a>
  <a href="https://github.com/PKU-Alignment/safety-gymnasium/stargazers">![GitHub Repo Stars](https://img.shields.io/github/stars/PKU-Alignment/safety-gymnasium?color=brightgreen&logo=github)</a>
  <a href="https://github.com/PKU-Alignment/safety-gymnasium/blob/HEAD/LICENSE">![License](https://img.shields.io/github/license/PKU-Alignment/safety-gymnasium?label=license&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSIjZmZmZmZmIj48cGF0aCBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0xMi43NSAyLjc1YS43NS43NSAwIDAwLTEuNSAwVjQuNUg5LjI3NmExLjc1IDEuNzUgMCAwMC0uOTg1LjMwM0w2LjU5NiA1Ljk1N0EuMjUuMjUgMCAwMTYuNDU1IDZIMi4zNTNhLjc1Ljc1IDAgMTAwIDEuNUgzLjkzTC41NjMgMTUuMThhLjc2Mi43NjIgMCAwMC4yMS44OGMuMDguMDY0LjE2MS4xMjUuMzA5LjIyMS4xODYuMTIxLjQ1Mi4yNzguNzkyLjQzMy42OC4zMTEgMS42NjIuNjIgMi44NzYuNjJhNi45MTkgNi45MTkgMCAwMDIuODc2LS42MmMuMzQtLjE1NS42MDYtLjMxMi43OTItLjQzMy4xNS0uMDk3LjIzLS4xNTguMzEtLjIyM2EuNzUuNzUgMCAwMC4yMDktLjg3OEw1LjU2OSA3LjVoLjg4NmMuMzUxIDAgLjY5NC0uMTA2Ljk4NC0uMzAzbDEuNjk2LTEuMTU0QS4yNS4yNSAwIDAxOS4yNzUgNmgxLjk3NXYxNC41SDYuNzYzYS43NS43NSAwIDAwMCAxLjVoMTAuNDc0YS43NS43NSAwIDAwMC0xLjVIMTIuNzVWNmgxLjk3NGMuMDUgMCAuMS4wMTUuMTQuMDQzbDEuNjk3IDEuMTU0Yy4yOS4xOTcuNjMzLjMwMy45ODQuMzAzaC44ODZsLTMuMzY4IDcuNjhhLjc1Ljc1IDAgMDAuMjMuODk2Yy4wMTIuMDA5IDAgMCAuMDAyIDBhMy4xNTQgMy4xNTQgMCAwMC4zMS4yMDZjLjE4NS4xMTIuNDUuMjU2Ljc5LjRhNy4zNDMgNy4zNDMgMCAwMDIuODU1LjU2OCA3LjM0MyA3LjM0MyAwIDAwMi44NTYtLjU2OWMuMzM4LS4xNDMuNjA0LS4yODcuNzktLjM5OWEzLjUgMy41IDAgMDAuMzEtLjIwNi43NS43NSAwIDAwLjIzLS44OTZMMjAuMDcgNy41aDEuNTc4YS43NS43NSAwIDAwMC0xLjVoLTQuMTAyYS4yNS4yNSAwIDAxLS4xNC0uMDQzbC0xLjY5Ny0xLjE1NGExLjc1IDEuNzUgMCAwMC0uOTg0LS4zMDNIMTIuNzVWMi43NXpNMi4xOTMgMTUuMTk4YTUuNDE4IDUuNDE4IDAgMDAyLjU1Ny42MzUgNS40MTggNS40MTggMCAwMDIuNTU3LS42MzVMNC43NSA5LjM2OGwtMi41NTcgNS44M3ptMTQuNTEtLjAyNGMuMDgyLjA0LjE3NC4wODMuMjc1LjEyNi41My4yMjMgMS4zMDUuNDUgMi4yNzIuNDVhNS44NDYgNS44NDYgMCAwMDIuNTQ3LS41NzZMMTkuMjUgOS4zNjdsLTIuNTQ3IDUuODA3eiI+PC9wYXRoPjwvc3ZnPgo=)</a>

</div>

<p align="center">
<a href="https://github.com/PKU-Alignment/safety-gymnasium#why-safety-gymnasium">Why Safety-Gymnasium?</a> |
  <a href="https://www.safety-gymnasium.com">Documentation</a> |
  <a href="https://github.com/PKU-Alignment/safety-gymnasium#installation">Install guide</a> |
  <a href="https://github.com/PKU-Alignment/safety-gymnasium#customize-your-environments">Customization</a> |
  <a href="https://github.com/PKU-Alignment/safety-gymnasium#future-plans">Future Plan</a>
</p>

Safety-Gymnasium is a highly scalable and customizable Safe Reinforcement Learning (SafeRL) library.
It aims to deliver a good view of benchmarking SafeRL algorithms and a standardized set of environments.
We provide a set of standard APIs which are compatible with information on constraints.
Users can explore new insights via an elegant code framework and well-designed environments.

--------------------------------------------------------------------------------

## Why Safety-Gymnasium?

Here we provide a table for comparison of **Safety-Gymnasium** and existing SafeRL Environments libraries.

|                                                                                   SafeRL<br/>Envs                                                                                   |            Engine             | Vectorized<br/> Environments | New Gym API<sup>**(3)**</sup> |    Vision Input     |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------: | :--------------------------: | :---------------------------: | :-----------------: |
|            [Safety Gym](https://github.com/openai/safety-gym)<br/>![GitHub last commit](https://img.shields.io/github/last-commit/openai/safety-gym?label=last%20update)            | `mujoco-py`<sup>**(1)**</sup> |              ❌               |               ❌               | minimally supported |
| [safe-control-gym](https://github.com/utiasDSL/safe-control-gym)<br/>![GitHub last commit](https://img.shields.io/github/last-commit/utiasDSL/safe-control-gym?label=last%20update) |           PyBullet            |              ❌               |               ❌               |          ❌          |
|                                                                       Velocity-Constraints<sup>**(2)**</sup>                                                                        |              N/A              |              ❌               |               ❌               |          ❌          | ❌ |
|    [mujoco-circle](https://github.com/ymzhang01/mujoco-circle)<br/>![GitHub last commit](https://img.shields.io/github/last-commit/ymzhang01/mujoco-circle?label=last%20update)     |            PyTorch            |              ❌               |               ❌               |          ❌          | ❌ |
|                                  Safety-Gymnasium<br/>![GitHub last commit](https://img.shields.io/github/last-commit/PKU-Alignment/safety-gymnasium)                                  |       **MuJoCo 2.3.0+**       |              ✅               |               ✅               |          ✅          |

<sup>(1): Maintenance (expect bug fixes and minor updates); the last commit is 19 Nov 2021. Safety Gym depends on `mujoco-py` 2.0.2.7, which was updated on Oct 12, 2019.</sup><br/>
<sup>(2): There is no official library for speed-related environments, and its associated cost constraints are constructed from info. But the task is widely used in the study of SafeRL, and we encapsulate it in Safety-Gymnasium.</sup><br/>
<sup>(3): In the gym 0.26.0 release update, a new API of interaction was redefined.</sup>

--------------------------------------------------------------------------------

## Environments

We designed a variety of safety-enhanced learning tasks and integrated the contributions from the RL community: `safety-velocity`, `safety-run`, `safety-circle`, `safety-goal`, `safety-button`, etc.
We introduce a unified safety-enhanced learning benchmark environment library called `Safety-Gymnasium.`

Further, to facilitate the progress of community research, we redesigned [Safety Gym](https://github.com/openai/safety-gym) and removed the dependency on `mujoco-py`.
We built it on top of [MuJoCo](https://github.com/deepmind/mujoco) and fixed some bugs, more specific bug reports can refer to [Safety Gym's BUG Report](https://github.com/PKU-Alignment/safety-gymnasium/blob/main/safety_gym_bug_report.md).

Here is a list of all the environments we support for now:

<table border="1">
  <thead>
    <tr>
      <th>Category</th>
      <th>Task</th>
      <th>Agent</th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4">Safe Navigation</td>
      <td>Goal[012]</td>
      <td rowspan="4">Point, Car, Doggo, Racecar, Ant</td>
      <td rowspan="4">SafetyPointGoal1-v0</td>
    </tr>
    <tr>
      <td>Button[012]</td>
    </tr>
    <tr>
      <td>Push[012]</td>
    </tr>
    <tr>
      <td>Circle[012]</td>
    </tr>
    <tr>
      <td>Velocity</td>
      <td>Velocity</td>
      <td>HalfCheetah, Hopper, Swimmer, Walker2d, Ant, Humanoid</td>
      <td>SafetyAntVelocity-v1</td>
    </tr>
  </tbody>
</table>

**Note**: We newly support `Doggo` agent in `v0.4.0`, the corresponding `benchmarks`, `pictures`, and `documentation` will be updated soon. And `PRs` are welcome.

Here are some screenshots of the Safe Navigation tasks.

#### Agents

<table class="docutils align-default">
  <tbody>
    <tr class="row-odd">
      <td>
        <figure class="align-default">
          <a class="reference external image-reference"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/point_front.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/point_front.jpeg"
              style="width: 180px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="doc">Point</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference" href="agents/car.html"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/car_front.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/car_front.jpeg"
              style="width: 180px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="doc">Car</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference" href="agents/racecar.html"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/racecar_front.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/racecar_front.jpeg"
              style="width: 180px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="doc">Racecar</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference" href="agents/ant.html"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/doggo_front.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/doggo_front.jpeg"
              style="width: 180px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="doc">Ant</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference" href="agents/ant.html"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/ant_front.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/ant_front.jpeg"
              style="width: 180px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="doc">Ant</span></a></strong>
        </p>
      </td>
    </tr>
  </tbody>
</table>

#### Tasks

<table class="docutils align-default">
  <tbody>
    <tr class="row-odd">
      <td>
        <figure class="align-default">
          <a class="reference external image-reference"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/goal0.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/goal0.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Goal0</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/goal1.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/goal1.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Goal1</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/goal2.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/goal2.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Goal2</span></a></strong>
        </p>
      </td>
    </tr>
    <tr class="row-even">
      <td>
        <figure class="align-default">
          <a class="reference external image-reference"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/button0.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/button0.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Button0</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference" href="./button#button1"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/button1.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/button1.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Button1</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference" href="./button#button2"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/button2.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/button2.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Button2</span></a></strong>
        </p>
      </td>
    </tr>
    <tr class="row-odd">
      <td>
        <figure class="align-default">
          <a class="reference external image-reference"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/push0.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/push0.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Push0</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/push1.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/push1.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Push1</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/push2.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/push2.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Push2</span></a></strong>
        </p>
      </td>
    </tr>
    <tr class="row-even">
      <td>
        <figure class="align-default">
          <a class="reference external image-reference"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/circle0.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/circle0.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Circle0</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/circle1.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/circle1.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Circle1</span></a></strong>
        </p>
      </td>
      <td>
        <figure class="align-default">
          <a class="reference external image-reference" href="./circle#circle2"><img
              alt="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/circle2.jpeg"
              src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/circle2.jpeg" style="width: 230px;"></a>
        </figure>
        <p class="centered">
          <strong><a class="reference internal"><span class="std std-ref">Circle2</span></a></strong>
        </p>
      </td>
    </tr>
  </tbody>
</table>

### Vision-base Safe RL

Vision-based safety reinforcement learning lacks realistic scenarios.
Although the original `Safety Gym` could minimally support visual input, the scenarios were too similar.
To facilitate the validation of visual-based safety reinforcement learning algorithms, we have developed a set of realistic vision-based SafeRL tasks, which are currently being validated on the baseline.

For the appetizer, the images are as follows:

<img src="https://github.com/PKU-Alignment/safety-gymnasium/raw/HEAD/images/vision_input.png" width="100%"/>

### Environment Usage

**Notes:** We support explicitly expressing the `cost` based on [**Gymnasium APIs**](https://github.com/Farama-Foundation/Gymnasium).
The `step` method returns 6 items `(next_obervation, reward, cost, terminated, truncated, info)` with an extra `cost` field.

```python
import safety_gymnasium

env_id = 'SafetyPointGoal1-v0'
env = safety_gymnasium.make(env_id)

obs, info = env.reset()
while True:
    act = env.action_space.sample()
    obs, reward, cost, terminated, truncated, info = env.step(act)
    if terminated or truncated:
        break
    env.render()
```

We also provide two convenience wrappers for converting the Safety-Gymnasium environment to the standard Gymnasium API and vice versa.

```python
# Safety-Gymnasium API: step returns (next_obervation, reward, cost, terminated, truncated, info)
# Gymnasium API:        step returns (next_obervation, reward, terminated, truncated, info) and cost is in the `info` dict associated with a str key `'cost'`

safety_gymnasium_env = safety_gymnasium.make(env_id)
gymnasium_env = safety_gymnasium.wrappers.SafetyGymnasium2Gymnasium(safety_gymnasium_env)

safety_gymnasium_env = safety_gymnasium.wrappers.Gymnasium2SafetyGymnasium(gymnasium_env)
```

Users can apply Gymnasium wrappers easily with:

```python
import gymnasium
import safety_gymnasium

def make_safe_env(env_id):
    safe_env = safety_gymnasium.make(env_id)
    env = safety_gymnasium.wrappers.SafetyGymnasium2Gymnasium(safe_env)
    env = gymnasium.wrappers.SomeWrapper1(env)
    env = gymnasium.wrappers.SomeWrapper2(env, argname1=arg1, argname2=arg2)
    ...
    env = gymnasium.wrappers.SomeWrapperN(env)
    safe_env = safety_gymnasium.wrappers.Gymnasium2SafetyGymnasium(env)
    return safe_env
```

or

```python
import functools

import gymnasium
import safety_gymnasium

def make_safe_env(env_id):
    return safety_gymnasium.wrappers.with_gymnasium_wrappers(
        safety_gymnasium.make(env_id),
        gymnasium.wrappers.SomeWrapper1,
        functools.partial(gymnasium.wrappers.SomeWrapper2, argname1=arg1, argname2=arg2),
        ...,
        gymnasium.wrappers.SomeWrapperN,
    )
```

In addition, for all Safety-Gymnasium environments, we also provide corresponding Gymnasium environments with a suffix `Gymnasium` in the environment id. For example:

```python
import gymnasium
import safety_gymnasium

safety_gymnasium.make('SafetyPointGoal1-v0')    # step returns (next_obervation, reward, cost, terminated, truncated, info)
gymnasium.make('SafetyPointGoal1Gymnasium-v0')  # step returns (next_obervation, reward, terminated, truncated, info)
```

--------------------------------------------------------------------------------

## Installation

### Install from PyPI

```bash
pip install safety-gymnasium
```

### Install from source

```bash
conda create -n <envname> python=3.8
conda activate <envname>

git clone https://github.com/PKU-Alignment/safety-gymnasium.git
cd safety-gymnasium
pip install -e .
```

### Important Notes

If you failed to render on your server, you can try:

```bash
echo "export MUJOCO_GL=osmesa" >> ~/.bashrc
source ~/.bashrc
apt-get install libosmesa6-dev
apt-get install python3-opengl
```

--------------------------------------------------------------------------------

## Customize your environments

We construct a highly expandable framework of code so that you can easily comprehend it and design your environments to facilitate your research with no more than 100 lines of code on average.

For details, please refer to our documentation.
Here is a minimal example:

```python
# import the objects you want to use
# or you can define specific objects by yourself, just make sure obeying our specification
from safety_gymnasium.assets.geoms import Apples
from safety_gymnasium.bases import BaseTask

# inherit the basetask
class MytaskLevel0(BaseTask):
    def __init__(self, config):
        super().__init__(config=config)
        # define some properties
        self.num_steps = 500
        self.agent.placements = [(-0.8, -0.8, 0.8, 0.8)]
        self.agent.keepout = 0
        self.lidar_conf.max_dist = 6
        # add objects into environments
        self.add_geoms(Apples(num=2, size=0.3))

    def calculate_reward(self):
        # implement your reward function
        # Note: cost calculation is based on objects, so it's automatic
        reward = 1
        return reward

    def specific_reset(self):
        # depending on your task

    def specific_step(self):
        # depending on your task

    def update_world(self):
        # depending on your task

    @property
    def goal_achieved(self):
        # depending on your task
```

## Future Plans

- [ ] Vision-based environments
- [ ] Bring in other robots
- [ ] Tested on different Python versions
- [ ] Tested on Windows and macOS

## Citing Safety-Gymnasium

If you find Safety-Gymnasium useful, please cite it in your publications.

```bibtex
@article{Safety-Gymnasium,
  author = {Jiaming Ji and Borong Zhang and Xuehai Pan and Jiayi Zhou and Juntao Dai and Yaodong Yang},
  title = {Safety-Gymnasium},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/PKU-Alignment/safety-gymnasium}},
}
```

## License

Safety-Gymnasium is released under Apache License 2.0.
