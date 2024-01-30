# Case for little backup box

This project provides a housing for little backup box based on a Raspberry Pi 4B or Raspberry Pi 5.<br>
It is based on a 3D drawing on the <a href="https://www.freecad.org">freeCAD</a> platform. This drawing can be easily adjusted using an integrated table of dimensions.<br>
<br>
<br>
For more information visit <a href="https://github.com/outdoorbits/little-backup-box">outdoorbits/little-backup-box</a>. In lbb's <a href="https://github.com/outdoorbits/little-backup-box/wiki">Wiki</a> you will find all information needed to plug it all together.</a>
<br>
<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/lbb-orange.jpg" align="center" width="90%">
	<figcaption>Little Backup Box in this case, including a ssd1331 color display, buttons for menu-navigation and a pwm-controlled fan</figcaption>
</figure>
<br>
<h2>The standard drawings assumes the following components:</h2>
<ol>
	<li>Raspberry Pi 4 Model B or Raspberry Pi 5</li>
	<li>Display ssd1331 (RGB color display with 96x64 pixels)</li>
	<li>Fan having external dimensions 30x30mm, hole spacing 24mm; prefer PMW-versions</li>
	<li>Micro key buttons 6x6 mm2, mounted on a board</li>
	<li>15 pieces of jumper wire, female</li>
	<li>4 screws M2.5 x 20 mm for the case</li>
	<li>8 screws M2.0 x 6 mm and nuts for the buttons</li>
	<li>Hot glue to stick the display</li>
</ol>

<h2>Customize drawing</h2>
If you use different hardware components, you can adapt the drawing.
It's (relatively) easy to adjust dimensions:
<ol>
	<li>Open the FCStd file with freeCAD</li>
	<li>Open the "dim" spreadsheet in the tree view</li>
	<li>Change the appropriate dimensions</li>
	<li>Mark the respective body in the tree view (e.g. "Bottom")</li>
	<li>Export the stl file (File - export...)</li>
</ol>

<br>
<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/case-full.png" align="center" width="90%">
	<figcaption>The whole case</figcaption>
</figure>

<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/case-bottom.png" align="center" width="90%">
	<figcaption>The bottom</figcaption>
</figure>

<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/case-top-inner.png" align="center" width="90%">
	<figcaption>Inside view of the top</figcaption>
</figure>

<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/fan.webp" align="center" width="50%">
	<figcaption>Fan, look for &quot;<a href="https://thepihut.com/products/highpi-pro-5v-fan-software-controlled">5V Fan - Software-Controlled</a>&quot;</figcaption>
</figure>

<figure align="center">
	<img src="https://github.com/outdoorbits/case-for-little-backup-box/blob/main/images/micro-buttons-6x6.png" align="center" width="50%">
	<figcaption>Mico buttons, look for &quot;<a href="https://eckstein-shop.de/10xMicroKeyTaster6x6mmButtonsModuleRastermaC39F22C54mm12V2F50mA">Micro key button</a>&quot;</figcaption>
</figure>
