itac-commons
============
This is the place where all common tools and folders will go to. 
The structure is as below: 
<ul>
	<li>documentation: Place where all documentation will go into</li>
	<li>tools:Where all tools such as FirePacket, HSQLDBPopulator etc. will go </li>
	<li>dbscripts: DB Scripts will be placed here</li>
	<li>commons:Common jars used across all aspects of the application go here </li>
</ul>
The folder structure of tools will be similar to that of producer or consumer, as an example. 
commons is created to avoid duplication of code and utilities and is stuctured as below: 
<ul>
	<li>model: Beans to transfer data between Data, Service and Business layers </li>
	<li>ruleengine: Experimental (may change) </li>
	<li>utilties: Bunch of utility functions such as reading from property files etc... </li> 
</ul>