### *Abstract*
*This study focuses on two radioisotopes of silver, 108Ag and 110Ag, characterized by a complex decay scheme. Each isotope has two disintegration modes, the isomeric transition leading to the daughter isotope (108Ag and 110Ag, respectively) with a short half-life. This experiment will use the Geiger counter, this time to measure radiation intensity as a function of time and thereby to measure the half-life of an isotope.*

## Aim
The objective of this experiment is to measure the half-lives of two radioisotopes. In this specific experiment silver isotopes Ag-108 and 110-Ag and their rates of disintegration.

## Background
One way of looking at a nucleus is to think of it as a box in which there are many particles, each with some energy. These particles continually exchange energy and, in some cases, an individual particle may acquire sufficient energy to penetrate the walls of the box. In the case of stable nuclei, the particles cannot get out of the box and the nuclei "live" forever. in the case of unstable nuclei, a particle does eventually get out of the box. Some unstable nuclei have high, thick walls -- these are the long-lived nuclei.
Others have low, thin walls -- these are the short-lived nuclei, those that have a high probability of emitting particles and changing into different more stable nuclei.
For all radioactive isotopes one finds that the "decay” curve (i.e., the plot of the number of disintegrations per second as a function of time) appears as shown in the graph below (Radioactive Decay of Silver 108 and 110). When there are very many radioactive nuclei in a sample, then the number of disintegrations per second can be described extremely well by a probability curve. Even though each decay is a random event. The totality of events is described by a well-defined equation. In the case of nuclear decay, the equation describing the number of nuclei remaining at time, t, is an exponential decay curve: 

                                              N(t)= N_o e^((-t)/τ)
where t is the elapsed time, N(t) is the number of nuclei that have not decayed after the time t, No is the number of radioactive nuclei present at time t: 0, and r is the mean lifetime of the nucleus. Frequently, it is more convenient to express the exponential decay in terms of the "half-life" of the nucleus, the time required for half of the nuclei to disintegrate. The relationship between the half-life, T, and the mean life, is the following:

                                            T_(1/2)=(ln2)τ=0.693τ
so, we can write the decay equation in terms of T:  N(t) = N_o e^((-0.693)/T_(1/2))
Note that the clock can be started at any instant. Hence, in a time T1/2, half the starting number of nuclei will have decayed regardless of when the clock was started.
The magnitude of the decay rate, R(t)=dN/dt (number of disintegrations per second), is simply related to equation

                                        R(t)= R_o e^((-0.693t)/T_(1/2))
#### The Geiger-Muller Counter:
One of the first devices used to detect radioactivity was a Geiger-Muller tube, which is a gas filled cylinder with a very thin metal wire down its center. A voltage difference is maintained between the center wire and the cylinder. If radiation interacts with the gas in the cylinder, ionization of the gas atoms takes place. Because of the voltage difference, the electrons move toward the center wire and the positive ions move toward the outer cylinder. This is an electrical discharge producing a pulse of current which can be counted. Each pulse indicates that a nucleus has decayed and the decay rate, R(t), is measured by the number of pulses per second

#### Thermal Neutron Activation:
Some radioactive isotopes occur in nature. Some stable isotopes, when bombarded with nuclear particles of appropriate energy, may be converted to different isotopes which are unstable (radioactive). In this exercise, stable silver isotopes are bombarded by neutrons and made into radioactive isotopes of silver.
ln the room adjacent to the laboratory is located a large tub of water, the hydrogen of which absorbs neutrons. This tub of water serves as a protective shield against neutrons. in the center of the tub of water is a small amount of polonium, which is radioactive and emits alpha particles (helium nuclei). The alpha particles strike a beryllium target and produce neutrons by the following nuclear reaction:

                                  Beryllium (9)+ α(4)==> neutron (1)+Carbon(12)
When the silver foil is inserted into the tub, some of the silver nuclei will capture a neutron thus creating a new isotope which is radioactive. There are two stable isotopes of silver that can capture neutrons and become radioactive.

## Procedure
1.	Python libraries were imported (i.e. math, NumPy and matplotlib)
2.	The specified range went from the initial atomic number of the Silver isotope. So, 110 for 110-Ag and 108 for 108-Ag.
3.	Then made sure the sample fit exactly the required such as 40.
4.	Scatter plots were generated since the rate of decay was determined randomly.
5.	Then a line of best fit.
6.	Using the calculated half-life of 108-Ag, isolate and plot the contribution of 110-Ag to the overall decay curve and calculate the half-life of 108-Ag.
7.	We carried the same process for both graphs. (See code)

