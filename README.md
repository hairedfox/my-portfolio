# My Portfolio

I'm creating my portfolio with Flask framework. This is lightweight and minimal. I like it.

I'll think about the UI later. For now, let's create it as an API. I can later add views if needed.

Technologies used:
- Python@3.11
- Flask@2.3.2
- pip@22.3.1
----
```
# Activate .venv
. ./.venv/bin/activate

# Extract to requirements from venv
pip freeze > requirements.txt

# Install all required packages later for new comers.
pip install -r requirements.txt

# Run the web server
flask run
flask --app [app-name] run
flask run --port=5000 --host=0.0.0.0
```
