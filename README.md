<h1>Software-Defined Visualization</h1>

<p>
The Software-Defined Visualization (SDVis) suite contains (mostly) open-source packages designed for performant rendering and visualization on supercomputing cyberinfrastructure. The goal of the suite is to enable visualization capabilities for <i>in situ</i> and post-process analysis across the various hardware architectures found in high performance computing.
</p>

<h2>Motivation</h2>
<p>
The design emphasis for supercomputing systems has moved from raw performance to performance-per-watt, and as a result, supercomputing
architectures are converging on processor with wide vector units and many processing cores per chip. Such processors are capable of performant image rendering purely in software. This improved capability is fortuitous, since the prevailing homogeneous system designs lack dedicated, hardware-accelerated rendering subsystems for use in data visualization. Reliance on this "software-defined" rendering capability will grow in importance since, due to growing data sizes, visualizations must be performed on the same machine where the data is produced. Further, as data sizes outgrow disk I/O capacity, visualization will be increasingly incorporated into the simulation code itself ({\it in situ} visualization).
</p>
<p>
Fortunately, a number of recently-developed software packages capture the improved rendering performance of general-purpose processors and expose that performance through common visualization toolkits. Among these packages are those that render via rasterization, the algorithm used in hardware accelerators, as well as those that render via ray tracing, an algorithm that physically simulates the travel of light. To produce insightful visualizations most efficiently, the visualization scientist should understand the capabilities, performance characteristics and precision limits of each rendering method.
</p>
<p>
The SDVis suite member projects are:
<ul>
<li>GLuRay (tacc.github.io/GLuRay)</li>
<li>GraviT (tacc.github.io/GraviT)</li>
<li>Manta (mantawiki.sci.utah.edu)</li>
<li>OpenSWR (openswr.org)</li>
<li>OSPRay (ospray.github.io)</li>
<li>vtkOSPRay (tacc.github.io/vtkOSPRay)</li>
	<ul>
	<li>pvOSPRay (tacc.github.io/pvOSPRay)</li>
	<li>visitOSPRay (tacc.github.io/visitOSPRay)</li>
	</ul>
</ul>
</p>
