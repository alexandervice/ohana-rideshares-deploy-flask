# Ohana Rideshares

This used to be deployed and hosted with AWS. Please contact me if you want me to restart the instance.

Ohana Rideshares is a Flask Python Project that allows for account registration and login to then request a ride from other users, choose to drive other riders, view ride details, and leave messages to the rider and/or the driver.

## Installation

```bash
pipenv install -r requirements.txt
```

You will also need to create the database from the ohana-rideshares-schema.mwb in MySQL, otherwise you won't be able to use the project properly.

If the requirements.txt file does not work

```bash
pip install flask PyMySQL flask-bcrypt
#navigate to the ohana rideshare folder
pipenv install flask PyMySQL
pipenv shell
pipenv install flask-bcrypt
```

## How to Run

```bash
pipenv shell
python server.py
```

## Screenshots

![Ohana all rides](https://github.com/alexandervice/ohana-rideshares-deploy-flask/blob/main/images/ohana-all-rides.png)

![Ohana ride details](https://github.com/alexandervice/ohana-rideshares-deploy-flask/blob/main/images/ohana-ride-details.png)

![Ohana login](https://github.com/alexandervice/ohana-rideshares-deploy-flask/blob/main/images/ohana-login.png)

![Ohana ride request](https://github.com/alexandervice/ohana-rideshares-deploy-flask/blob/main/images/ohana-ride-request.png)

![Ohana user details](https://github.com/alexandervice/ohana-rideshares-deploy-flask/blob/main/images/ohana-user-info.png)

![Ohana schema](https://github.com/alexandervice/ohana-rideshares-deploy-flask/blob/main/images/ohana-schema.png)
