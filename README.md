<html>
 <body>
<p>ERSN-OpenMC is a Graphical User Interface for OpenMC Monte Carlo particle transport simulation code, originally developed by Jaafar EL Bakkali &amp; Tarek EL Bardouni, membres of Radiation and Nuclear Systems Group (ERSN; Equipe Radiations et Systèmes Nucléaires) at Faculty of Sciences Tetuan (Morocco).This java-based application has been created to provide a user-friendly human-computer interface using <a href="http://mit-crpg.github.io/openmc/"> OpenMC Monte Carlo code </a>  as a neutrons calculation engine. This java-based application allowing creation/edition separate mandatory XML files describing the geometry, the materials involved and the settings of a given OpenMC simulation. The creation/edition facility is also allowed to the optional xml files such as tallies (results of given simulation), plotting and CMFD (Coarse-Mesh Finite Difference) acceleration. The ERSN-OpenMC will help the OpenMC users to avoid hardcoding full content of those XML files when creating, editing its. In order to displaying the user application xml files in a more readable way, the syntax highlighter approach has been considered where the open source java library <a href="https://code.google.com/p/jsyntaxpane/"> jsyntaxpane </a>  was used as default highlighter for those xml files.</p>

<p><b> 1 - Getting ERSN-OpenMC application </b>
<br> For Ubuntu you need the following : <br>
 <br> 1.  update the OS:   <br>  $ sudo apt-get update  <br>
                        <br>          $ sudo apt-get upgrade <br>
<br> 2.  install g++ :           $ sudo apt-get install g++ <br>
<br> 3.  install java 8 : <br>
                <br>             $ sudo add-apt-repository ppa:webupd8team/java <br>
                         <br>    $ sudo apt-get update <br>
                         <br>    $ sudo apt-get install oracle-java8-installer  <br>
<br>4. download the ERSN-OpenMC GUI from : <br>
<br><a href="https://github.com/EL-Bakkali-Jaafar/ERSN-OpenMC/releases">https://github.com/EL-Bakkali-Jaafar/ERSN-OpenMC/releases</a> <br>
<br>5.  untar the archive and double-click on the extracted binary file to run it under java <br>
</p> <a href="https://camo.githubusercontent.com/0045b480bf8d53a0d303fd1d6a68b1727cea4c8f/68747470733a2f2f736f75726365666f7267652e6e65742f702f6572736e2d6f70656e6d632f73637265656e73686f742f70696374757265312e706e67" target="_blank"><img src="https://camo.githubusercontent.com/0045b480bf8d53a0d303fd1d6a68b1727cea4c8f/68747470733a2f2f736f75726365666f7267652e6e65742f702f6572736e2d6f70656e6d632f73637265656e73686f742f70696374757265312e706e67" data-canonical-src="https://sourceforge.net/p/ersn-openmc/screenshot/picture1.png" style="max-width:100%;"></a><p></p>

<p><br>6.  then install the prerequisites and openMC (you will be asked to enter the sudoer password) <br></p>

<p><b> 2 - Creating new  OpenMC project with ERSN-OpenMC application </b></p>

<p>This java-based application allows user to create new OpenMC project via the following form:</p>

<p></p> <a href="https://camo.githubusercontent.com/248e4736f8f2d7305c6e5577b2c04b7de7e5e37b/68747470733a2f2f736f75726365666f7267652e6e65742f702f6572736e2d6f70656e6d632f73637265656e73686f742f323031352d30332d30312d3033303334335f353234783333305f7363726f742e706e67" target="_blank"><img src="https://camo.githubusercontent.com/248e4736f8f2d7305c6e5577b2c04b7de7e5e37b/68747470733a2f2f736f75726365666f7267652e6e65742f702f6572736e2d6f70656e6d632f73637265656e73686f742f323031352d30332d30312d3033303334335f353234783333305f7363726f742e706e67" data-canonical-src="https://sourceforge.net/p/ersn-openmc/screenshot/2015-03-01-030343_524x330_scrot.png" style="max-width:100%;"></a><p></p>

