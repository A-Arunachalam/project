#Setup

Start by installing Pipenv using the following command via Pip

pip install pipenv

mkdir enterprise_AI && cd ocr_server && pipenv install --three

We can now activate our virtual environment and start installing our dependencies:

pipenv shell
pipenv install pytesseract Pillow 