## Results

![Figure 2024-08-30 154951 (0)](https://github.com/user-attachments/assets/83c1877a-8bc9-4ac4-9180-acdc078894c9)

Figure of 110 Silver Decay

![Figure 2024-08-30 154951 (1)](https://github.com/user-attachments/assets/baef71c9-aae9-4ef0-9dd1-7678c5010d6f)

Figure of 108 Silver Decay

##### Comparison of the theoretical value and experimental value:

experimental values:
for Ag-110:
t_(1/2)=(ln⁡(2))/0.031 = 22.4s

for Ag-108:
t_(1/2)=(ln⁡(2))/0.0050 = 138.6s

theoretical values:
for Ag-110:
t_(1/2)=24.6s

for Ag-108:
t_(1/2)=143.4s

## Conclusion
In conclusion, during the performed calculations on how to half-live the two isotopes of silver 108-Ag and 110-Ag. It was found that the difference in the value differed by about 2.2% for the 110Silver. Which was not much different from the theoretical value. Furthermore, we discovered that for 108Silver had a slightly larger error ratio of 4.2% but was also not enough to change the outcome of the experiment.

##### Experiment questions:
Why is a neutron source stored in a wax block?
-	Storing neutron sources in wax blocks makes them easier to handle and transport. It provides a convenient way to contain and shield the source while allowing for controlled access to the neutrons when needed. This is particularly important for research and industrial applications where neutron sources are routinely used.

Why is the silver activated inside the wax block?
-	Activating silver inside a wax block provides a convenient and reliable method for performing neutron activation analysis, calibrating detectors, characterizing neutron beams, and monitoring neutron flux in various scientific and industrial applications involving neutron sources and neutron-based techniques.

How does a Geiger counter work? Give special attention to damping processes
-	A Geiger counter works by detecting ionization events in a gas-filled tube caused by incoming ionizing radiation. Damping processes, including the high voltage and quenching agents, are used to control the duration of the electron avalanche and maintain the counter's sensitivity and reliability for detecting radiation. The electrical pulses generated by these ionization events are then counted and processed to measure radiation levels.
There exists a number of radio-active units. Define them all.
    Becquerel (Bq): The Becquerel is the SI unit of radioactivity and measures the number of radioactive disintegrations (decays) per second in a radioactive substance.
    Curie (Ci): The Curie is a non-SI unit and is often used to express larger quantities of radioactivity. 1 Curie is equivalent to 3.7 x 10^10 Becquerels.
    Gray (Gy): The Gray is the SI unit of absorbed dose of ionizing radiation and measures the energy deposited by ionizing radiation per unit mass of a material.    Rad (radiation absorbed dose): The Rad is a non-SI unit and is used to measure absorbed doses of ionizing radiation. 1 Rad is equivalent to 0.01 Gray.
    Sievert (Sv): The Sievert is the SI unit of equivalent dose and effective dose. It quantifies the biological damage caused by different types of ionizing radiation. The Sievert takes into account the type of radiation and its potential harm to living tissue.
    Rem (roentgen equivalent man): The Rem is a non-SI unit used to measure equivalent dose and effective dose. 1 Rem is equivalent to 0.01 Sievert.
    Gray per second (Gy/s): This unit is used to describe the dose rate, or the rate at which radiation is delivered to a material or biological tissue.
    Activity (A): Activity measures the number of radioactive disintegrations per unit of time and is often expressed in Becquerels (Bq).
    Exposure (Roentgen, R): The Roentgen is a unit of measurement for ionization in air caused by X-rays or gamma rays.
 Absorbed dose rate (Gy/s or Rad/s): This unit describes the rate at which radiation energy is absorbed by a material.   
 Half-life (T1/2): The half-life is a time unit that measures the time it takes for half of a quantity of a radioactive substance to decay.

These units are essential for quantifying and understanding the properties of ionizing radiation, including its intensity, dose, biological effects, and safety considerations in various applications, from medical radiography and nuclear power to environmental monitoring and scientific research.

## References

Giordano, N. J., 1997. Computational physics. Upper Saddle River, NJ: Simon & Schuster/ Viacom Comany.
Paul A. Tipler & Ralph A. Llewellyn. 2012. Modern Physics. 6th ed. New York: W.H Freeman.
https://en.wikipedia.org/wiki/Isotopes_of_silver
https://www.sciencedirect.com/science/article/pii/S0969804313005502

