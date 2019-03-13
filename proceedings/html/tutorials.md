<h2>List of Tutorials</h2>
<div>
<ol><li>
<p><strong>Title:&nbsp;</strong> Test-Driven Library Development: Best practices and usage of Modelica testing solutions including the novel Testing Library</p>
<p><strong>Presenters:</strong> Dassault Systèmes</p>
<p><strong>Abstract<em>:</em></strong><em>&nbsp;This tutorial gives an introduction to existing Modelica testing solutions including the novel Testing Library of Dassault Systèmes. It is shown in detail how tests for Modelica classes can be crated and run.</em></p>
<p><em>Due to the component based and object oriented modelling approach Modelica classes typically depend on a big number of other classes. Hence it is hard to ensure that no unwanted changes or errors are introduced anywhere if a class is modified. Also the upgrade to a new library or tool version is a critical process: developers must check if their classes behave like they did before the upgrade was performed.  Running unit tests helps to discover such problems and they gained wide acceptance in software development, like junit for Java programming or nose and py.test in python. We will discuss how the concept of unit tests can be applied in the Modelica world and show which possibilities exist to create and identify tests and what effort is needed to maintain the test models.</em></p>
<p><em>The Modelica landscape already has a big number of testing solutions to offer, so we will have a look on the different implementations and analyse their capabilities. The new Testing library from Dassault Systèmes will also be presented in the tutorial. It contains the required components to create test models and to generate reference results. The library was designed such that test models can be created and maintained with low effort - all within Dymola. Finally it is shown how the Testing library can be used to run the tests periodically using Python and Jenkins.</em></p>
<p><em>In the hands-on session the course participants can implement their own test model with the Testing Library. As it is not released yet, a copy of the library with a time limited license will be handed out.</em></p>
<p><em>At the end of the workshop the participants should be able to create test models with the testing solution that is tailored to their needs.</em></p>
<p><em><br />
</em></p>
</li>
  <li>
<p><strong>Title:&nbsp;</strong>Multilevel modelling using the Actuator Library and systematical introduction of faults using the FaultTriggering Library</p>
<p><strong>Presenters:</strong> DLR</p>
<p><strong>Abstract<em>:</em></strong><em>&nbsp;The tutorial is aimed at advanced Modelica users. It introduces attendees to the concept of multi-level modelling, the Actuator Library and the open source FaultTriggering Library. An example design of an Electromechanical Actuator (EMA) will be created. This creation involves all steps of the model design process, from pre-design up to detailed design stage.</em></p>
<p><em>For this multi-level modelling approach, Modelicas object orientation features will be extensively used to create a model which can grow with the modelling needs of the user. The design will be started from a simple representation of an actuator using ideal transformers. Gradually, more complex models will be introduced to include the nonlinear behavior of the components (e.g. backlash, load dependent friction and motor saturation). As last step, non-nominal behavior in case of faults will be introduced. The modelling of such faulty behavior plays, among others, an important role in the development of Health Monitoring (HM) and Fault Detection (FD) functions. The FaultTriggering library will be used to systematically introduce a fault in a bearing model. Finally, a model with multiple faults will be analyzed.</em></p>
<p>&nbsp;  </p>
  </li>
  <li>
<p><strong>Title:&nbsp;</strong>Modeling of a Mobile Inverted Pendulum System (MIPS)</p>
<p><strong>Presenter:</strong>&nbsp;ESI</p>
<p><strong>Abstract<em>:</em></strong><em>&nbsp;Powerful, miniaturized and cheap single board computers such as BeagleBone, Raspberry Pi® or Arduino are increasingly utilized in education, for realization of hobby projects or as prototyping hardware for embedded systems. During this tutorial the possibility will be shown how SimulationX can be beneficially used for the development of systems with such hardware. A self-balancing two-wheeled vehicle was developed and built as a demonstrator for model based development. This mechatronic system shall meet the following requirements:</em></p>
<p><em>The proposed tutorial &ldquo;Modeling of a Mobile Inverted Pendulum System&rdquo; is both listening, modeling and hopefully learning. The tutorial is based on the V-cycle of the development process, that is starting from requirements, component design, system integration and prototyping resulting in virtual and real testing via several design iterations. It features hands-on-experience as you will get and use SimulationX (Windows 7 or newer required), perform modeling tasks based on the provided templates and libraries and watch the real vehicle in action. The real benefit for you is to see the design and development process in action where Modelica is the method of choice. <a title="ESI tutorial abstract" href="https://modelica.org/events/modelica2017/partners/Abstract.pdf">Please check the PDF</a> that includes comprehensive figures for a better understanding of the objective of the tutorial.</em><br>
  <em><br />
  <br />
  </em></p>
  </li>
  <li>
