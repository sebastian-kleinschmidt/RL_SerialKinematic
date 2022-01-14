<div id="top"></div>

<br />
<div align="center">

<h3 align="center">Deep Reinforcement Learning Project: Serial Kinematic</h3>

  <p align="center">
    This projects demonstrates an agent learning to control a serial kinematic to follow a sphere.
    <br />
    <a href="https://github.com/sebastian-kleinschmidt/RL_SerialKinematic"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/sebastian-kleinschmidt/RL_SerialKinematic">View Demo</a>
    ·
    <a href="https://github.com/sebastian-kleinschmidt/RL_SerialKinematic/issues">Report Bug</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

This projects demonstrates an agent learning to control a serial kinematic to follow a sphere using **Deep Reinforcement Learning**.

### Environment Details

#### Reward
A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

#### State and Action Space
The state space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

#### Goal
The task is episodic, and in order to solve the environment, your agent must get an average score of +30 over 100 consecutive episodes.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* [Jupyter Notebook](https://jupyter.org/)
* [Conda](https://docs.conda.io/)
* [PyTorch](https://pytorch.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites and Installation

This project needs Conda installed on your system to create the needed environment. To then create a conda environment including all dependencies, use the following commands:
1. Create and activate a conda environment:
  ```sh
  conda create --name drl python=3.6
  source activate drl
  ```
> :warning: **If you are on a Windows machine**: Use ```activate drl``` instead of ```source activate drl```

2. Install required dependencies:
  ```sh
  pip install -r requirements.txt
  ```

3. Create an IPython kernel for the drl environment:
  ```sh
  python -m ipykernel install --user --name drl --display-name "drl"
  ```


<!-- USAGE EXAMPLES -->
## Usage
You can start the Jupyter Notebook by executing ```jupyter notebook``` in an active drl Conda environment (see prerequisites section). Execute the documented cells to either train a new agent or use the preptrained one.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://github.com/sebastian-kleinschmidt/RL_SerialKinematic.svg?style=for-the-badge
[contributors-url]: https://github.com/sebastian-kleinschmidt/RL_SerialKinematic/graphs/contributors
[forks-shield]: https://github.com/sebastian-kleinschmidt/RL_SerialKinematic.svg?style=for-the-badge
[forks-url]: https://github.com/sebastian-kleinschmidt/RL_SerialKinematic/network/members
[stars-shield]: https://github.com/sebastian-kleinschmidt/RL_SerialKinematic.svg?style=for-the-badge
[stars-url]: https://github.com/sebastian-kleinschmidt/RL_SerialKinematic/stargazers
[issues-shield]: https://github.com/sebastian-kleinschmidt/RL_SerialKinematic.svg?style=for-the-badge
[issues-url]: https://github.com/sebastian-kleinschmidt/RL_SerialKinematic/issues
[license-shield]: https://github.com/sebastian-kleinschmidt/RL_SerialKinematic.svg?style=for-the-badge
[license-url]: https://github.com/sebastian-kleinschmidt/RL_SerialKinematic/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/sebastiankleinschmidt/
[product-screenshot]: images/serialkinematic.gif