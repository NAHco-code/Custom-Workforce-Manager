<!--TODO:
- package json in client (DONE: WILL)
- where to put invoice form
- figure out back end server and authentication
- create components
- connect components + render in App

PAGES:
  - login
    - admin dashboard
        **weather - date and time
      - job assignment page (when job is clicked - able to edit)
        **functionality:
          *create jobs
          *edit jobs
          *approve as complete

    - employee dashboard
        **weather - date and time
      - specific job page when component is clicked - able to edit)
        **functionality:
          *clock in/out
          *check tasks off list
          *add tasks/make notes
          *fill out invoice + mark as complete/{send admin notication}

ASSIGNMENTS:
- Will:
  *Password Auth - using passport npm package

- Corrine:
  *

- Kathryn:
  *

- Brandon:
  *

- Michael:
  *

-->



# Fleet-Sheets
## Progressive Web Application (Mobile/Tablet First)

### Extra Information/Resources
* [Introduction to PWA's](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Introduction)

### User Story
    AS AN ADMINISTRATOR
    I WANT to be able to
    - create invoices, that employees can easily fill out
    - receive job information and create jobs
    - assign jobs to employees
    - monitor employee Job progress
    SO THAT I can efficently operate and manage my small / medium sized business's fleet employees.


    AS AN EMPLOYEE
    I WANT to be able to
    - view assigned jobs for the day
    - access jobsite information (i.e. address, contact information, notes, etc)
    - complete related jobsite forms/invoices
    - mark jobs completed
    - have the ability to continue to work while remote and offline
    SO THAT I can continue to complete my job expectations in an easy and organized fashion.

### Technology To Use (MERN Stack)
* MongoDb
* Express
* React (w/ hooks)
* Node.Js
* Tailwind CSS &&|| react-material-ui (or something new)

### Desired PWA Functionalities
* Available offline
* Downloadable to android + ios homescreen's
* Device camera functionality / implementation
* Fast load speeds
* Mobile app look/feel
* Push Notifications (mobile + desktop)

    "seed": "node scripts/seedDB.js",

      "eslintConfig": {
    "extends": [
      "react-app",
      "react-app/jest"
    ]
  },
