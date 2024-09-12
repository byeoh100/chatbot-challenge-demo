<p align="center">
  <img src="./DoD_logo_red.svg" width=300px>
</p>

# Deal or Dragon

**Deal or Dragon**, formerly known as Chatbot Challenge, is a standard dungeon crawler with a twist: instead of *fighting* the monsters, you are trying to convince them to *buy* an item.

## Collaborators
* Len Kedrow
* Kyle Bleeker
* Brandon Yeoh
* Erika Holzinger
* Christopher Roberts

## Features
* **Account Creation**
    * Users can create an account to track characters and wins/losses.
* **Unique characters**
    * User created characters have stat points that can be allocated to influence the way that the monsters percieve you.
* **AI powered**
    * Each monster is a custom-trained ChatGPT chatbot model that responds accordingly to the conversation with the player.
    * AI powered monsters allow for a unique and reactive playthrough on every interaction.

## How to install and run
To run the backend: <br/>
* `cd backend`
* `pip install -r requirements.txt`
* `cd chatbot_proj`
* `python manage.py runserver`

To run the frontend: <br/>
* `cd frontend/chatbot`
* `npm install`
* `npm run dev`

## Built With:
* React/Vue
* Django
* PostgreSQL
* ChatGPT