<p><strong>Title: </strong>Cyber-Physical Modeling of Electrical Power Systems using OpenIPSL and OpenModelica</p>
<p><strong>Presenters:</strong> KTH</p>
<p><strong>Abstract<em>:</em></strong> <em>The Modelica language, being standardized and equation-based, has proven valuable for the for model exchange, simulation and even for model validation applications in actual power systems. These important features have been now recognized by the European Network of Transmission System Operators, which have adopted the Modelica language for dynamic model exchange in the Common Grid Model Exchange Standard (v2.5, Annex F).</em></p>
<p><em>Following previous FP7 project results, within the ITEA 3 openCPS project, the presenters have continued the efforts of using the Modelica language for power system modeling and simulation, by developing and maintaining the OpenIPSL library: <a href="https://github.com/SmarTS-Lab/OpenIPSL" target="_blank">https://github.com/SmarTS-Lab/OpenIPSL</a></em></p>
<p><em>The tutorial first gives an overview of the origins of the openIPSL and it&rsquo;s models, it contrasts it against typical power system tools, and an introduction the OpenIPSL library.</em></p>
<p><em>The new project features that help in the OpenIPSL maintenance (use of continuous integration, regression testing, documentation, etc.) are also described.</em></p>
<p><em>The second part of the tutorial consists of working with three examples, we assume you have very little experience with OpenModelica and the Modelica language, so detailed instructions are provided.</em></p>
<p><em>In the first example, you will work setting up a power system from scratch and performing simulations using OpenModelica and the OpenIPSL. The second example consists on performing linear analysis and implementing a power system stabilizer for the model of example one.Finally, in the third example, you will perform simulations of a typical IEEE 9-Bus power systems and perform a simple analysis of results.</em></p>
<p><em>Youtube Videos! See an overview of OpenIPSL here: <a href="https://youtu.be/H6h9s4iMzA8?t=3616" target="_blank">https://youtu.be/H6h9s4iMzA8?t=3616</a></em></p>
<p><br />
  <br />
</p>
</li><li><strong>Title:&nbsp;</strong>Optimized control and operation of coupled energy systems
  <p><strong>Presenters:</strong>&nbsp;Modelon</p>
<p><strong>Abstract<em>:</em></strong><em>&nbsp;In this workshop, new co-simulation and optimization tools applied to interacting energy systems will be presented through hands on case studies and examples.</em></p>
<p><em>Energy production has become increasingly diverse with the rise of renewable generation (wind, solar, hydro, geothermal, etc.) in combination with traditional generation approaches. With an increasing focus on efficiency, energy consumption is also undergoing change in terms of the spatial and temporal aspects of energy usage (i.e. load shifting and storage, distributed and co-generation, demand limiting consumption, etc.). These factors present challenges to modeling, simulation, control and optimization. In this tutorial, we will discuss new tools and techniques to address them.</em></p>
<p><em>Several institutions participating in the IEA EBC Annex 60 are developing models for energy systems, these libraries span different technological domains and adopt various paradigms in terms of library structure and interfaces. Using co-simulation via the open source Modelon PyFMI package, examples of techniques to simulate the interaction between energy producers (power generation) and consumers (i.e. a commercial building from the LBL library) will be presented. Optimization of the control of these interconnections (amount of energy flow and timing) will be demonstrated using open source python-based tools.</em></p>
<p><em>Accurate model predictions are needed for optimization of energy systems and one section of the tutorial will be devoted to parameter estimation and tuning using dynamic optimization techniques. Once assimilated to data, dynamic optimization will again be used to demonstrate optimal control of a large chiller system.</em></p>
<p><em>The tutorial leverages new features in JModelica.org, an open source tool for simulation and optimization of Modelica models.</em></p>
<p><em><br /><br /></em></p>
</li>
<li>
<p><strong>Title:&nbsp;</strong>Introduction to Modeling, Simulation, Debugging and Optimization with Modelica and OpenModelica</p>
<p><strong>Presenter:</strong>&nbsp;Peter Fritzson and Bernhard Thiele, Linköping University, Sweden; Bernhard Bachmann and Willi Braun, FH Bielefeld, Germany</p>
<p><strong>Abstract<em>:</em></strong><em>&nbsp;This tutorial gives an introduction to the Modelica language, the OpenModelica environment, and an overview of modeling and simulation in a number of application areas. Moreover, an introduction to debugging Modelica  models will be given, and an introduction of model-based dynamic optimization with OpenModelica including  goal functions, constraints, convergence. Some advanced features of OpenModelica will be demonstrated,  including clocked synchronous support, real-time embedded code generation, enhanced OMPython. A number of hands-on exercises will be done during the tutorial, both graphical modeling using the Modelica standard library and textual modeling. Bring your laptop for exercises. </em></p>
<p><em>Approximate Schedule: </em></p>
<p><em><strong>1.</strong> Modelica background. <br>
    <strong>2.</strong> Graphical modeling and simulation introductory exercise. <strong><br>
  3. </strong>Overview of the OpenModelica environment. <strong><br>
  4. </strong>Hands-on model debugging exercise. <strong><br>
  5. </strong>Modelica language concepts.<br>
  <strong>6. </strong>Hands-on textual modeling. <br>
  <strong>7. </strong>Modelica discrete event, hybrid, clocked synchronous, state machine.<br>
  <strong>8. </strong>Small discrete-event and small state machine exercise. <br>
  <strong>9. </strong>Modelica concepts of components, connectors and connections <br>
  <strong>10.  </strong>Short overview of the Modelica standard library. <strong><br>
  11. </strong>More advanced Graphical modeling exercise. <strong><br>
  12. </strong>Model-based dynamic optimization with OpenModelica and exercise. <a title="Abstract OpenModelica tutorial" href="https://modelica.org/events/modelica2017/partners/Abstract-Modelica-Intro-Tutorial-2017-v1b.pdf"><br>
  More information...</a></em></p>
