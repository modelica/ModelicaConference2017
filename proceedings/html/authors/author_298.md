<h2>Papers by Michael Wetter:</h2>
<p>
<b>Title:</b> <i> Modelling of Heat Pumps with Calibrated Parameters Based on Manufacturer Data </i> <br />
<b>Authors:</b> <a href="../authors/author_44.html">Massimo Cimmino</a> and <a href="../authors/author_298.html">Michael Wetter</a><br />
<b>Abstract:</b>A Modelica model for the simulation of heat pumps is presented. The model uses a simplified vapor compression cycle with only five refrigerant states. Parameters to the model are evaluated using an optimization procedure to minimize the differences between the model predicted heating capacities and power input and those provided in the manufacturer technical data. The optimization process is done from a Python implementation of the heat pump model.
The model is first tested by verifying that calibration from performance data generated by the heat pump model results in the same parameters as the ones used in the generation of the performance data. In the presented example, calibrated parameters were found close to the original parameters used to generate the data, except for the evaporator heat transfer coefficient for which the model was found not to be very sensitive. In a second example, the model is calibrated against manufacturer data. The heating capacities and power input calculated from the calibrated model are within 2.7% and 4.7% of the manufacturer data, respectively. Finally, the computational performance of the model is tested in a system simulation of a hydronic heating system. The simulation using the presented heat pump model was executed in 152 seconds, compared to 140 seconds for the same system using a simple boiler model.<br />
<b>Links:</b> <a href="../submissions/ecp17132219_CimminoWetter.pdf">Full paper</a></p>