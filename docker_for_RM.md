# Docker (for dummies) for Remote Monitoring V2
## Publishing your own code/changes

###Customizing the (UI) solution 
(seed: https://docs.microsoft.com/en-us/azure/iot-suite/iot-suite-remote-monitoring-customize)

1. Clone the github repository

    	git clone https://github.com/Azure/pcs-remote-monitoring-webui.git
	
	Note: If you use the PREVIEW template, clone the branch 1.0.0-preview.4	
	    git clone -b <branch> --single-branch <url>

2. Change something (just for test)

	○ For example, in   src/common/lang.js write   CONTOSO: 'YourCompanyName' 
	○ And change the logo: add it in "assets/icons" and edit the file: src/components/layout/leftNav/leftNav.js, change the line
		import ContosoIcon from '../../../assets/icons/Contoso.svg';

