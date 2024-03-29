<div align="center" id="top"> 
  <img src="<insert beatufil image here>" alt="Modular Science Framework" />

  &#xa0;

  <!-- <a href="git@github.com:multiscale-cosim/TVB-NEST-usecase1.git">Demo</a> -->
</div>

<h1 align="center">Modular Science Framework v2.0</h1>

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

The [Modular Science Framework](https://www.fz-juelich.de/en/ias/jsc/about-us/structure/simulation-and-data-labs/sdl-neuroscience/research/modular-science) provides a low entry threshold software framework to ease the deployment of complex interactive workflows on HPC resources. In particular, it tackles the following two challenges: 
 1. the robust online deployment of a complex workflow comprises multiple applications
 2. the orchestration of data flows in an interactive and reproducible fashion.

The framework comprises a set of following micro-services like independent applications:

* <a href="https://github.com/multiscale-cosim/EBRAINS_ConfigManager"> Configurations Manager </a>
* <a href="https://github.com/multiscale-cosim/EBRAINS_InterscaleHUB"> InterscaleHub </a>
* <a href="https://github.com/multiscale-cosim/EBRAINS_Launcher"> Launcher </a>
* <a href="https://github.com/multiscale-cosim/EBRAINS_RichEndpoint"> Rich Endpoint </a>
* <a href="https://github.com/multiscale-cosim/EBRAINS_WorkflowConfigurations"> Workflow Configurations </a>

## Features ##

 - Provides a handle on the deployment of complex co-simulation workflows and their execution on high-performance computing (HPC) systems.
 - Offers steering of the execution of the workflows
 - Offers insights on both levels, system (HPC) and individual subsystem (application/simulator), in order to monitor the resource usage (e.g. CPU, Memory).
 - Provides health & status information of the whole system and individual applications to detect failures and bottlenecks for effienct use of resources and dubugging purposes with minimal overhead on performance.
 - Keeps track of steering and state transitions for provenance tracking.


## Technologies ##

The following tools were used in this project:

- [Python](https://www.python.org/)
- [CMake](https://cmake.org/)
- [C++](https://isocpp.org/)
- [Makefile](https://www.gnu.org/software/make/manual/make.html)

## How to use ##

Modular Science Framework v2.0 includes the following driving usecases as demonstration of multi-scale co-simulations. Follow below link to the repository of these usecase for a more detailed description, installation guide and how to run it.


- [TVB NEST Co-simulation Usecase 1](https://github.com/multiscale-cosim/TVB-NEST-usecase1): A multi-scale neuroscience use-case which connects a spiking neural network with a neural mass model using the simulators [NEST](https://www.nest-simulator.org/) and [TVB](https://www.thevirtualbrain.org/tvb/) respectively.
- [NEST LFPy](https://github.com/multiscale-cosim/Cosim-LFPy): This usecase demonstrates how to use the Co-simulation framework to calculate Local Field Potentials (LFPs) in real time, based on spike events streamed from the [NEST](https://www.nest-simulator.org/) simulator. The LFP signals are calculated from the spike events by applying the so-called kernel approach, as outlined in Hagen et al. (2022): https://doi.org/10.1371/journal.pcbi.1010353. This usecase can be used as a starting point for applying the Co-simulation framework to other network models in NEST or TVB, and also for simulating other brain signals like EEG, MEG, or ECoG signals.
- [Cosim-NEST Desktop-Insite](https://github.com/multiscale-cosim/Cosim_NestDesktop_Insite): It demonstrates the seemsless integration of Modular Science with external tools such as [NEST Desktop](https://nest-desktop.readthedocs.io/en/latest/) (a web based GUI application) and the [Insite pipeline](https://vrgrouprwth.github.io/insite/). The integration is based on the [TVB NEST Co-simulation Usecase 1](https://github.com/multiscale-cosim/TVB-NEST-usecase1) which serves as the foundation. This allows users of NEST Desktop to:
  - Create a spiking neural network for [NEST](https://www.nest-simulator.org/) simulator.
  - Observe the neuronal or network activity with Insite during the simulation.

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
