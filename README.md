
# Full Stack Project - MyDrugs

- A drug prescription app(stores the prescription and the drug info)
- I've thought about this app idea when I personally experienced how impossible it is
to remember the names of the meds/when did I get it/refill?/dr's name?/description/etc.
- Any patients who get prescriptions from a doctor

### Unsolved Problems

- I still need to update/organize page layout
- I need to make each prescription clickable to be selected in order to update(edit)  
- I would like to add a visible user profile right by the prescription view page after user signing in

## Important Links

## Important Links

- [Project Repo Front End](https://github.com/JeheeChoi/my-drugs-client)
- [Project Repo Back End](https://github.com/JeheeChoi/my-drugs)
- [Deployed API](https://salty-woodland-25840.herokuapp.com/prescriptions)
- [Deployed Client](https://jeheechoi.github.io/my-drugs-client/)

## Technologies Used

- JavaScript
- HTML/CSS
- jQuery
- Express
- MongoDB
- Mongoose

## User stories

- User can sign up/sign in/sign out/change pw
- User can create(add) a record of a prescription
- User can see all the prescriptions that are stored
- User can update the prescriptions(log side effects, likes/dislikes)
- User can delete(archieve) the prescriptions


## Wireframes

![wireframe1](https://i.imgur.com/GNA3lxo.png)
https://imgur.com/a/EnDex7R


## Resources

resources: user, prescription
User attributes: firstName, lastName, DOB
Prescription attributes: drugName, description, orderBy(dr's name), date, refills?


## ERD (entity relationship diagram)

One to many relationship: a user to many prescriptions.
![ERD1](https://i.imgur.com/ctfBUsw.png)
https://imgur.com/a/NTsBb3s


## Routing

user routes
prescription routes


## Timetable

- Day 1 - Setting up repos, READme, consulting with instructor, pseudo code, start working on userSchema
- Day 2 - Working on user - server.js/model/user routes/curl scripts
- Day 3 - Working on prescription - server.js/model/prescription routes/curl scripts
- Day 4 - Finishing up Working on front end
