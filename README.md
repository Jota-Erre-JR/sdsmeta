# sdsmeta

## ***Spring React Week***

https://sdsmeta-juliocorrea.netlify.app/

<div aling = "jusify">

A full-stack project integrated with twillio, capable of sending an sms to a specific mobile number with the information contained in the fields of the table presented on the screen.
</div>

# Project Screens
## WEB screen
<div style="display: inline_block"><br>
  <img align="center" alt="WEB-SCREEN" height="800" width="1200" src="https://github.com/Jota-Erre-JR/sdsmeta/blob/main/assets/img/sdsmetaweb.svg">
  </div>
  
## Mobile Screen
<div style="display: inline_block"><br>
  <img align="center" alt="WEB-SCREEN" height="500" width="800" src="https://github.com/Jota-Erre-JR/sdsmeta/blob/main/assets/img/sdsmetamobile.svg">
  </div>

# Technologies used
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- Axios
## Production deployment
- Backend: Heroku
- Front end web: Netlify
- Database: Postgresql
## Would you like to test?

First you need to create an account at:
https://www.twilio.com/

```bash
# clone repository
git clone git@github.com:Jota-Erre-JR/sdsmeta.git
```

## Back end
### Step: Deploy to Heroku

- Create app on Heroku
- Set environment variables with values from your TWILLIO account:
  - TWILIO_SID
  - TWILIO_KEY
  - TWILIO_PHONE_FROM
  - TWILIO_PHONE_TO

```bash
heroku -v
heroku login
heroku git:remote -a <app-name>
git remote -v
git subtree push --prefix backend heroku main
```

## Front end web
### Step: Deploy on Netlify
https://www.netlify.com/

Basic Deployment

Base directory: frontend
Build command: yarn build
Publish directory: frontend/dist
Environment variables:
```
VITE_BACKEND_URL
```
additional settings

Site settings -> Domain Management: (put whatever name you want)
Deploys -> Trigger deploy

## Autor

Julio Correa

<a href = "https://github.com/Jota-Erre-JR" target="_blank"><img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" target="_blank"></a>
<a href = "https://www.linkedin.com/in/julio-cesar-correa" target="_blank"><img src = "https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>

<div align="center">
  <a href="https://github.com/Jota-Erre-JR/sdsmeta">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jota-Erre-JR&layout=compact&langs_count=7&theme=dracula"/>
    </div>
