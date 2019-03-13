<h2>Papers by Martin Otter:</h2>
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
<hr />
<p>
<b>Title:</b> <i> Innovations for Future Modelica </i> <br />
<b>Authors:</b> <a href="../authors/author_65.html">Hilding Elmqvist</a>, <a href="../authors/author_106.html">Toivo Henningsson</a> and <a href="../authors/author_209.html">Martin Otter</a><br />
<b>Abstract:</b>This paper discusses language innovations for future Modelica versions, on the one hand for generally applicable language elements, and on the other hand to improve modeling of multibody systems with contacts, and media modeling. In a companion paper new algorithms are proposed to handle much larger models than can be treated today. All these innovations are developed and evaluated with the experimental modeling and simulation environment Modia. Modia is based on Julia, a powerful programming language with strong focus on scientific computing, meta-programming and just-in-time compilation that allows very fast development. The modeling language is directly defined and implemented with Julia’s meta-programming constructs and is designed tightly together with the symbolic and numeric algorithms. This approach is very well suited for innovation and experimenting with evolutions of modeling capabilities in Modelica.<br />
<b>Links:</b> <a href="../submissions/ecp17132693_ElmqvistHenningssonOtter.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Transformation of Differential Algebraic Array Equations to Index One Form </i> <br />
<b>Authors:</b> <a href="../authors/author_209.html">Martin Otter</a> and <a href="../authors/author_65.html">Hilding Elmqvist</a><br />
<b>Abstract:</b>Several new algorithms are proposed that in effect transform DAEs (Differential Algebraic Equations) to a special index one form that can be simulated with standard DAE integrators. The transformation to this form is performed without solving linear and/or nonlinear equation systems, the sparsity of the equations is kept, and array equations remain array equations or differentiated versions of them. Furthermore, certain DAEs can be handled where structural index reduction methods fail. It is expected that these new algorithms will help to treat large Modelica models of any index in a better way as it is currently possible. The algorithms have been evaluated and tested in the experimental simulation environment Modia that is implemented with the Julia programming language.<br />
<b>Links:</b> <a href="../submissions/ecp17132565_OtterElmqvist.pdf">Full paper</a></p>