<p>&nbsp;</p>
</li>
<li>
<p><strong>Title:&nbsp;</strong>Control of Electric Drives</p>
<p><strong>Presenter:</strong>&nbsp;OTH</p>
<p><strong>Abstract<em>:</em></strong><em>&nbsp;Based on the equations of an electric drive and the inverter the principles of cascaded control of electric drives will be explained. Starting with the innermost current controller, proceeding with the speed controller, and adding a position controller, the choice of controller types and the optimal controller parameterization are illustrated with examples in Modelica. Topics like feed-forward, limited controller output and anti-windup are adressed.</em></p>
<p><em>Basic knowledge in Modelica and control engineering are required.</em></p>
<p><em>The participants will receive a hand-out of the presentation and the Modelica library used and implemented during the workshop on an USB-stick.</em></p>
<p><em>The workshop is based on lectures held at East-Bavarian University of Applied Sciences Regensburg.</em></p>
<p><em>Either the participants work on their own notebooks, having a Modelica tool already installed, or computers with an installed Modelica tool are available on-site.</em></p>
<p>&nbsp;</p>
</li>
<li>
<p><strong>Title:&nbsp;</strong>Continuous Integration: Testing Modelica libraries</p>
<p><strong>Presenter:</strong>&nbsp;UDK</p>
<p><strong>Abstract<em>:</em></strong><em>&nbsp;This tutorial gives an introduction to Continuous Integration (CI) for Modelica library developers. The tutorial assumes the developer already knows and uses git in combination with github and wants to run tests on a daily basis or triggered by events (e.g. a Pull Request). The participants can choose between a tutorial for Jenkins+Dymola or a tutorial for TravisCI+OpenModelica.</em></p>
<p><em>Material provided includes a step-by-step manual collaboratively written as a github wiki, a github repositry with Modelica code that can be forked, edited and tested, various possible test scripts for different use cases, a VirtualBox image running Ubuntu, Jenkins and Dymola (in demo mode), and a TravisCI configuration file for running OpenModelica on Ubuntu.</em></p>
<p> </p>
</li>
<li>
<p><strong>Title:&nbsp;</strong>Build your Own Hardware Lab with Modelica and Arduino!</p>
<p><strong>Presenter:</strong>&nbsp;Wolfram</p>
<p><strong>Abstract<em>:</em></strong><em>&nbsp;By combining Modelica and Arduino it is possible to quickly create prototypes and hardware labs of a wide-variety of systems. You can use your Arduino to either control some physical system, like a robot, or to actuate on a virtual system. This blog includes several examples of things you could do, from controlling a physical robot to disturbing a virtual inverted pendulum modeled in Modelica.</em></p>
<p><em>In this hands-on tutorial you will develop a small hardware lab using Wolfram SystemModeler and the Wolfram ModelPlug Library. We will also show case larger systems and hand out the "recipe" to create your own replica of these hardware labs.</em></p>
<p><em>Before the session you will receive a link to download and install SystemModeler and the ModelPlug library on your laptop (Win, OS X, or Linux). We will bring Arduino boards and hardware that you can use during the session.</em><br>
  It is v<em>ery important that these programs are installed before the tutorial, as it might take a lot of time to download and install them due to limited bandwidth:</em></p>
<ul>
  <li><em>SystemModeler (trial can be downloaded from <a href="https://www.wolfram.com/system-modeler/trial/" target="_blank">https://www.wolfram.com/system-modeler/trial/</a>. They will need to create a Wolfram ID for this)</em></li>
  <li><em>C++ compiler (Recommended versions for different platforms can be in the following links: <a href="http://www.wolfram.com/system-modeler/compiler-windows/" target="_blank">Windows</a>, <a href="https://www.wolfram.com/system-modeler/compiler-linux/" target="_blank">Linux</a>, <a href="https://www.wolfram.com/system-modeler/compiler-mac/" target="_blank">Apple</a>)</em></li>
  <li><em>Arduino IDE (Downloadable from <a href="https://www.arduino.cc/en/Main/Software" target="_blank">https://www.arduino.cc/en/Main/Software</a>)</em></li>
  <li><em>ModelPlug Modelica Library (Downloadable from <a href="https://www.wolfram.com/system-modeler/libraries/model-plug/" target="_blank">https://www.wolfram.com/system-modeler/libraries/model-plug/</a>)</em></li>
</ul>
<p><em>The hardware needed (except your laptops), including Arduinos, sensors and actuators, will be provided by Wolfram.</em></p>
<p><em>If you encounter any problems during download/installation, or have any other questions prior to the tutorial, you can contact us at <a href="mailto:markusd@wolfram.com">markusd@wolfram.com</a></em></p>
<p><em>Previous knowledge about Modelica and Arduino is not necessary.</em></p>
<p> </p>
</li></ol>