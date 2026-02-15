---
title: Research and Projects
layout: page
description: 'Brain-as-world thinking'
image: assets/images/2024_ver2.jpg
nav-menu: true
---
<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Along-Tract Analysis of Cerebellar Pathways in MCI and AD</h2>
		</header>
		<p><strong>Duration:</strong> April 2024 - July 2024<br>
		<strong>Supervisor:</strong> Dr. Samira Raminfard</p>
		<h3>Overview</h3>
		<p>The cerebellum's role in cognition is increasingly recognized, but how do its cortical connections degrade in Alzheimer's? I worked on extracting and analyzing cerebellar white matter tracts to quantify structural changes.</p>
		<span class="image main">
			<img src="assets/images/cerebellar-tracts.png" alt="Cerebellar pathway tractography" />
			<p style="text-align: center; font-size: 0.9em; margin-top: 0.5em;">
				<strong>Figure 1.</strong> A: CPC-L (Cortico-Ponto-Cerebellar Left), B: CPC-R (Cortico-Ponto-Cerebellar Right), C: CTC-L (Cerebello-Thalamo-Cortical Left), D: CTC-R (Cerebello-Thalamo-Cortical Right)
			</p>
		</span>
		<h3>Methods</h3>
		<p>Used exploreDTI to isolate cortico-ponto-cerebellar (cortex → cerebellum) and cerebello-thalamo-cortical (cerebellum → cortex) pathways. Calculated FA (fractional anisotropy), MD (mean diffusivity), RD (radial diffusivity), and AD (axial diffusivity) along tract profiles. Set up comparison pipeline between MCI and AD patient groups.</p>
		<h3>What I Learned</h3>
<p>Working with diffusion imaging is messy. You need anatomical knowledge just to define the right ROIs, and tract extraction is all about tweaking parameters until things look right, which means artifacts can sneak in easily.</p>

<p>But the bigger question hit me while working with the along-tract analysis: how do we even decide where to split a tract? By anatomical regions? By where synapses are? And what about polysynaptic pathways? If signals jump between multiple neurons along the way, are we even capturing the real communication path? The tract looks continuous in the image, but the actual signal might be doing something completely different.</p>

<p>It made me realize these metrics show us structure—where the wires are, but not how information actually flows through them. That gap between what we measure and what's actually happening keeps bothering me.</p>
		<p><strong>Tools:</strong> exploreDTI, MATLAB, diffusion MRI analysis, tractography</p>
	</div>
</section>



