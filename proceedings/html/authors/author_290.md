<h2>Papers by Andrea Walther:</h2>
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