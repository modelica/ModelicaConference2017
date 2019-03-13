<h2>Session 4B: Buildings I</h2>
<p>
<b>Title:</b> <i> Coupled Simulation between CFD and Multizone Models Based on Modelica Buildings Library to Study Indoor Environment Control </i> <br />
<b>Authors:</b> <a href="../authors/author_273.html">Wei Tian</a>, <a href="../authors/author_308.html">Wangda Zuo</a>, <a href="../authors/author_249.html">Thomas Sevilla</a> and <a href="../authors/author_253.html">Michael Sohn</a><br />
<b>Abstract:</b>Multizone models are widely used in building airflow and energy performance simulations because they are often suitable for the analysis needed, and due to their fast computation speed.However, the results provided by the multizone
models are sometimes limited due to the underlying well-mixed assumption of the air in a zone (e.g., a room). For zones where this assumption is not suitable, a Computational Fluid Dynamics (CFD) models may be needed. This paper proposes a coupled simulation model between the multizone and CFD models. The model allows the simulation of a dynamic interaction between airflow and Heating, Ventilation and Air-Conditioning (HVAC) systems for buildings with stratified airflow
distribution in some of the zones. The approach is implemented using Modelica and its buildings library. In this presenation, we first discuss the
design and implementation of a data synchronization strategy between the two
models. We then show a possible validation of the implementation by comparing the simulated results with experimental data from previous research. Finally, we perform a case study by linking a Variable Air Volume (VAV) terminal box to the space in order to evaluate the capability of the coupled simulation. Finally,
further research needs are discussed at the end of the paper.<br />
<b>Links:</b> <a href="../submissions/ecp1713255_TianZuoSevillaSohn.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Co-Simulation between detailed building energy performance simulation and Modelica HVAC component models </i> <br />
<b>Authors:</b> <a href="../authors/author_196.html">Andreas Nicolai</a> and <a href="../authors/author_210.html">Anne Paepcke</a><br />
<b>Abstract:</b>We discuss the application of the FMI Co-Simulation technology to building energy performance simulation, where detailed physical building models are coupled to Modelica-based HVAC component and plant models. First, we describe the generation process of the building FMU from our stand-alone building simulation program NANDRAD and sketch out internal algorithms for FMI version 2 capabilities. Then, coupling scenarios are described and physical interface conventions are presented. Usability is addressed by automatic generation of building-model specific adapters and wrappers. The building FMU and plant FMUs are then simulated together using different Co-Simulation master algorithms. Finally, based on simulation results and performance analysis we conclude with recommendations on suitable master algorithm options and specific features of suitable building FMUs.<br />
<b>Links:</b> <a href="../submissions/ecp1713263_NicolaiPaepcke.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Aspects of FMI in Building Simulation </i> <br />
<b>Authors:</b> <a href="../authors/author_245.html">Torsten Schwan</a>, <a href="../authors/author_284.html">René Unger</a> and <a href="../authors/author_216.html">Jörg Pipiorke</a><br />
<b>Abstract:</b>Building physics and HVAC system simulation have become an important usage scenario of the Modelica modeling language and related simulation tools since the publication of first adequate libraries (Wetter, 2009). In 2010, the tool independent standard FMI was published in version 1.0. It enables the exchange of models between different simulation tools and even different modeling approaches. Although, automotive industry mainly initiated the FMI development, it can extensively benefit building simulation, too.
This paper describes four completely different applications of FMI in the building simulation environment which even extend the basic idea of simple model exchange. This includes the description of developed models as well as additionally required software components implementing the FMI standard.<br />
<b>Links:</b> <a href="../submissions/ecp1713273_SchwanUngerPipiorke.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Application of Richardson Extrapolation to the Co-Simulation of FMUs from Building Simulation </i> <br />
<b>Authors:</b> <a href="../authors/author_45.html">Christoph Clauss</a>, <a href="../authors/author_168.html">Kristin Majetta</a> and <a href="../authors/author_180.html">Richard Meyer</a><br />
<b>Abstract:</b>The application of the FMI technology gains ground in building simulation. As far as specialized tools support the FMI simulator coupling becomes an important option to simulate complex building models. Co-simulation needs a master algorithm which controls the communication time steps as well as the signal exchange between FMUs. Often a constant communication step size is applied chosen by the user. The Richardson extrapolation approach allows variable master step sizes. An extension of this approach is presented, and the method is applied to both academic test examples as well as examples of building simulation which co-simulate FMUs from NANDRAD and SimulationX. Richardson extrapolation turns out to guarantee finding an appropriate step size at the prize of downgraded performance.<br />
<b>Links:</b> <a href="../submissions/ecp1713279_ClaussMajettaMeyer.pdf">Full paper</a></p>