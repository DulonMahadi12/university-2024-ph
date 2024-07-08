<!-- <img src="https://i.ibb.co/52XLK52/depositphotos-295558520-stock-illustration-university-campus-building-hall-education.jpg" alt="isolated" width="full" style="margin: 0 auto;"/>

# University Management System Backend

**Version:** 1.0.0
**variant:** 1

---

**Author:** Dulon Mahadi Molla  
**Affiliation:** Student of .PH  
**Location:** Casara, Narayanganj, Narayanganj, P.C 1400

# Environment Variable :
```javascript
PORT = "3000"
MONGODB_URI = "mongodb+srv://<databaseUser>:<password>@cluster0.cg7lyl6.mongodb.net/<collectionName>?retryWrites=true&w=majority&appName=Cluster0"
```

# Project Setup :
- Clone This Project From Here : [-Github-](https://github.com/DulonMahadi12/school_-Backend-.git)

```javascript
git clone https://github.com/DulonMahadi12/school_-Backend-.git
cd school_-Backend-
npm install
npm install --force
npm run dev
```
- Server Live Link : [-Server-](ehere-to-host-server*)
- Project Overview Video : [-Video-](project-overview-video-link*')
```javascript
// package.json
"scripts": {
    "start": "node dist/server.js",
    "dev": "nodemon",
    "build": "tsc",
    "lint": "eslint . --ext .ts",
    "lint:fix": "eslint . --ext .ts --fix",
    "prettier": "prettier \"**/*.{js,jsx,json,md,ts--check",
    "prettier:fix": "prettier \"**/*.{js,jsx,json,md,ts}\" --write"
  }
```

# Resource :
- https://i.ibb.co/dGWYqm9/manage1.png
- https://i.ibb.co/68SxfmX/manage2.png

# API Endpoints :
### Create demo :
```javascript
demoRouter
  .route('/api')
  .post()
  .get();

demoRouter
  .route('/api')
  .get()
  .put()
```

# Project Overview :
- **GitHub repository:**
  - Create a GitHub repository named: &{project name}. Ensure the files included ".gitignore" and "readme.md".

<!-- -----------------------------------------------------------------------------------
  Administrator = Building - Room - Department(Building) - Gurdian + Student(Gurdian)(Department) - AcademicPayment - Coop(department)

Department = Section(Bulding)(Room) - instructor(department)(section) - course(Department)(instructor)(section) - assaignment(Department)(course)(instructor) - semister(department)(courses)(Instructor)

Student = StudentCopy(student)(Department)(Coop)(Assaignment)(Semister)(Payment)

____________________
API ENDPOINTS:
 
1. Administrator build Buildings 👷‍♂️ 🏢 (post: /api/build/buldings).

2. Administrator build Rooms. How many rooms in Building. Room referenceing Building. (Post: /api/build/rooms).

3. Administrator create Departments like science, arce, commarce. which is referencing Building that which building 🏢 witch Department (Post: /api/create/departments).

4. Administrator create Gurdian+Student here Student referencing the Gurdian. (Post: /api/create/students).

5. Administrator create AcademicPayment that every s Students payment every semester fee or monthly fees. AcademicPayment referencing Student and Department. (Post: /api/create/payments).

6. Administrator create deferent Coops that verify every Student personality and skills. Coops referencing Department.

___________________________
7. Department create Instructor for lead student courses. Instructor referenceing Department and Section that which is her identity in this institution.(post: /api/create/instructors).

8. Department create Course to provide every details of all subject. Course referencing Department, Instructor and Section that means Course provide her identity.(Post: /api/create/courses).

9. Department create Assignment fighting games that children may impliment knowlage and more active. Assignment referencing Department, Course, and Instructor to provide Assignment identity.(post: /api/create/assignment).

10. Department create Semister to identity yearly justifying every students. Semister referencing Department, Course, and Instructor.

___________________

11. Student create his all historical document that he was the truely part of this instruction. Student referencing all of his history that instruction need.(post: /api/create/studentcopy)
----------------------------------------------------------------------------------------- -->


# Third Party Packages (npm) :
typeScript, express, mongoose, cors, dotenv, zod, es-lint, pitter,
  -->
