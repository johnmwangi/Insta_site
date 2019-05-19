# Insta_Site


## Built By [John Mwangi]()

## Description
This is aclone of the popular social media application: Instagram. The application allows users to upload, like and comment on other peoples images. Images must have captions and users have profiles where they can see all their images. The admin is  currently responsible for editing or deleting images.
**Users must log in with credible emails**

## User Stories
These are the behaviours/features that the application implements for use by a user.

Users would like to:
* View all images submitted by any user.
* Click on images to display more details.
* Search for users.
* Receive email when signing up.
* Follow others.
* Like Images.


## Admin Abilities
These are the behaviours/features that the application implements for use by the admin.

Admin should:
* Sign in to the application
* Add, Edit and Delete images
* Delete images
* Manage the application.

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Admin Authentication | **On demand** | Access Admin dashboard |
| User Authentication | **On demand, verify emails before proceeding** | Access Admin dashboard |
| Display all images with comments and likes | **Home page** | Clickable links to open any images in a modal |
| Display single images on modal | **On  click** | All details should be viewed|
| To add an image  | **Through Admin dashboard and homepage** | Click on add and upload respectively|
| To edit image  | **Through Admin dashboard** | Redirected to the  image form details and editing happens|
| To delete an image  | **Through Admin dashboard** | click on image object and confirm by delete button|
| To search  | **Enter text in search bar** | Users can search by username|
| View other users profiles via story menu bar | **Click username on user stories navigation** | Users can view all images posted by any user|
| Comment on images | **Add comments below respective image** | Users can add comments on any image|
| Like images | **Add likes to an image** | Users can add likes to images they like|


## SetUp / Installation Requirements
### Prerequisites
* python3.6
* pip
* virtualenv
* Requirements.txt

### Cloning
* In your terminal:

        $ git clone
        $ cd Instrapicha

        ## Running the Application
        * Creating the virtual environment

                $ python3.6 -m venv --without-pip virtual
                $ source virtual/bin/activate
                $ curl https://bootstrap.pypa.io/get-pip.py | python

        * Installing Django and other Modules

                $ see Requirements.txt

        * To run the application, in your terminal:

                $ python3.6 manage.py runserver

        ## Testing the Application
        * To run the tests for the class files:

                $ python3.6 manage.py test images

        ## Technologies Used
        * Python3.6
        * Django  framework and postgresql database

        ## Known Bugs
        * User must add profile before uploading an image or viewing profiles
        * Multiple likes can be done on single image

        Copyright (c) 2019 John Mwangi.
