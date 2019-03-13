<h2>Papers by Bernhard Bachmann:</h2>
<p>
<b>Title:</b> <i> Smart Processing of Function Calls to Achieve Efficient Simulation Code </i> <br />
<b>Authors:</b> <a href="../authors/author_98.html">Jan Hagemann</a>, <a href="../authors/author_266.html">Patrick Täuber</a>, <a href="../authors/author_202.html">Lennart Ochel</a> and <a href="../authors/author_10.html">Bernhard Bachmann</a><br />
<b>Abstract:</b>This paper introduces a new algorithm to increase the simulation performance of algebraic equation systems by encapsulating function calls. This avoids all unnecessary  evaluations of function calls and leads to positive structural effects. To enable the reader to reconstruct the algorithm, all four phases of the algorithm are described in detail and the complexity of them is analyzed. The overall complexity is $O(n)$, where $n$ is the number of equations. It is shown that the algorithm significantly decreases the simulation time for a wide range of physical based models.<br />
<b>Links:</b> <a href="../submissions/ecp17132581_HagemannTauberOchelBachmann.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Towards Adjoint and Directional Derivatives in FMI utilizing ADOL-C within OpenModelica </i> <br />
<b>Authors:</b> <a href="../authors/author_33.html">Willi Braun</a>, <a href="../authors/author_148.html">Kshitij Kulshreshtha</a>, <a href="../authors/author_73.html">Rüdiger Franke</a>, <a href="../authors/author_10.html">Bernhard Bachmann</a> and <a href="../authors/author_290.html">Andrea Walther</a><br />
<b>Abstract:</b>Algorithmic differentiation has proven to be an efficient method for
evaluating derivative information for implementations of mathematical
functions. In the context of the Functional Mockup Interface (FMI)
the reverse mode of algorithmic differentiation shows immense promise.

FMI is increasingly used for model-based applications, such as parameter
estimation or optimal control. The paper motivates the exploitation of
algorithmic differentiation and proposes an extension of FMI for the
evaluation of adjoint directional derivatives.

Attempts to interface algorithmic differentiation libraries with Modelica
tools have been made. Instead of generating code for the target language
which is instrumented with algorithmic differentiation library API and then
compiled, in this new approach the intermediate representation used by the
library is generated directly. This avoids compilation of the target language that often
takes a large fraction of the overall simulation time.
It also avoids model execution in order to create such an internal
representation at runtime. The initial results are presented here.<br />
<b>Links:</b> <a href="../submissions/ecp17132363_BraunKulshreshthaFrankeBachmannWalther.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Solving large-scale Modelica models: new approaches and experimental results using OpenModelica </i> <br />
<b>Authors:</b> <a href="../authors/author_33.html">Willi Braun</a>, <a href="../authors/author_41.html">Francesco Casella</a> and <a href="../authors/author_10.html">Bernhard Bachmann</a><br />
<b>Abstract:</b>Modelica-based modeling and simulation is becoming increasingly important for the development of high quality engineering products. Therefore, the system size of interest in a Modelica-based simulation is continously increasing and the traditional way of generating simulation code, e.g. involving symbolic transformations like matching, sorting, and tearing, must be adapted to this situation.
This paper describes recently implemented sparse solver techniques in OpenModelica in order to efficiently compile and simulate large-scale Modelica models. A proof
of concept is given by evaluating the performance of selected benchmark problems.<br />
<b>Links:</b> <a href="../submissions/ecp17132557_BraunCasellaBachmann.pdf">Full paper</a></p>