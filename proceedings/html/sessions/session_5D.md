<h2>Session 5D: Control Systems II</h2>
<p>
<b>Title:</b> <i> From system model to optimal control - A tool chain for the efficient solution of optimal control problems </i> <br />
<b>Authors:</b> <a href="../authors/author_90.html">Manuel Gräber</a>, <a href="../authors/author_75.html">Jörg Fritzsche</a> and <a href="../authors/author_268.html">Wilhelm Tegethoff</a><br />
<b>Abstract:</b>Based on a specific application example - the thermal management system of an internal combustion engine - a toolchain is presented for formulating and solving of nonlinear optimal control problems. Starting from graphical modeling of the thermal management system with the Modelica library TIL, the model is exported to the standardized model exchange format Functional Mock-up Interface (FMI). Furthermore, it is imported to the optimal control software package MUSCOD-II. Python is used as scripting language for the problem formulation, the numerical solution and the processing of results. By using FMI as an interface, models from any simulation and modeling tools can be used if there is an FMI model export and the models fulfill certain mathematical requirements (smoothness).<br />
<b>Links:</b> <a href="../submissions/ecp17132249_GraberFritzscheTegethoff.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Nonlinear Model Predictive Control of a Thermal Management System for Electrified Vehicles using FMI </i> <br />
<b>Authors:</b> <a href="../authors/author_71.html">Torben Fischer</a>, <a href="../authors/author_143.html">Tom Kraus</a>, <a href="../authors/author_138.html">Christian Kirches</a> and <a href="../authors/author_83.html">Frank Gauterin</a><br />
<b>Abstract:</b>Energy-efficient thermal management systems for Emobility
help to decrease energy consumption and increase
range. Due to transient external conditions and the
increasing system complexity, optimization-based control
approaches are required in order to harness the full potential
of such systems. In (Fischer et al., 11th Int. Modelica
Conf, 2015), we have presented a model-based development
cycle for a thermal management system in Emobility
to this end. In this article, we build upon this
work to describe the use of this model within a nonlinear
model predictive control (NMPC) approach. The main
benefits of using an advanced optimization-based control
system in this application are a) the ability to control
the battery temperature and the cabin temperature simultaneously,
b) the increased energy efficiency achieved
by exploiting the predictive character of the optimizationbased
control approach, c) the possibility to include operational
limits as constraints in the optimization problems
and d) the fast reaction to disturbances or model parameter
changes. We evaluate the merit of the proposed advanced
control system by way of a comparison to conventional
PID controller.<br />
<b>Links:</b> <a href="../submissions/ecp17132255_FischerKrausKirchesGauterin.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Defining and Solving Hybrid Optimal Control Problems with Higher Index DAEs </i> <br />
<b>Authors:</b> <a href="../authors/author_222.html">Radoslaw Pytlak</a>, <a href="../authors/author_259.html">Damian Suski</a>, <a href="../authors/author_264.html">Tomasz Tarnawski</a> and <a href="../authors/author_305.html">Tomasz Zawadzki</a><br />
<b>Abstract:</b>The paper deals with optimal control problems defined
for hybrid systems described by higher index DAEs. We
present a prototype solution that supports the whole process
from defining such problem to solving it and presenting
results. Problem’s definition is done with Dynamic
Optimization Modeling Language (DOML) which
is based directly on Modelica. The proposed numerical
procedure for solving the problems of interest has the following
features: 1) it is based on the appropriately defined
adjoint equations formulated for the discretized equations
being the result of the numerical integration of system
equations by an implicit Runge–Kutta method; 2) initialization
for higher index DAEs is performed with the help
of Pantelides’ algorithm; 3) it does not require the system
to be transformed to ODEs (through differentiation of
some algebraic equations).
The paper presents numerical examples related to hybrid
systems described by index three DAEs, showing the
validity of the proposed approach. All software components
needed to carry out the computations, i.e. the code
editor, compiler, numerical libraries and GUI for presenting
results are prepared as parts of a combined platform:
Interactive Dynamic Optimization Server (IDOS).<br />
<b>Links:</b> <a href="../submissions/ecp17132265_PytlakSuskiTarnawskiZawadzki.pdf">Full paper</a></p>