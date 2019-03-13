<h2>Session 4C: Process & Chemical Engineering</h2>
<p>
<b>Title:</b> <i> Development of a Thermodynamic Engine in OpenModelica </i> <br />
<b>Authors:</b> <a href="../authors/author_122.html">Rahul Jain</a>, <a href="../authors/author_184.html">Kannan Moudgalya</a>, <a href="../authors/author_76.html">Peter Fritzson</a> and <a href="../authors/author_221.html">Adrian Pop</a><br />
<b>Abstract:</b>OpenModelica, an open source equation oriented modeling environment
  for steady state and dynamic simulation, lacks good chemical
  engineering support.  This problem is addressed by making available
  in different ways the thermodynamic library Chemsep that comes with
  DWSIM, an open source sequential modular steady state simulator.
  Only slow speeds could be achieved through a Python-C API based
  interface connecting OpenModelica with the thermodynamic library.  A
  socket programming based interface helps achieve faster speeds.
  Best results have been achieved by porting the thermodynamic library
  and the calculation routines to OpenModelica, due to two reasons:
  (1) thermodynamic equations are solved simultaneously with mass and
  energy balances (2) overheads in calling the external routines of
  DWSIM are eliminated.  Performances of the above mentioned three
  approaches have been validated with steady state and dynamic
  simulations.  Benzene - toluene separation, methanol - ethanol -
  water distillation, and steam distillation of an n-octane - n-decane
  mixture, have been carried out through these simulations.  This work
  makes available a powerful simulation platform to the chemical
  engineering.<br />
<b>Links:</b> <a href="../submissions/ecp1713289_JainMoudgalyaFritzsonPop.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Integrated Process and Molecular Design with Modelica Using Continuous-Molecular Targeting </i> <br />
<b>Authors:</b> <a href="../authors/author_84.html">Christoph Udo Gertig</a>, <a href="../authors/author_276.html">Dominik Tillmanns</a>, <a href="../authors/author_239.html">Johannes Schilling</a>, <a href="../authors/author_18.html">Uwe Bau</a>, <a href="../authors/author_151.html">Franz Lanzerath</a>, <a href="../authors/author_96.html">Joachim Gross</a> and <a href="../authors/author_14.html">André Bardow</a><br />
<b>Abstract:</b>The performance of many chemical and energy con-version processes depends on the choice of the mole-cules used, e.g. as solvents or working fluids. To cap-ture the complex relations between the properties of the molecules used and the process conditions, the selection of suitable molecules should be directly integrated into process design. Solving the resulting challenging integrated design problem is enabled by the Continous-Molecular Targeting – Computer-Aided Molecular Design (CoMT-CAMD) approach. Here, the combinatorial complexity of the molecular decisions is avoided by relaxing molecular parameters in a physically-based thermodynamic model. So far, implementations of CoMT-CAMD were based on procedural programming languages. This impedes reusability and the investigation of process variants as well as the design of complex processes. In order to overcome these shortcomings, we implement the CoMT-CAMD approach based on object-oriented process modeling and thus enable the integrated process and molecular design with Modelica. The resulting approach is demonstrated for the design of a process and the working fluid for a geothermal Organic Rankine Cycle application.<br />
<b>Links:</b> <a href="../submissions/ecp17132101_GertigTillmannsSchillingBauLanzerathGrossBardow.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Dynamic Simulations of the Post-combustion CO2 Capture System of a Combined Cycle Power Plant </i> <br />
<b>Authors:</b> <a href="../authors/author_182.html">Rubén Mocholí Montañés</a> and <a href="../authors/author_200.html">Lars Olof Nord</a><br />
<b>Abstract:</b>Dynamic process models of the capture unit of a 600 MW combined cycle power plant with post-combustion CO2 capture were developed in the Modelica language. The process models were utilized to understand the transient response of the capture unit when the plant was initially operated at steady-state conditions at different power plant’s loads. Simulations to characterize the open-loop response of main process variables of the process to step-change disturbances in flue gas mass flow rate, solvent circulation mass flow rate and reboiler duty were performed. It was found that the plant was slower when operated at lower loads, i.e., it required longer total stabilization times for the most relevant variables of the process. Simulations revealed that the PCC unit responded significantly faster to an increase in exhaust gas mass flow rate than to a reduction in exhaust gas mas flow rate.<br />
<b>Links:</b> <a href="../submissions/ecp17132111_MocholimontanesNord.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Optimizing the start-up process of post-combustion capture plants by varying the solvent flow rate </i> <br />
<b>Authors:</b> <a href="../authors/author_170.html">Thomas Marx-Schubach</a> and <a href="../authors/author_240.html">Gerhard Schmitz</a><br />
<b>Abstract:</b>This paper presents an optimization of the start-up process of a post-combustion carbon capture plant (PCC-plant) by varying the solvent flow rate. In a first optimization run the start-up time is minimized. In a second optimization run the overall carbon capture rate during the start-up process is maximized. The results show the great potential of the optimization, as the start-up time can be reduced from t=4650 seconds in the reference case to t=2840 seconds in the optimized scenario.<br />
<b>Links:</b> <a href="../submissions/ecp17132121_MarxschubachSchmitz.pdf">Full paper</a></p>