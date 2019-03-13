<h2>Papers by Lennart Ochel:</h2>
<p>
<b>Title:</b> <i> Smart Processing of Function Calls to Achieve Efficient Simulation Code </i> <br />
<b>Authors:</b> <a href="../authors/author_98.html">Jan Hagemann</a>, <a href="../authors/author_266.html">Patrick Täuber</a>, <a href="../authors/author_202.html">Lennart Ochel</a> and <a href="../authors/author_10.html">Bernhard Bachmann</a><br />
<b>Abstract:</b>This paper introduces a new algorithm to increase the simulation performance of algebraic equation systems by encapsulating function calls. This avoids all unnecessary  evaluations of function calls and leads to positive structural effects. To enable the reader to reconstruct the algorithm, all four phases of the algorithm are described in detail and the complexity of them is analyzed. The overall complexity is $O(n)$, where $n$ is the number of equations. It is shown that the algorithm significantly decreases the simulation time for a wide range of physical based models.<br />
<b>Links:</b> <a href="../submissions/ecp17132581_HagemannTauberOchelBachmann.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Discrete-time models for control applications with FMI </i> <br />
<b>Authors:</b> <a href="../authors/author_73.html">Rüdiger Franke</a>, <a href="../authors/author_175.html">Sven Erik Mattsson</a>, <a href="../authors/author_209.html">Martin Otter</a>, <a href="../authors/author_297.html">Karl Wernersson</a>, <a href="../authors/author_207.html">Hans Olsson</a>, <a href="../authors/author_202.html">Lennart Ochel</a> and <a href="../authors/author_30.html">Torsten Blochwitz</a><br />
<b>Abstract:</b>The paper proposes an extension of FMI 2.0 for the rigorous treatment of discrete-time models. This includes the introduction of discrete-time states, the declaration of clocks in the model description and an extension of the calling interface for the external activation of clocks by an importing environment.

The synchronous discrete-time extension enables for the first time the synchronization of FMUs with the environment and with other FMUs. It specializes the existing generic event mechanism of FMI 2.0 and maps to synchronous features of Modelica.

Discrete-time FMUs are needed for the generation of controller code from functional models. This paper outlines different use cases, including a simple PI controller, feed forward control with a nonlinear inverse model and nonlinear model predictive control.

The FMI change proposal FCP-001 and the Modelica change proposal MCP-0024 describe the proposed extensions in more detail. Test implementations exist in the simulation tools Dymola and OpenModelica and in the importing optimization solver HQP. The use cases given in this paper served for further refinement of the change proposals and the test implementations.<br />
<b>Links:</b> <a href="../submissions/ecp17132507_FrankeMattssonOtterWernerssonOlssonOchelBlochwitz.pdf">Full paper</a></p>