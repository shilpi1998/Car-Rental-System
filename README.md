# Car-Rental-System
## How Car Rental Services Work<br>
A car rental is a vehicle that can be used temporarily for a period of time with a fee. Renting a
car assists people to get around even when they do not have access to their own personal vehicle
or don’t own a vehicle at all. The individual who want to rent a car must first contact the car
rental company for the desired vehicle. This can be done online. At this point, this person has to
supply some information such as: dates of rental, and type of car. After these details are worked
out, the individual renting the car must present a valid Identification card.<br>

Online Car Rental System, a project made with python language, django framework and
mysql as database.<br>

The project is intended to be developed as a platform where the user can book the cars on rent as
well as car dealer can also can give his/her car on rent.
The Home page will be having mainly 2 buttons: Customer portal and Car dealer portal. Here,
the user can click on the button accordingly to proceed with their desired actions.<br>

## Structure of Project<br>
There are three modules (apps), one for car dealers, one for customers, one for the home page.
Each app handles usual django things like models, urls and views.<br>

## System<br>
This system works like the car-dealer goes to the car_dealer_portal, signs up and uploads
cars that he thinks are available for renting. Customer logs in to the customer_portal,
enters the area at which he wants the car and the system scans through all the available
car-dealers and their cars at that particular area and shows the results to the customer. If
the car is already rented by someone else it won’t show up in the search results.<br>

## CSS<br>
The simple CSS file provided by w3schools.org is used. The main purpose of this project
was to learn django framework, handling backend tasks and managing database, so didn’t
used bootstrap or other CSS frameworks.<br>

##Database<br>
The local mysql database is used and the python classes in models.py helps
managing/updating database. The database configuration can be accessed in
ocrs/ocrs/settings.py and in that file under the DATABASE section you can add your
own database, username password etc.<br>

