
# Fruit Basket

Its a django based web app for the simulation of fruit shop.


## Run locally

To run this project change directory to the project folder and run the command

```bash
  python manage.py runserver
```


## Features

- Two user modes
- Authenticated users can update and delete from  fruit list.
- Normal users can buy the fruits



## Tech Stack

**Client:** HTML, CSS, Javascript

**Server:** Python, Django


## End points

| Endpoints | Function | Users 
|----------:|:--------:|:---------------------------------|
|`/` | Here the list of fruits and their qty with price is present | `Normal` user can buy it and `Authenticated` users can change it.|
|`/add` | `Authenticated` users can add items. | not applicable for `Normal` users |
|`/login` | To `Authenticate` users | not applicable for `Normal` users |
|`/register` | To register users | `Normal` users can register themselves in order to become a privillaged user |
|`/buy` | To Purchase the fruits | `Normal` users can purchase|
|`/update` | To update the fruit details | `Authenticated` users can only update|
|`/delete` | To delete the fruits | `Authenticated` users can only delete|



## Screenshots

`/` (home)

![Screenshot_2023-11-02_19_41_56](https://github.com/hackman01/django-workshop/assets/84094140/d94a11f3-fc5e-4fa2-b0bb-a5fa831dc576)


`/login`

![login](https://github.com/hackman01/django-workshop/assets/84094140/dcd22a26-5460-46bc-b4ac-819f0a2289a8)



`/register`


![register](https://github.com/hackman01/django-workshop/assets/84094140/9b37f908-27fc-449b-b8ee-9d3ca68607b8)



`/` (Authenticated user)


![loginA](https://github.com/hackman01/django-workshop/assets/84094140/b4c615f2-7c65-487f-a858-a5761c2da278)
