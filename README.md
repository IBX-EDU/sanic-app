## ibx-sanic-app

Sanic application for the Fly.io cloud deployment

# Components
- [Sanic](https://sanic.dev): Sanic is a Python 3.8+ web server and web framework that’s written to go fast.
- [Fly.io](https://fly.io): Fly is a platform for running full stack apps and databases.

# Deployment
0. [Fly.io](https://fly.io) - create account
1. mkdir ibx-sanic-app
2. cd ibx-sanic-app
3. python -m venv venv
4. .\venv\scripts\activate
5. pip install sanic
6. pip freeze > requirements.txt
7. create server.py
8. some code
9. configure Procfile
10. flyctl auth login
11. flyctl launch
12. flyctl deploy
13. browse https://ibx-sanic-app.fly.dev/
