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

A lab can address the experimentation needs for many kind of users. It aims at standardizing and automating the most time-consuming parts of the experimentation process, making it easy to run relevant experiments. It also makes possible combining experiments or building on top of existing ones to tackle even more advance problems without remodeling and reimplementing everything from scratch. It hence modularizes experiments.

## Features

Here are the interesting features of GridAlive: 
1. **Unified environment and agent interface** using OpenAI Gym, Tensorflow, Keras and more, so you can focus on developing control algorithms.
2. **[Synthetic Data Generation with ChroniX2Grid](https://github.com/BDonnot/ChroniX2Grid)** to model realistic chronics of any power system worldwide, as they are today or will be tomorrow. 
3. **[An experimentation framework with Grid2op](https://github.com/rte-france/Grid2Op)** for developping new environments and running hundreds of trials under different configurations, with logs, plots and analytics for testing new control algorithms. Experimental settings are stored in standardized JSONs for reproducibility and comparisons.
4. **[Interfacing the simulator of your choice](https://github.com/rte-france/gridAlive/backends)** depending on the problem requirements or for benchmarking similar simulators. **Lightsim2grid** can be a first handy a fast simulator to run.
5. **[In-depth analytics of the experiments with Grid2viz](https://github.com/rte-france/grid2viz)** for evaluating the agents and environments, and to help pick the best solution.
6. **[Custom Benchmarking evaluation tool with Grid2Bench](https://github.com/IRT-SystemX/Grid2Bench)** for automatically benchmarking several agents on list of custom KPIs through a report generation
7. **[Open-source algorithm implementations with l2rpn-baselines](https://github.com/rte-france/l2rpn-baselines), with reusable modular components** for developing more advanced algorithms or benchmarking over new environments.
8. **[Interactive Human-AI GUI with Grid2game](https://github.com/BDonnot/grid2game),** for letting human play decision scenarios assisted by an AI agent, to experiment with hybrid Human-AI collaboration

![GridAlive overview](https://github.com/rte-france/gridAlive/blob/master/pictures/GridALive_schematic.png)

# License information
Copyright 2019-2020 RTE France

    RTE: http://www.rte-france.com

This Source Code is subject to the terms of the Mozilla Public License (MPL) v2 also available 
[here](https://www.mozilla.org/en-US/MPL/2.0/)




