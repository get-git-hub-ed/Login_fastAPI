# Login_fastAPI

Install the dependencies:
pip install -r requirements.txt

Run the API with Uvicorn:
uvicorn src.main:app --reload

Register a user at localhost:8000/register

Log in and get a token at localhost:8000/login

Then use that token as an auth header to get a valid response(username) from the protected endpoint
