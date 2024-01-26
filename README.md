<h1>Engine data recorder.</h1>

<p>The aim of this small project was to make an engine speed recorder, that will record the rpm of the engine and the period of each rotation.</p>
<p>The rotation is being measured by the use of encoder. It has:</p>
<ul>
  <li>A - yellow wire (500 impulses per rotation)</li>
  <li>~A - green wire</li>
  <li>B - blue wire</li>
  <li>~B - orange wire</li>
  <li>~B - orange wire</li>
</ul>
  A, ~A, B, ~B, VCC, GND, single-rotation and ~single-rotation wires. 

<p>Single-rotation wire emits the high-level signal each time there is a full-rotation, which will be used.</p>
<img src="encoder.jpeg" alt="encoder image" width=300/>
<p>Prototype connection for signal investigation:</p>
<img src="cables.jpeg" alt="connector image" width=300/>
<h2>The circuitry:</h2>
