# Advanced_IVR
Changing the way we use Interactive Voice Response through our innovation and thinking.


# Question Detector

This is poweful "NLP" model which works on the principal of finding tags or classes related to a particular question. The tagging part uses deep learning techniques trained on a public dataset containing 40,000 data related to 20 tags.

Finding tags reduces the large search space over the stackoverflow which helps our project not only run faster but also helps in finding best result in user question querry.

After finding the questions a similarity search is done using "The Leatest NLP Techniques".

The data genrated is then processed by the backend api and is stored in the database for future refrence and then it is retrived back via server to provide the User with the detected questions by our Model.

Along with question we are also serving the predcted tags along withh there acurrecy score predicted by our model.The acurrecy can be incresed to more then 95 % if correct amount of data supplied.

# Note For the external file download
Please download the following file from the resources and paste it in asked_question folder
and extract in the asked_question only
[Link To File](https://drive.google.com/open?id=1uQJv6Cz1b3g1OeyE951V05nC0lwo1rWp)

## Getting Started
1.) Starting the Ai Model

	
	To run the complete project you need to have the following packages imported correctly:
		1: Python Version >= 3.x
		2: install pickle-(Any version)
		3: install Keras-(Any version)
		4: install Sklearn-(Any version)
		5: install Numpy-(Any version)
		6 install pandas-(Any version)
		Please set the working directory ibm/asked_question
		You can use os.chdir(path).

	Navigate To IBM folder and run the ibm.py located in asked_question folder.
		If running succesfully procees to step 2.
		otherwise try importing files correctly.

2.)  Starting the Website 

	To run the complete project you need to have nodejs configured on your system.
		1: Open CMD in Root Project.
		2: installing packages write npm install.
		3: To run the project Continusly install npm install -g nodemon
		4: In CMD run nodemon
			result: listening on port 9000.
				connected to db.
		5: open chrome type "http://localhost:9000/"
			Now proceed as the workflow goes....


### Prerequisites

	1.) Python installed and configured with system Preferably in Anaconda navigator.
	2.) Nodejs installed and configured with the system.


### Preview And Idea
The Idea and Vedio is saved in documents and video folder.
Preview Our vedio on [Youtube Link](https://www.youtube.com/watch?v=s16EKLR2FpU&feature=youtu.be)

## Authors

* **Priyanshu Sinha** 
* **Saurabh Singh** 

