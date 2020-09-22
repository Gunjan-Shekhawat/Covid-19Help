# Covid-19Help

A Website containing all the information regarding Covid-19.
[Check the website](https://covid-19help.herokuapp.com)

## Tech Stack

- NodeJS
- Express
- MongoDB

Deployed on Heroku.

## Build and run

1. Clone Repo
   - `git clone https://github.com/shivamgupta1999/Covid-19Help.git`
2. To install all the dependencies, enter command:
   -  `node install`
3. To run:
   -  `node app.js`

## Made By

 FSociety (@steverogers07 @Gunjan-Shekhawat and @shivamgupta1999)

COVID-19

This is a Full stack web development task provided by Flikr Hackathon 6.0.
It is a website for the COVID-19.
The website includes the following information:
1) Contact & Helpline Information
2) Notification & Advisory from the government Information.
3) Hospital Dashboard
4) Comparison of daily sample tests and confirmed cases of the patients.

Technologies Used :
	Frontend => HTML, CSS, Bootstrap 4.4.1
	Backend => ExpressJs
	Runtime Environment => NodeJs
	Database => MongoDB
	Deployment => Heroku app

Brief description of each section :
1) Contact & Helpline Information 
	It showcases the helpline number for each state using an API and also displays when was it last updated.
2)Notification & Advisory from the government Information.
	It showcases all the notifications issued by government and agencies using an API along with its 
	date of release and link to the notification. The table uses a scrollbar to navigate and also displays 
	when was it last updated.
3) Hospital Dashboard
	a) Hospitals Beds:
	It showcases the number of Urban beds, rural beds, Urban hospitals, rural hospitals,
 	total beds and total hospitals in every state and also displays when was it last updated.
	
	b) Medical Colleges:
	It showcases the number of Hospital beds, Institute name, City name, Type of organization, 
	and admission capacity in every state in a tabular format.
	It has filter buttons of  'State' and 'Type of organization' from which one can filter the results
	in the table.The table uses a scrollbar to navigate and also displays 
	when was it last updated.
4) Comparison of daily sample tests and confirmed cases of the patients
	It showcases the number of Covid-19 cases in a graphical form. 
	The graph displays the number of people deceased. The date and exact number of people
	deceased on that date is visible at plotting points.
	One can use various filters like Gender, age range , state and from a specific time period 
	to see the curve of people deceased .
	Download option is available to the user for every graph.
