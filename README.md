<h1 align="center">Project "PhotoSHAKE" from team "CHANEL N°5"</h1>

<p align="center">
  <a href="#about">About</a> &#xa0; | &#xa0; 
  <a href="#Usage ">Usage </a> &#xa0; | &#xa0;
  <a href="#Features ">Features </a> &#xa0; | &#xa0;
  <a href="#Technologies ">Technologies </a> &#xa0; | &#xa0;
  <a href="#starting">Starting</a> &#xa0; | &#xa0;
  <a href="#made-by">Made by</a> &#xa0; | &#xa0;
  

</p>

<br>

##  About ##

Photo Share is a web application that allows users to share, comment, and search photos.


##  Usage 

This project exposes many endpoints through a REST API. To access these APIs, use any API client. The API documentation can be found at documentation.


##  Features

User authentication: Users can create accounts, log in, and log out.\
Image upload: Users can upload images to share with others.\
Image comment: Users can leave comments under each others images.\
Image search: Users can search for images by tag.

##  Technologies

In this project we used the following technologies:\

Python\
FastAPI\
PostgreSQL (for the database)\
Docker (for containerization)\
Other dependencies listed in requirements.txt and package.json

##  Starting

To run the Photo Share project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/Dmytro-Tarasenko/PhotoShare
   ```

2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
   Create file `.env` using `.env.example`.


3. Set up the database:
   - Run `docker-compose up -d` to create Docker container.
   - Create a PostgreSQL database named `photo_share` or other name that you put in your `.env` file.
   - Run `alembic upgrade head` to install migration in DB.
   

4. Run the application:
   ```sh
   uvicorn main:app --host localhost --port 8000 --reload
   ```

5. Access the application at `http://localhost:8000` or `127.0.0.1:8000` in your web browser.


##  Made by

Made with  by "CHANEL N°5":\
:fire: [Dmytro Tarasenko](https://github.com/Dmytro-Tarasenko)\
:fire: [Denys Poletuchiy](https://github.com/ArleKinG44)\
:fire: [Angelika Kodlubovska]()\
:fire: [Sergiy Chabanchuk](https://github.com/chabanchuk)\
:fire: [Maksym Melnyk](https://github.com/Resst94)\
:fire: [Oleksandr Buts](https://github.com/Oleksandr190378)


&#xa0;

<a href="#top">Back to top</a>
