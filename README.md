# Sonkyo-Benchmark

Sonkyo-Benchmark is a vibration-based study of a small-scale wind turbine (WT) blade, with the aim of establishing a benchmark
work for the Structural Health Monitoring (SHM) community. The blade under consideration is part of the Windspot 3.5kW WT, provided by Sonkyo Energy, and is tested both **experimentally** and **numerically** in healthy and damaged states, under varying environmental and operational conditions.

## Part I - Experimental study

In the experimental part of this project, a specimen of the Windspot 3.5kW WT blade is tested in a climate chamber under controlled temperature and humidity conditions. The vibration-based assessment of the blade is carried out for a number of damaged states under varying temperature conditions between -15<sup>o</sup>C to +40<sup>o</sup>C. A detailed documentation of the experimental set-up, including the types of deployed sensors, the nature of excitation as well as the investigated damage scenarios and environmental variations is provided in the experimental [paper](https://doi.org/10.1002/stc.2660), while the entire dataset is made available via [Zenodo](https://zenodo.org/record/3229743#.XR-VRHUzbwo).

## Part II - Numerical study

In this numerical part, a Finite Element (FE) model of the Windspot 3.5kW blade is constructed with the aim of supplementing the experimental work with a physical model exposed to diverse operational conditions, loading scenarios and damage patterns that are not easily explorable and controllable in the laboratory.

A detailed description of the numerical model and the underlying assumptions, as well as the spectrum of operational conditions, the measured quantities and the wind load model is offered in the numerical [paper](https://doi.org/10.1002/stc.2734), which also serves as the manual for the Matlab application.

### Getting started

Pull down a copy by downloading or cloning the repository

```
git clone https://github.com/ETH-WindMil/Sonkyo-Benchmark ~/Sonkyo-Benchmark
```

### Results

Upon submission and completion of a job named *Job_name*, the following result files are generated, depending on the type of analysis:

**Modal analysis**

<div style="margin-left:55px">
<table>
  <thead>
      <tr>
        <th align="left", width="160">File</th>
        <th align="left", width="160">Field</th>
        <th align="left", width="400">Description</th>
      </tr>
  </thead>
  <body>
      <tr>
          <td rowspan=2, valign="top"> <i>Job_name</i>.mat </td>
          <td> frequencies </td>
          <td> The system natural frequencies in Hz. </td>
      </tr>
      <tr>
          <td> modes </td>
          <td> The corresponding mode shapes at output locations. </td>
      </tr>
  </tbody>
</table>
</div>

**Dynamic analysis**

<div style="margin-left:55px">
<table>
  <thead>
      <tr>
        <th align="left", width="160">File</th>
        <th align="left", width="160">Field</th>
        <th align="left", width="400">Description</th>
      </tr>
  </thead>
  <body>
      <tr>
          <td rowspan=4, valign="top"> <i>Job_name</i>.mat </td>
          <td> time </td>
          <td> The time instants at which solution is obtained. </td>
      </tr>
      <tr>
          <td> strains </td>
          <td> The strain time history at output locations. </td>
      </tr>
      <tr>
          <td> displacements </td>
          <td> The displacement time history at output locations. </td>
      </tr>
      <tr>
          <td> accelerations </td>
          <td> The acceleration time history at output locations. </td>
      </tr>
  </tbody>
</table>
</div>


## Cite as

Ou, Y. and Tatsis, K. E. and Dertimanis, V. K. and Spiridonakos, M. D. and Chatzi, E. N. "Vibration-based monitoring of a small scale wind turbine blade under varying climate conditions. Part I: An experimental benchmark". Struct Control Health Monit. 2021; 28:e2660. https://doi.org/10.1002/stc.2660

Tatsis, K. E. and Ou, Y. and Dertimanis, V. K. and Spiridonakos, M. D. and Chatzi, E. N. "Vibration-based monitoring of a small scale wind turbine blade under varying climate and operational conditions. Part II: A numerical benchmark". Struct Control Health Monit. 2021; 28:e2734. https://doi.org/10.1002/stc.2734

## About current version

The current version 0.2 contains only the user-interface which is not connected to the numerical model. Version 1.0 is to be released soon and will contain the final numerical model, as documented in Part II.

## Found a Bug?

If you think you've found a bug, go ahead and create a new [GitHub issue](https://help.github.com/en/articles/creating-an-issue). Be sure to include as much information as possible so that we can reproduce the bug.
