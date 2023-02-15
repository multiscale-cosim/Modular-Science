<div align="center" id="top"> 
  <img src="../../../misc/logo.jpg" alt="Modular Science Framework" />

  &#xa0;

  <!-- <a href="git@github.com:multiscale-cosim/TVB-NEST-usecase1.git">Demo</a> -->
</div>

<h1 align="center">Modular Science Framework v1.0</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/multiscale-cosim/TVB-NEST-usecase1?color=56BEB8" />

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/multiscale-cosim/TVB-NEST-usecase1?color=56BEB8" />

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/multiscale-cosim/TVB-NEST-usecase1?color=56BEB8" />

  <img alt="License" src="https://img.shields.io/github/license/multiscale-cosim/TVB-NEST-usecase1?color=56BEB8" />

  <img alt="Github issues" src="https://img.shields.io/github/issues/multiscale-cosim/TVB-NEST-usecase1?color=56BEB8" />

  <img alt="Github forks" src="https://img.shields.io/github/forks/multiscale-cosim/TVB-NEST-usecase1?color=56BEB8" />

  <img alt="Github stars" src="https://img.shields.io/github/stars/multiscale-cosim/TVB-NEST-usecase1?color=56BEB8" />
</p>

<hr>

<p align="center">
  <a href="#about">About</a> &#xa0; | &#xa0; 
  <a href="#features">Features</a> &#xa0; | &#xa0;
  <a href="#technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#how-to-use">How to use</a> &#xa0; | &#xa0;
  <a href="#license">License</a> &#xa0; | &#xa0;
  <a href="#author" target="_blank">Author</a> &#xa0; | &#xa0;
  <a href="#acknowledgement" target="_blank">Acknowledgement</a>
</p>

<br>

## About ##

The Modular Science (MSC) Framework facilitates deployment, integratation, orchestration and intuitive & interactive control of larger complex workflows.
It can execute a independant applications running in parallel on heterogeneous HPC platforms. The framework comprises a set of following micro-services like independent applications:

* <a href="https://github.com/multiscale-cosim/EBRAINS_ConfigManager"> Configurations Manager </a>
* <a href="https://github.com/multiscale-cosim/EBRAINS_InterscaleHUB"> InterscaleHub </a>
* <a href="https://github.com/multiscale-cosim/EBRAINS_Launcher"> Launcher </a>
* <a href="https://github.com/multiscale-cosim/EBRAINS_RichEndpoint"> Rich Endpoint </a>
* <a href="https://github.com/multiscale-cosim/EBRAINS_WorkflowConfigurations"> Workflow Configurations </a>

## Features ##

 - Provides a handle on the complexity of the co-simulation deployment and execution on high-performance computing (HPC) systems.
 - Offers the steering of the execution of the whole workflow
 - Offers the insights in both the system level and the individual subsystem (application/simulator) levels to monitor the resource usage (e.g. CPU, Memory) without affecting the performance.
 - Provides with the health & status information of the whole system and the application/simulator-wide to detect the failures, bottlenecks and dubugging purposes without having any affects on performance.
 - Keeps the track of steering and state transitions for provenance tracking.


## Technologies ##

The following tools were used in this project:

- [Python](https://www.python.org/)
- [CMake](https://cmake.org/)
- [C++](https://isocpp.org/)
- [Makefile](https://www.gnu.org/software/make/manual/make.html)

## How to use ##

The first release of the Modular Science Framework includes the driving usecase as demonstration of multi-scale co-simulations. Follow below links to the repositories of this usecase for a more detailed description, installation guide and how to run it.

- [TVB NEST Co-simulation Usecase 1](https://github.com/multiscale-cosim/TVB-NEST-usecase1/tree/stable-release): A multi-scale neuroscience use-case which connects a spiking neural network with a neural mass model using the simulators [NEST](https://www.nest-simulator.org/) and [TVB](https://www.thevirtualbrain.org/tvb/) respectively.
- more to come...

## License ##

This project is under license from BSD 3-Clause. For more details, see the [LICENSE](LICENSE) file.

## Author ##

Made by the <a href="https://www.fz-juelich.de/en/ias/jsc/about-us/structure/simulation-and-data-labs/sdl-neuroscience/teams" target="_blank">Multiscale Simulation and Design team</a> of the Simulation and Data Lab (SDL) Neuroscience at Forschungszentrum Jülich.

## Acknowledgement ##

This project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 785907 (HBP SGA2). 

This project/research has received funding from the European Union’s Horizon 2020 Framework Programme for Research and Innovation under the Specific Grant Agreement No. 945539 (HBP SGA3). Specific Grant Agreement ‘Interactive Computing E-Infrastructure for the Human Brain Project – ICEI’ (01/2018-03/2023).

This project has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 800858 (HBP SGA ICEI).


&#xa0;

<a href="#top">Back to top</a>
