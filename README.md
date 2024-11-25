CODETRIBE DATABASE MONGO

## Description



1. ## Create the Database

You'll run this line on 
mongosh
use codetribe
2. Create the Facilitators Collection
Insert a document into the Facilitators collection:

db.Facilitators.insertOne({
    Name: "John Doe",
    Location: "Cape Town",
    Course: "Full Stack Development"
})
3. ## Create the Trainees Collection
Insert a document into the Trainees collection:


db.Trainees.insertOne({
    Name: "Jane Smith",
    Location: "Johannesburg",
    Facilitator: "John Doe"
})
4. ## Create the Projects Collection
Insert a document into the Projects collection:


db.Projects.insertOne({
    Name: "Weather App",
    Course: "Full Stack Development",
    Lesson: "API Integration"
})

(mongoDB\image\creating collection.png)

## Verifying the Data
 use the following commands:

View all documents in the Facilitators collection:

db.Facilitators.find().pretty()
View all documents in the Trainees collection:


db.Trainees.find().pretty()
View all documents in the Projects collection:


db.Projects.find().pretty()

(mongoDB\image\showingcollections.png)