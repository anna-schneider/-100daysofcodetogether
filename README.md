#100daysofcodingtogether

### Overview 
#100daysofcodingtogether is a job search tracking app, built in collaboration after completion of the Software Engineering Immersive. Bees forever. 

### Wireframes
[Whimsical](https://whimsical.com/8f5LCvH8VBg4nkUMM9ruvw@2Ux7TurymLbAVwquNxQS)

### MVP

#### Goals

- User authentication utilizing Oauth Saml
- Link to third party job search platforms & save postings 
- Leverages AWS Amplify
- App uses React Native

#### Libraries

> Use this section to list all supporting libraries and their role in the project.

|     Library     | Description                 |
| :-------------: | :-------------------------- |
|  React Router   | _For main site navigation._ |
| React Bootstrap | _For styling resources._    |
|      Axios      | _For API data._             |

<br>

#### Data



#### Component Hierarchy

src
|__ assets/
      |__ fonts
      |__ images
|__ components/
     |__ shared/
          |__ Form/
                |__ Form.jsx
                |__ Form.css
          |__ Button/
                |__ Button.jsx
                |__ Button.css
          |__ Layout/
                |__ Layout.jsx/
                |__ Layout.css/
                    |__ Header/
                          |__ Header.jsx
                          |__ Header.css
                    |__ Footer/
                          |__ Footer.jsx
                          |__ Footer.css
                    |__ Nav/
                          |__ Nav.jsx
                          |__ Nav.css
|__ screens/
      |__ Home.jsx
      |__ Register.jsx
      |__ Jobs.jsx
      |__ Job-Tracker.jsx
      |__ Saved-Jobs.jsx




#### Component Breakdown

| Component |    Type    | state | props | Description                                               |
| :-------: | :--------: | :---: | :---: | :-------------------------------------------------------- |
|  Header   | functional |   n   |   y   | _The header will contain the logo & nav._                 |
|   Home    |   class    |   n   |   y   | _The homepage will render the options in flexbox._        |
|   Jobs    |   class    |   n   |   y   | _The Jobs page will render the API calls                  |
|   Form    |   class    |   y   |   n   | _The form will take input to create field in Airtable._   |
|   Nav     |   class    |   y   |   y   | _The buttons will link between the two views._            |
|  Button   |   class    |   y   |   y   | _The numbers will render in results view._                |
|           |   class    |   y   |   y   | _The scratch will animate the numbers in results view._   |
|  Footer   | functional |   n   |   y   | _The footer will show creator info_                       |

#### Component Estimates

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Planning & Research |    H     |      hrs       |     hrs       |   2 hrs     |
| Code Components     |    H     |      hrs       |     hrs       |    hrs      |
| Setup State & API   |    H     |      hrs       |     hrs       |    hrs      |
| Setup Route/Link    |    H     |      hrs       |     hrs       |    hrs      |
| CSS                 |    L     |      hrs       |     hrs       |    hrs      |
| Responsive Design   |    H     |      hrs       |     hrs       |    hrs      |
| Create CRUD Actions |    H     |      hrs       |     hrs       |    hrs      |
| Error Handling      |    H     |      hrs       |     hrs       |    hrs      |
| Post MVP            |    L     |      hrs       |     hrs       |    hrs      |
| TOTAL               |          |      hrs       |     hrs       |    hrs      |

#### Helper Functions

> Use this section to document all helper functions– generic functions that can be reused in other applications.

| Function | Description |
| :------: | :---------- |
|   TBD    |             |

### Post-MVP

- Create path/flow for recruiters

---

### Code Showcase



### Code Issues & Resolutions


````
