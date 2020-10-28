# GridAlive

GridAlive is a **full lab ecosystem** to model and study a large class of power system related problems. It relies on [Grid2op](https://github.com/rte-france/Grid2Op) experimentation framework at its core.

More specifically, it let one model time-dependant and decision-making problems such as real-time power grid operations or future grid development. 
Recent **competitions along NeurIPS 2020 conference** tackled such problems indeed (see https://l2rpn.chalearn.org/ for more information). 
These competitions demonstrated the richfullness of GridALive framework to design and run such large scale experiments, which now turn into benchmarks that help the research community make new advances at large together.

## A lab
A lab is a place with a set of tools and a framework where you can:
- study and model a large class of problems 
- define and implement new experiments 
- run and analyze experiments
- reproduce and share experiments
- replay experiments on demand
- create new benchmarks

A lab can address the experimentation needs for many kind of users.

## Features

Here are the interesting features of GridAlive: 
1. **Unified environment and agent interface** using OpenAI Gym, Tensorflow, Keras and more, so you can focus on developing control algorithms.
2. **[Synthetic Data Generation with ChroniX2Grid](https://github.com/mjothy/ChroniX2Grid)** to model realistic chronics of any power system worldwide, as they are today or will be tomorrow. 
3. **[An experimentation framework with Grid2op](https://github.com/rte-france/Grid2Op)** for developping new environments and running hundreds of trials under different configurations, with logs, plots and analytics for testing new control algorithms. Experimental settings are stored in standardized JSONs for reproducibility and comparisons.
4. **[Interfacing the simulator of your choice](https://github.com/rte-france/gridAlive/backends)** depending on the problem requirements or for benchmarking similar simulators.
5. **[In-depth analytics of the experiments with Grid2viz](https://github.com/mjothy/grid2viz)** for evaluating the agents and environments, and to help pick the best solution.
6. **[Open-source algorithm implementations](https://github.com/rte-france/l2rpn-baselines), with reusable modular components** for developing more advanced algorithms or benchmarking over new environments.

![GridAlive overview](https://github.com/rte-france/gridAlive/blob/master/pictures/GridALive_schematic.png)

# License information
Copyright 2019-2020 RTE France

    RTE: http://www.rte-france.com

This Source Code is subject to the terms of the Mozilla Public License (MPL) v2 also available 
[here](https://www.mozilla.org/en-US/MPL/2.0/)



