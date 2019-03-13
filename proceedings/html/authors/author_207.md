<h2>Papers by Hans Olsson:</h2>
<p>
<b>Title:</b> <i> Model-based Embedded Control using Rosenbrock Integration Methods </i> <br />
<b>Authors:</b> <a href="../authors/author_207.html">Hans Olsson</a>, <a href="../authors/author_175.html">Sven Erik Mattsson</a>, <a href="../authors/author_209.html">Martin Otter</a>, <a href="../authors/author_214.html">Andreas Pfeiffer</a>, <a href="../authors/author_39.html">Christoff Bürger</a> and <a href="../authors/author_107.html">Dan Henriksson</a><br />
<b>Abstract:</b>Directly generating controller code from models is important for model-based design. This paper will demonstrate how Dymola can generate embedded C-code for Modelica models – with several novel aspects, and demonstrate this for actual application examples.

Specifically the paper will show that Dymola can generate embedded C-code designed to be easy to embed, with care about minimal foot-print, traceability, and straightforward integration in embedded platforms.

The paper will focus on using Rosenbrock methods for index-1 problems (instead of the normal transformation to index-0) that allows Dymola to handle stiff systems in a way that both is theoretically sound and has an upper bound on the execution time per sample.

The stiff systems in the control system often occur due to using an inverse (simplified) model of the real plant in the controller, and the paper will also propose to extend Modelica making it more straightforward to construct an inverse model of the plant in the controller.<br />
<b>Links:</b> <a href="../submissions/ecp17132517_OlssonMattssonOtterPfeifferBurgerHenriksson.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Discrete-time models for control applications with FMI </i> <br />
<b>Authors:</b> <a href="../authors/author_73.html">Rüdiger Franke</a>, <a href="../authors/author_175.html">Sven Erik Mattsson</a>, <a href="../authors/author_209.html">Martin Otter</a>, <a href="../authors/author_297.html">Karl Wernersson</a>, <a href="../authors/author_207.html">Hans Olsson</a>, <a href="../authors/author_202.html">Lennart Ochel</a> and <a href="../authors/author_30.html">Torsten Blochwitz</a><br />
<b>Abstract:</b>The paper proposes an extension of FMI 2.0 for the rigorous treatment of discrete-time models. This includes the introduction of discrete-time states, the declaration of clocks in the model description and an extension of the calling interface for the external activation of clocks by an importing environment.

The synchronous discrete-time extension enables for the first time the synchronization of FMUs with the environment and with other FMUs. It specializes the existing generic event mechanism of FMI 2.0 and maps to synchronous features of Modelica.

Discrete-time FMUs are needed for the generation of controller code from functional models. This paper outlines different use cases, including a simple PI controller, feed forward control with a nonlinear inverse model and nonlinear model predictive control.

The FMI change proposal FCP-001 and the Modelica change proposal MCP-0024 describe the proposed extensions in more detail. Test implementations exist in the simulation tools Dymola and OpenModelica and in the importing optimization solver HQP. The use cases given in this paper served for further refinement of the change proposals and the test implementations.<br />
<b>Links:</b> <a href="../submissions/ecp17132507_FrankeMattssonOtterWernerssonOlssonOchelBlochwitz.pdf">Full paper</a></p>