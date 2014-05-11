## BackQuotes

The project is divided five parts.

* BackData
	Port: 4111

	Holds data if needed

* BackMail
	Port: 4112

	Sends email

* BackQueue
	Port: 4113

	Holds the queues

* BackScraper
	Port: 4114

	Scrapes Flashback for data and performs actions

* BackUser
	Port: 4115

	Holds account data if needed

* BackWeb
	Port: 4116

	The web frontend for the project

* BackWorker
	Port: 4117

	Reads the queues and does the appropriate action if needed


### Installation and running

BackQuotes is the main repo, containing all the parts that is needed for all the features.

Every repo includes a ````boostrap.sh``` in ```scripts/```-folder which you want to run to install all
dependencies, build and run the application in that folder. Every repo also have a ```src/```-folder
(where applicable) that contains the source for the application.

In the future, main repo will be able to start all applications needed.
