How to run the project

-Prerequisites

1. This dependancy must be added to the build.gradle file in order for the CSV to be generated.
	dependencies {
   		 implementation group: 'com.opencsv', name: 'opencsv', version: '4.1'
	}
   Upon completion, you will be prompted with an onscreen icon which should be clicked for the dependencies to be updated 

2. You may change the initial directory for your convenience.
	In MainClass.class
      		Scroll until you find the crossCompare method and change initial directory path to
	
3. After it is completed, click the green play button on the top.
    It is configured to build and run so upon clicking, the UI will be displayed.

	Click the compare button and you will be prompted with a UI to select the files of your choice
	 >I have a testing folder in my directory (inside uidemo\\sample). This folder contains the required files for testing such as empty, .md, .java ect

   Upon clicking, the similarities will be displayed and the rest of the results are printed onto 'result.csv' which can be found in the same directory
   Click stop to stop the program and interrupt the threads.