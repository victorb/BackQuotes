## BackQuotes

BackQuotes is all about providing notifications for users of
Flashback.org, the biggest swedish forum, focused on freedom of speech

The project is divided five parts.

* BackData

	Holds data if needed

* BackMail

	Sends email

* BackQueue

	Holds the queues

* BackScraper

	Scrapes Flashback for data and performs actions

* BackUser

	Holds account data if needed

* BackWeb

	The web frontend for the project

* BackWorker

	Reads the queues and does the appropriate action if needed


### Installation and running

BackQuotes is the main repo, containing all the parts that is needed for all the features.

Every repo includes a ````boostrap.sh``` in ```scripts/```-folder which you want to run to install all
dependencies, build and run the application in that folder. Every repo also have a ```src/```-folder
(where applicable) that contains the source for the application.

In the future, main repo will be able to start all applications needed.
