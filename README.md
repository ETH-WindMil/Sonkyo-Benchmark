# Sonkyo-Benchmark

Sonkyo-Benchmark is a vibration-based study of a small-scale wind turbine (WT) blade, with the aim of establishing a benchmark
work for the Structural Health Monitoring (SHM) community. The blade under consideration is part of the Windspot 3.5kW WT, provided by Sonkyo Energy, and is tested both **experimentally** and **numerically** in healthy and damaged states, under varying environmental and operational conditions.

## Experimental Part

In the experimental part of this project, a specimen of the Windspot 3.5kW WT blade is tested in a climate chamber under controlled temperature and humidity conditions. Apart from the initially healthy state, the vibration-based assessment of the blade is carried out for two distinct families of damaged states. The first one attempts to simualte icing accretion by adhering a set of lumped masses on specific locations while the second group is focused on the investigation of cracks with varying characteristics, which are physically introduced on the structure as surface cuts. This results in 3 scenarios with added mass and a combination of 9 cracked scenarios, with each case tested under varying temperature conditions, from -15<sup>o</sup>C to +40<sup>o</sup>C using a step of 5<sup>o</sup>C. A detailed documentation of the experimental set-up, including the types of deployed sensors, the nature of excitation as well as the investigated damage scenarios and environmental variations is provided in the experimental [paper](https://github.com/ETH-WindMil/Sonkyo-Benchmark).


<details> <summary> Sensors layout </summary>
  <img src="https://github.com/ETH-WindMil/Sonkyo-Benchmark/blob/master/figures/Sensor_configuration.png">
</details>


<details> <summary> Experimental set-up </summary>
  ![alt text](https://github.com/ETH-WindMil/Sonkyo-Benchmark/blob/master/figures/Experimental_set_up-eps-converted-to.pdf)
</details>


<details><summary> Test cases </summary>

  <div style="margin-left:105px;font-size:20px">
  <table>
    <thead>
        <tr>
          <th align="center", width="90"> <sub> Case label </sub> </th>
          <th colspan=3, align="left", width="410"> <sub> Description </sub> </th>
          <th align="center", width="190"> <sub> Number of experiments </sub> </th>
        </tr>
    </thead>
    <body>
        <tr>
            <td height="2", align="center"> <sub> R </sub> </td>
            <td height="2", colspan=3> <sub> Healthy state </sub> </td>
            <td height="2", align="center"> <sub> 21 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> A </sub> </td>
            <td colspan=3> <sub> Added mass 1 x 44 gr </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> B </sub> </td>
            <td colspan=3> <sub> Added mass 2 x 44 gr </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> C </sub> </td>
            <td colspan=3> <sub> Added mass 3 x 44 gr </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> D </sub> </td>
            <td colspan=3> <sub> Crack 1: l1 = 5 cm </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> E </sub> </td>
            <td> <sub> Crack 1: l1 = 5 cm, </sub> </td> 
            <td colspan=2> <sub> Crack 2: l2 = 5 cm </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> F </sub> </td>
            <td> <sub> Crack 1: l1 = 5 cm, </sub> </td>
            <td> <sub> Crack 2: l2 = 5 cm, </sub> </td>
            <td> <sub> Crack 3: l3 = 5 cm </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> G </sub> </td>
            <td> <sub> Crack 1: l1 = 10 cm, </sub> </td>
            <td> <sub> Crack 2: l2 = 5 cm, </sub> </td>
            <td> <sub> Crack 3: l3 = 5 cm </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> H </sub> </td>
            <td> <sub> Crack 1: l1 = 10 cm, </sub> </td>
            <td> <sub> Crack 2: l2 = 10 cm, </sub> </td>
            <td> <sub> Crack 3: l3 = 5 cm </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> I </sub> </td>
            <td> <sub> Crack 1: l1 = 10 cm, </sub> </td>
            <td> <sub> Crack 2: l2 = 10 cm, </sub> </td>
            <td> <sub> Crack 3: l3 = 10 cm </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> J </sub> </td>
            <td> <sub> Crack 1: l1 = 15 cm, </sub> </td>
            <td> <sub> Crack 2: l2 = 5 cm, </sub> </td>
            <td> <sub> Crack 3: l3 = 5 cm </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> K </sub> </td>
            <td> <sub> Crack 1: l1 = 15 cm, </sub> </td>
            <td> <sub> Crack 2: l2 = 15 cm, </sub> </td>
            <td> <sub> Crack 3: l3 = 5 cm </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
        <tr>
            <td align="center"> <sub> L </sub> </td>
            <td> <sub> Crack 1: l1 = 15 cm, </sub> </td>
            <td> <sub> Crack 2: l2 = 15 cm, </sub> </td>
            <td> <sub> Crack 3: l3 = 15 cm </sub> </td>
            <td align="center"> <sub> 6 per temperature per set-up </sub> </td>
        </tr>
    </tbody>
  </table>
  </div>

</details>


## Numerical Part

In this numerical part, a Finite Element (FE) model of the Windspot 3.5kW blade is constructed with the aim of supplementing the experimental work with a physical model exposed to diverse operational conditions, loading scenarios and damage patterns that are not easily explorable and controllable in the laboratory.

A detailed description of the numerical model and the underlying assumptions, as well as the spectrum of operational conditions, the measured quantities and the wind load model is offered in the numerical [paper](https://github.com/ETH-WindMil/Sonkyo-Benchmark), which also serves as the manual for the Matlab application.

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

Ou, Y. and Tatsis, K. E. and Dertimanis, V. K. and Spiridonakos, M. D. and Chatzi, E. N. (2019) "Vibration-based monitoring of a small scale wind turbine blade under varying climate conditions: An experimental benchmark".

Tatsis, K. E. and Ou, Y. and Dertimanis, V. K. and Spiridonakos, M. D. and Chatzi, E. N. (2019) "Vibration-based monitoring of a small scale wind turbine blade under varying climate conditions: A numerical benchmark".

## Found a Bug?

If you think you've found a bug, go ahead and create a new [GitHub issue](https://help.github.com/en/articles/creating-an-issue). Be sure to include as much information as possible so that we can reproduce the bug.
