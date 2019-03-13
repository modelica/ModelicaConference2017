<h2>Papers by Tomas Härdin:</h2>
<p>
<b>Title:</b> <i> FMI Go! A simulation runtime environment with a client server   architecture over multiple protocols </i> <br />
<b>Authors:</b> <a href="../authors/author_150.html">Claude Lacoursière</a> and <a href="../authors/author_101.html">Tomas Härdin</a><br />
<b>Abstract:</b>We present a software infrastructure to perform distributed simulations
  with Functional Mockup Interface (FMI) compatible components.
  Distribution is achieved done by mapping the FMI API to a communication
  protocol with current support for both TCP/IP and MPI.  This is a
  client-server architecture where the client is the global simulation
  stepper and the servers are the simulation modules.  The client contains
  several time stepping algorithms, root finding for cases involving loops,
  and support for asynchronous data exchange with ``monitors'' and
  ``observers'' which only consume data.  The servers provide support for
  numerical directional derivatives, filtering, and interpolation.
  Extensive support is provided for the System Specification and
  Parameterization (SSP), an emerging standard aimed at supporting the FMI.

  The software is open source with a permissive license and designed to be
  used inside simulation environments and platforms with user interfaces.
  The focus being strictly on the mathematical and runtime aspect of FMI
  based simulations.<br />
<b>Links:</b> <a href="../submissions/ecp17132653_LacoursiereHardin.pdf">Full paper</a></p>