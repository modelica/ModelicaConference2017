<h2>Papers by Dan Henriksson:</h2>
<p>
<b>Title:</b> <i> Model-based Embedded Control using Rosenbrock Integration Methods </i> <br />
<b>Authors:</b> <a href="../authors/author_207.html">Hans Olsson</a>, <a href="../authors/author_175.html">Sven Erik Mattsson</a>, <a href="../authors/author_209.html">Martin Otter</a>, <a href="../authors/author_214.html">Andreas Pfeiffer</a>, <a href="../authors/author_39.html">Christoff Bürger</a> and <a href="../authors/author_107.html">Dan Henriksson</a><br />
<b>Abstract:</b>Directly generating controller code from models is important for model-based design. This paper will demonstrate how Dymola can generate embedded C-code for Modelica models – with several novel aspects, and demonstrate this for actual application examples.

Specifically the paper will show that Dymola can generate embedded C-code designed to be easy to embed, with care about minimal foot-print, traceability, and straightforward integration in embedded platforms.

The paper will focus on using Rosenbrock methods for index-1 problems (instead of the normal transformation to index-0) that allows Dymola to handle stiff systems in a way that both is theoretically sound and has an upper bound on the execution time per sample.

The stiff systems in the control system often occur due to using an inverse (simplified) model of the real plant in the controller, and the paper will also propose to extend Modelica making it more straightforward to construct an inverse model of the plant in the controller.<br />
<b>Links:</b> <a href="../submissions/ecp17132517_OlssonMattssonOtterPfeifferBurgerHenriksson.pdf">Full paper</a></p>