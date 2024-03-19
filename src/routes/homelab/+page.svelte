<svelte:head><title>Building out my Home Lab</title></svelte:head>
<p><a href="/">Go Back</a></p>

<p>1λ.com :: <span style="color: #ff0019;">~</span> $ cat homelab/intro.md</p>

<p>
	> I've mostly used cloud GPU resources for the initial cost savings. Dropping *thousands* of pounds in building my own deep learning rig was always tempting, but I just never pulled the trigger. Getting by with the desktop I used for gaming became less and less suitable, and purely from a interest perspective, I wanted my own hardware. This went hand in hand with also wanting to improve my home lab.
	<br><br>
	> I've always enjoyed having my own lab network to test various automations, mess around with orchestration, and learn general networking to connect them together. I'll be using this post to update my progress of where I'm current at with my Home Lab, what changes I've made, and why.
</p>

<p>1λ.com :: <span style="color: #ff0019;">~</span> $ cat homelab/log.md</p>

<p>
	## <span style="color: #ff0019;">Mini-Deep Learning Rig</span>
	<br><br>
	Coming Soon!
</p>

<p>
	## <span style="color: #ff0019;">2024-03-18</span>
	<br><br>
	The first entry, of where I am currently with my lab, this won't have much detail, purely because it's been a long time since buying the hardware, and I'm not sure of the reasons I picked these over others.
</p>

<p>### Cabinet</p>
<ul>
	<li>Deep Wall Server Cabinet (6U).</li>
	<li>13A Rack Mount PDU (6-way).</li>
	<li>Network Rack Mount Patch Panel (24 Port).</li>
	<li>Fixed Rack Mount Shelf (1U).</li>
	<li>Cat6A 30AWG Ethernet Cables (10G).</li>
	<li>All using RackStuds (These things are amazing, super recommend).</li>
</ul>

<p>### Networking</p>
<ul>
	<li>Fibre Broadband (A lousy 60 Mbps Down, 20-25 Mbps Up).</li>
	<li>Carrier Provided Router.</li>
	<li>OpenWrt (On a Raspberry Pi 4B).</li>
	<li>2x NETGEAR GS308E - 8-Port Gigabit Ethernet Smart Managed Plus Switch (1G).</li>
</ul>

<p>### Desktop</p>
<ul>
	<li>Intel i9-9900K @ 4.8 GHz</li>
	<li>64 GB DDR4 @ 3600 MHz</li>
	<li>NVIDIA GeForce RTX 4060 Ti 16 GB</li>
	<li>MPG Z390 GAMING EDGE AC</li>
	<li>Intel® Ethernet Connection I219-V (1GbE)</li>
</ul>

<p>### Spare Desktop</p>
<ul>
	<li>Intel i7-6700K @ 4.4 GHz</li>
	<li>64 GB DDR4 @ 2600 MHz</li>
	<li>NVIDIA GeForce RTX 2060 Ti 8 GB</li>
</ul>

<p>### MacBook Air (13-inch (M2 Chip))</p>
<ul>
	<li>8-Core CPU</li>
	<li>10-Core GPU</li>
	<li>16GB Unified Memory</li>
	<li>512GB SSD Storage</li>
</ul>

<p>### Storage</p>
<ul>
	<li>8 TB SSD Total</li>
	<li>14 TB HDD Total</li>
</ul>

<p>### Other</p>
<ul>
	<li>Raspberry Pi 4B (x4)</li>
	<li>Raspberry Pi 3 (x2)</li>
</ul>

<p>
	### Services
	<br><br>
	I run some services on this lab, mostly for testing and learning purposes. I'll list some below, and update this list as I add more.
</p>
<ul>
	<li>Full 3-Node Hyper-V Nested Cluster</li>
	<li>3-Node Docker Swarm</li>
	<li>2-Node Kubernetes Cluster (Testing)</li>
	<li>Management and User Active Directories (DCx3)</li>
	<li>Grafana (Prometheus, Node Exporter, Cadvisor)</li>
	<li>MySQL Database (x3)</li>
	<li>Nginx</li>
	<li>TeamSpeak</li>
</ul>