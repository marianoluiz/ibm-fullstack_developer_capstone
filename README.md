# coding-project-template

mod1: Hands-on Lab: Static Pages

virtualenv venv
source venv/bin/activate

python3 -m pip install -U -r requirements.txt

python3 manage.py createsuperuser

npm run build


docker compose up - start services mongodb & node
# not docker-compose

backend: 3030
frontend: 8000