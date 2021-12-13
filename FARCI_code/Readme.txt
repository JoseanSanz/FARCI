To apply the algorithm it is necessary to execute the command: java -jar FARC_imb.jar param.txt

The file param.txt determines:
	*) The paths to the input files (train, validation, test) of the classifier 
	*) The paths to the output files of the classifier:
		* Training results
		* Testing results
		* Definition of the membership functions 
		* Rules learned by the system
		* Time used by the classifier in each stage
		* Total time used by the classifier
		* Number of rules after applying each stage of the classifier
		* Evolution of the evolutionary algorithm applied by the classifier
	* The values for the different hyper-parameters of the classifier
	
The input files should containg the data in the KEEL format. You can download this type of data in the KEEL webpage: http://www.keel.es/

The explanation about the execution of the method using the KEEL structure is made in the .rar file containing the source code of FARCI: source_code_FARCI.rar (see the Readme file of that folder).