Interaction Bridge Database
==========================

This is a java application to create a BridgeDb derby database to map identifiers of interactions from 
different databases to each other. It has been created using the interaction mapping from Rhea 
(http://www.ebi.ac.uk/rhea/). The identifier from Rhea is mapped to identifiers from Enzyme Code, 
EcoCyc, MetaCyc, Macie, Reactome, Kegg Reaction, Unipathway, and Uniprot. This database can be used to 
annotate interactions in PathVisio(http://www.pathvisio.org/), which are displayed in Wikipathways
(http://wikipathways.org/index.php/WikiPathways) as linkouts to the corresponding databases.

You can build the program by checking out the source code and running the build file using ant.

Or, alternatively you can use the program directly without having to first build it, by downloading the pre-built 
InteractionDB.jar file from the dist folder and run the jar providing the absolute path of the interaction database 
to be created as an argument.

Running the InteractionDb.jar from your command line: 

java -jar InteractionDB.jar "/absolute/path/InteractionsDatabase.bridge"

Open this project in Eclipse:
1. Clone this repository into a local folder on your computer (with "git clone <link>")
1. Open a (new) workspace
1. Click on File -> Import... -> Git/Project from Git .
1. Click Next
1. Click on "Existing Local Repository"
1. Click Next
1. Click Add...
1. Find the local folder where this github repository is located.
1. Click Finish in the pop-up menu.
1. Click Next, and when you can click Finish in the main menu, please do.

From Eclipse, you can build the jar file:
1. Find the build.xml file
1. Right mouse click on this file, Run As -> Ant Build.
Check the console output if the jar was build properly.
1. The latest version should be located in the "Dist" folder.

You can also run the IntdbBuilder class from Eclipse:
1. Open the IntdbBuilder (located under src/org/bridgedb/interaction).
1. Click on Run -> Run Configurations