<p>Once the user click on "create project" button a new OpenMC project will be created automatically.</p>

<p></p> <a href="https://camo.githubusercontent.com/fdda1ccb8b9eb851e4a0098316d7e8c4f6fdb067/68747470733a2f2f736f75726365666f7267652e6e65742f702f6572736e2d6f70656e6d632f73637265656e73686f742f4552534e2d6f70656e6d635f312e706e67" target="_blank"><img src="https://camo.githubusercontent.com/fdda1ccb8b9eb851e4a0098316d7e8c4f6fdb067/68747470733a2f2f736f75726365666f7267652e6e65742f702f6572736e2d6f70656e6d632f73637265656e73686f742f4552534e2d6f70656e6d635f312e706e67" data-canonical-src="https://sourceforge.net/p/ersn-openmc/screenshot/ERSN-openmc_1.png" style="max-width:100%;"></a><p></p>

<p>The utility makes the download, compilation and installation of OpenMC code and related libraries, happen automatically and transparent to the user. </p>

<p></p> <a href="https://camo.githubusercontent.com/13c22cd1b2c2067da3c5cc5438417c52e2b24deb/68747470733a2f2f612e6673646e2e636f6d2f636f6e2f6170702f70726f6a2f6572736e2d6f70656e6d632f73637265656e73686f74732f4552534e2d4f70656e4d435f322e706e67" target="_blank"><img src="https://camo.githubusercontent.com/13c22cd1b2c2067da3c5cc5438417c52e2b24deb/68747470733a2f2f612e6673646e2e636f6d2f636f6e2f6170702f70726f6a2f6572736e2d6f70656e6d632f73637265656e73686f74732f4552534e2d4f70656e4d435f322e706e67" data-canonical-src="https://a.fsdn.com/con/app/proj/ersn-openmc/screenshots/ERSN-OpenMC_2.png" style="max-width:100%;"></a><p></p>

<p>The user can choose an isotope from a table of nuclides and select physical quantities to be scored as we can see in the following figure: 
</p> <a href="https://camo.githubusercontent.com/d1df086c6f259c5393ebd310cff0cef1431a136d/68747470733a2f2f612e6673646e2e636f6d2f636f6e2f6170702f70726f6a2f6572736e2d6f70656e6d632f73637265656e73686f74732f323031352d30312d31382d3030313530385f31333636783736385f7363726f742e706e67" target="_blank"><img src="https://camo.githubusercontent.com/d1df086c6f259c5393ebd310cff0cef1431a136d/68747470733a2f2f612e6673646e2e636f6d2f636f6e2f6170702f70726f6a2f6572736e2d6f70656e6d632f73637265656e73686f74732f323031352d30312d31382d3030313530385f31333636783736385f7363726f742e706e67" data-canonical-src="https://a.fsdn.com/con/app/proj/ersn-openmc/screenshots/2015-01-18-001508_1366x768_scrot.png" style="max-width:100%;"></a><p></p>

<p><br></p>

<p><b> 3- Using existing installation of Openmc </b>
 The ERSN-OpenMC has been created to be flexible, the users can link their own installation of OpenMC to the ERSN-OpenMC application, thereby changing the three configuration files as follow:</p>

<p>openmc.dir: user must indicates the full path of openmc executable</p>

<p>cross_sections.dir : full path to the cross_sections.xml file</p>

<p>utils.dir: full path to the sub-directory utils that is located into src directory of openmc</p>

<p><b> 4 - Contribution </b></p>

<p>Anyone can contribute, even if they have a java programming skills.</p>

<p><b> 5 - I want a help </b></p>

<p>Contact:
Jaafar EL Bakkali, at  <a href="mailto:bahmedj@gmail.com">bahmedj@gmail.com</a> or Tarek EL Bardouni, at <a href="mailto:tarekbardouni@uae.ma">tarekbardouni@uae.ma</a>          </p>

<p><b> 6 - License </b></p>

<p>This software is free software; you can redistribute it and / or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version. For the complete text of the license see the GPL-web page.</p>
</article>
  </div>
</div>
  </body>
</html>

