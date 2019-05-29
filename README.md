# Sonkyo-Benchmark

Sonkyo-Benchmark is a vibration-based study of a small-scale wind turbine (WT) blade, with the aim of establishing a benchmark
work for the Structural Health Monitoring (SHM) community. The blade is part of the Windspot 3.5kW WT, provided by Sonkyo Energy, and is tested both experimentally and numerically in healthy and damaged states, under varying environmental and operational conditions.

## Experimental Part



## Numerical Part

In this numerical part, a Finite Element (FE) model of the Windspot 3.5kW blade is constructed with the aim of supplementing the experimental work with a physical model exposed to diverse operational conditions, loading scenarios and damage patterns that are not easily explorable and controllable in the laboratory.

A detailed description of the numerical model and the underlying assumptions, as well as the spectrum of operational conditions, the measured quantities and the wind load model is offered in the [paper](https://github.com/ETH-WindMil/Sonkyo-Benchmark), which also serves as the manual for the Matlab application.

### Getting started

Clone the repository using

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

Ou, Y. and Tatsis, K. E. and Dertimanis, V. K. and Spiridonakos, M. D. and Chatzi, E. N. (2019) "Vibration-based monitoring of a small scale wind turbine blade under varying climate conditions: An experimental benchmark".

Tatsis, K. E. and Ou, Y. and Dertimanis, V. K. and Spiridonakos, M. D. and Chatzi, E. N. (2019) "Vibration-based monitoring of a small scale wind turbine blade under varying climate conditions: A numerical benchmark".
