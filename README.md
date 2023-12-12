<div align="center">
  
# House of Wisdom Website 🏛️

![title](pictures/logo.png)

At House Of Wisdom, we believe in the power of education to transform lives, and our Portfolio Project is dedicated to facilitating meaningful connections between Alx students seeking academic support and other Alx students eager to share their expertise.
<br/> <br/>
To take a look at our project, you can visit this website: [House of Wisdom](https://houseofwisdom.vercel.app/)
</div>

## Overview 🌟
1. **Technologies** 
2. **Installation** 
3. **Usage** 🚀
4. **Contributors** 
5. **License** 

## Technologies
***Backend***
- **Flask**: Web framework in Python.
- **MySQL**: Open-source relational database management system.

Libraries

1. **Flask-CORS** 
   - *Description*: Cross-origin resource sharing (CORS) for Flask.

2. **Flask-WTF** 
   - *Description*: Handles form submissions, validates data, and renders forms within Flask views.

3. **Flask-SQLAlchemy** 
   - *Description*: Flask extension simplifying the integration of SQLAlchemy, a SQL toolkit, and Object-Relational Mapping (ORM) library, with Flask applications.

4. **MySQL for Python** 
   - *Description*: MySQL driver for Python.

5. **UUID** 
   - *Description*: Generates UUIDs.

***Frontend***
<!-- You can add specific frontend technologies here -->

***Web server***🌐
- **Nginx** 
- **Gunicorn** 

## Installation 🚀
***Getting Started***

- Clone this repo with --recurse-submodules flag:
```
git clone --recurse-submodules https://github.com/Kerzers/houseofwisdom.git
```
- Go to the repo:
```
cd houseofwisdom
```
- Make sure to install the required dependencies by running: `setup.sh`.
- Go to kns:
```
cd kns
```
- Setup the database by this command:
```
cat setup_db | sudo mysql
```
- Run the Flask application:
```
./run_app.py
```
- In a new terminal with the same path: Add a list of courses in the database by running this command:
```
cat add_courses | sudo mysql
```

## Usage 🚀
1. Access the backend API endpoints for the House of Wisdom website by using the routes if you want to test locally.

## Contributors 🤝
- [AHRA Ahlane](https://github.com/kerzers) - ahra.ahlame@gmail.com
- [EL HAMRANI Omar](https://github.com/RyuzakiiL23) - elhamrani.omar23@gmail.com

🎉 We are grateful to make it this far and bring our own Simple_Shell to life 😊!

## License 📜
This project is licensed under the MIT License Copyright (c) 2023 Omar EL HAMRANI Ahlame AHRA.
