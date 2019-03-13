<h2>Session 9B: Numerical & Symbolic Methods</h2>
<p>
<b>Title:</b> <i> Solving large-scale Modelica models: new approaches and experimental results using OpenModelica </i> <br />
<b>Authors:</b> <a href="../authors/author_33.html">Willi Braun</a>, <a href="../authors/author_41.html">Francesco Casella</a> and <a href="../authors/author_10.html">Bernhard Bachmann</a><br />
<b>Abstract:</b>Modelica-based modeling and simulation is becoming increasingly important for the development of high quality engineering products. Therefore, the system size of interest in a Modelica-based simulation is continously increasing and the traditional way of generating simulation code, e.g. involving symbolic transformations like matching, sorting, and tearing, must be adapted to this situation.
This paper describes recently implemented sparse solver techniques in OpenModelica in order to efficiently compile and simulate large-scale Modelica models. A proof
of concept is given by evaluating the performance of selected benchmark problems.<br />
<b>Links:</b> <a href="../submissions/ecp17132557_BraunCasellaBachmann.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Transformation of Differential Algebraic Array Equations to Index One Form </i> <br />
<b>Authors:</b> <a href="../authors/author_209.html">Martin Otter</a> and <a href="../authors/author_65.html">Hilding Elmqvist</a><br />
<b>Abstract:</b>Several new algorithms are proposed that in effect transform DAEs (Differential Algebraic Equations) to a special index one form that can be simulated with standard DAE integrators. The transformation to this form is performed without solving linear and/or nonlinear equation systems, the sparsity of the equations is kept, and array equations remain array equations or differentiated versions of them. Furthermore, certain DAEs can be handled where structural index reduction methods fail. It is expected that these new algorithms will help to treat large Modelica models of any index in a better way as it is currently possible. The algorithms have been evaluated and tested in the experimental simulation environment Modia that is implemented with the Julia programming language.<br />
<b>Links:</b> <a href="../submissions/ecp17132565_OtterElmqvist.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Smart Processing of Function Calls to Achieve Efficient Simulation Code </i> <br />
<b>Authors:</b> <a href="../authors/author_98.html">Jan Hagemann</a>, <a href="../authors/author_266.html">Patrick Täuber</a>, <a href="../authors/author_202.html">Lennart Ochel</a> and <a href="../authors/author_10.html">Bernhard Bachmann</a><br />
<b>Abstract:</b>This paper introduces a new algorithm to increase the simulation performance of algebraic equation systems by encapsulating function calls. This avoids all unnecessary  evaluations of function calls and leads to positive structural effects. To enable the reader to reconstruct the algorithm, all four phases of the algorithm are described in detail and the complexity of them is analyzed. The overall complexity is $O(n)$, where $n$ is the number of equations. It is shown that the algorithm significantly decreases the simulation time for a wide range of physical based models.<br />
<b>Links:</b> <a href="../submissions/ecp17132581_HagemannTauberOchelBachmann.pdf">Full paper</a></p>