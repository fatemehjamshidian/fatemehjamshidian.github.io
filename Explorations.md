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
			<img src="assets/images/cerebellar-tracts.png" alt="Cerebellar pathway tractography" style="width: 30%; />
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



<section id="two">
	<div class="inner">
		<header class="major">
			<h2>The Influence of Salient Experiences on Hippocampal Activity Correlations</h2>
		</header>
		<p><strong>Duration:</strong> November 2023 - September 2024<br>
		<strong>Supervisor:</strong> Dr. Tristan Manfred Stöber, Ruhr University, Bochum, Germany</p>
		<h3>Overview</h3>
		<p>How do social experiences reshape the way neurons talk to each other? I analyzed cell assembly dynamics in the hippocampus—specifically CA2-CA3 regions—to see how spike patterns and correlations change after salient social interactions.</p>
		<h3>Methods</h3>
		<p>Python-based electrophysiology analysis of spike trains. Examined correlations between neuronal firing patterns in CA2 and CA3 following social experiences to understand how cell assemblies reorganize.</p>
			<span class=""image fit"">
			<img src="assets/images/ca2cA3.png" alt="cell assembly analysis" style="width: 30%; />
			<p style="text-align: center; font-size: 0.9em; margin-top: 0.5em;">
				<p>A) Three examples of assemblies that exceeded the Marcenko-Pastur threshold from a representative session. Assembly members were identified as neurons with ICA weights exceeding an Otsu threshold, and assemblies with both CA2 and CA3 or CA1 and CA2 neuron members were named joint cell assemblies. B) Assembly Similarity Index matrix. Joint assemblies from social interaction were compared to non-social joint cell assemblies. This was calculated as the dot product of different assembly pairs, and a similarity index above the 95 percentile of a surrogate distribution was considered significant. C) Venn diagrams illustrate the proportions of assemblies detected in social (yellow) and object interaction conditions (green). 
			</p>
		<h3>What I Learned</h3>
		<p>This was my first time working with single-neuron recordings. I'd always worked with macroscale data—MRI, fMRI, diffusion imaging—where you see big blobs of brain activity. But spikes? That's magic. You can actually watch individual neurons firing, see the exact timing of their conversations.</p>
		<p>But honestly, I learned more than just technical skills. This was my first international collaboration, working remotely with Tristan's lab in Germany. Tristan is the kind of person who genuinely supports his students—no matter who you are or where you're from. His way of looking at the world, his approach to science and people, taught me a lot.</p>
		<p>Working on an international team showed me something important: you learn to express your ideas clearly while staying independent in your thinking. You realize you're not the center of the world. When you work with people from different cultures, you see how many ways there are to approach the same problem. You're just one part of a bigger team, and that team only works when everyone takes responsibility for their piece and brings their own perspective. That's how you actually create something valuable.</p>
		<p><strong>Tools:</strong> Python, electrophysiology analysis, spike train analysis</p>
	</div>
</section>

