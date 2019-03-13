<h2>Papers by Rüdiger Franke:</h2>
<p>
<b>Title:</b> <i> Discrete-time models for control applications with FMI </i> <br />
<b>Authors:</b> <a href="../authors/author_73.html">Rüdiger Franke</a>, <a href="../authors/author_175.html">Sven Erik Mattsson</a>, <a href="../authors/author_209.html">Martin Otter</a>, <a href="../authors/author_297.html">Karl Wernersson</a>, <a href="../authors/author_207.html">Hans Olsson</a>, <a href="../authors/author_202.html">Lennart Ochel</a> and <a href="../authors/author_30.html">Torsten Blochwitz</a><br />
<b>Abstract:</b>The paper proposes an extension of FMI 2.0 for the rigorous treatment of discrete-time models. This includes the introduction of discrete-time states, the declaration of clocks in the model description and an extension of the calling interface for the external activation of clocks by an importing environment.

The synchronous discrete-time extension enables for the first time the synchronization of FMUs with the environment and with other FMUs. It specializes the existing generic event mechanism of FMI 2.0 and maps to synchronous features of Modelica.

Discrete-time FMUs are needed for the generation of controller code from functional models. This paper outlines different use cases, including a simple PI controller, feed forward control with a nonlinear inverse model and nonlinear model predictive control.

The FMI change proposal FCP-001 and the Modelica change proposal MCP-0024 describe the proposed extensions in more detail. Test implementations exist in the simulation tools Dymola and OpenModelica and in the importing optimization solver HQP. The use cases given in this paper served for further refinement of the change proposals and the test implementations.<br />
<b>Links:</b> <a href="../submissions/ecp17132507_FrankeMattssonOtterWernerssonOlssonOchelBlochwitz.pdf">Full paper</a></p>
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