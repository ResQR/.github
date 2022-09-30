
ARCHITECTURE



APIS AND METHODS

API
/api/user/<user_id>
GET: Returns the user´s information

/api/user
POST: Creates a user

/api/user
PUT: Updates a user

/api/user
DELETE: Removes a user

/api/stats
GET: Returns stats like number of users
class User(name, document, emergency_services, allergies, pathologies, medication, contacts)
A User object.
Describes a user, with their medical information.

Parameters
name – the name of the user.
user_id - unique id for each user.
document – the user’s personal id.
emergency services – (optional) the medical services the user is affiliated with.
allergies – (optional) allergies the user has.
pathologies – (optional) pathologies the user has.
medication – (optional) medication the user needs.
contacts – people that can serve as an emergency contact for the user.

DATA MODEL


USER STORIES
As a traveler, I would like to be able to use the app in other countries and not worry about having to manually translate any of the data into the country’s language.
As a health worker, I would prefer not having to download any app or register and just be able to access the information quickly through the phone’s browser.
As an old person who does not know much about technology, I would like it if it was easy and intuitive to use, as my nephew is getting tired of me calling them for help.


MOCKUPS


