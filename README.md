# CometLot
Parking app for UTD

# Inspirations
We looked at a common problem that occurs here at UTD - finding the open parking spots for UTD staffs and students

# What it does
Our app that we developed aims at providing the vacant parking information for the users, students and staffs at UTD, by incorporating Alexa assistant to our system.

# How we built it
In terms of building the project we used python and OpenCV along with javascript and Amazon Alexa. Alexa is deployed as a "log-in" component for the parking app. In order to solve one of the main challenges we faced - detecting where vacant spaces were in the parking lots - OpenCV was used to detect these spaces that are vacant and non-vacant and return it back to the Alexa and ultimately back to the user.

# Challenges we ran into
1) We followed an misguided outline for implementing our own Alexa lambda function. The correct version of the platform is written in javascript while we built our initial version in python.
2) There will be some techinical issues: OpenCV version control conflict.
3) Practical issues: what if there are only one open spot and when you reach there, the space has been taken

# Accomplishments that we're proud of
We are proud to be able to detect with high accuracy with the usage of OpenCV.

# What we learned
1) OpenCV is not compatible with all versions of Python;
2) Some parking structures have different angles of light that can misclassify what type of parking is their.
3) Alexa Developer Console is a powerful interactive workspace to design and add new skills to Alexa
4) Lambda function is added to connect the front end (Voice User Interface) to the actual code implemented to create new skills.

# What's next for CometLot
1) Implement OpenCV in the system once we have the access to the data API provided by the IT service
2) Customized Lambda function will be added to add more functionalities for the applilcation.
