# Google Calendar API Integration to List all the events of an User

## [Click to how this Application works](#application-snapshots)

## Tech Stack :
1. Django
2. Django-rest-framework
3. Google Oauth 2.0 
4. Google APIs for Calendar

## Steps to run this Project
1. Clone this repository
2. Create a virtual environment
3. Install the required packages by running the command in terminal `pip install -r requirement.txt`

4. Install ngrok  [Why](#why-we-need-ngrok-to-be-installed)
5. After Successfull intallation of ngrok run the command `ngrok http 8000` 
6. Start the server by running `python manage.py runserver`
7. Now instead of using `https://localhost:8000' use the <mark>Forwarding Url</mark> from the ngrok console
8. Now you can use the endpoints successfully

## Why we need ngrok to be installed ?
To use Google OAuth for accessing the Google APIs we need a secure http connection and for that we need to attach an ssl certificate to our application but for development phase django doesn't support ==https== that's why we need ngrok to be installed . It basically creates a Tunnel forwarding to localhost:8000 with over https

## Application Video 

https://github.com/prafullpandey614/Google_Calendar_Integration_with_Django/assets/81959129/12f28c43-107a-467a-a6ee-5c5e5719c212



