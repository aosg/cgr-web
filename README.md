# Competency Growth Review Trans-European Division

## 1. Objective
This project aims to build an site for assessment tool for pastoral development. Pastor, together
with the ministerial secretary, will be able to create a personal development plan for the coming year

## 2. Functionalities
- Initial basic login through email accounts;
- User Registration for invite with Name, Email, Password, Union, Association, Church;
- Form to complete score for each of the 7 competencies;
- History of results;
- Database API for configuration and storage of information used by the application through the accounting system;
- Server configuration for user of the system;

## 3. Infrastructure and Resources
- The site may be accessed through a link available on the TED website;
- Database server for access to registered members; Firebase on Google;
- API to access the accounting system;

## 4. Forms
Five type of users can be fill the assessment, for the pastor

- SF = Self (Pastor)
- PR = Peer
- ML = Ministerial
- CL = Church Leader
- CM = Church Member

- The user that is to receive the invitation, must have a unique code of access with email;
- In this access the admin can select the type of user (SF - PR - ML - CL CM) and send the invite;
- Each one will need their own login so that no one will see what others have written;
- Then an average score for each of the 7 competencies will be generated;
- Only the Ministerial will receive the average score and from this, together with the pastor, will
be able to create a personal development plan.

## 5. Example
I’m a Pastor and will going to do my own assessment, maybe my code would be:

- Chimello.Rodrigo-2017-SF-043
- Chimello.Rodrigo = Last name.Name
- 2017 = Year
- SF = Self (Pastor)
- 043 = Number from my employing conference
- I’m a Church Member and will going to do the assessment, where I receive the invitation from my
email:
- Johnson.Patrick-2017-CM-043