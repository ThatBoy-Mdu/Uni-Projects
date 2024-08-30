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
