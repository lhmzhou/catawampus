# catawampus

To classify images built with a React/Next frontend and a Python/Flask backend. On the frontend, users can upload images and get a classification for said image. The Python/Flask backend app handles the machine learning to classify the uploaded image.

To run the DVC pipeline: `dvc exp run`

## Set up the backend

- Create a virtual environment with: `python3 -m venv .venv`
- Activate the virtual environment with: `source .venv/bin/activate`
- Install all of the dependencies with: `pip3 install -r requirements.txt`

## Set up the frontend

- Go to the root directory and run: `npx create-next-app@latest --ts`



