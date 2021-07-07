![](https://img.shields.io/badge/Microverse-blueviolet)

# Re-Former - Bare Metal Forms and Helpers

This is an educational project to learn about forms using Ruby on Rails.

## Built With

- ![](<https://img.shields.io/badge/-Ruby on Rails-rgb(199%2C%2032%2C%2039)?style=plastic&logo=ruby>)
- ![](<https://img.shields.io/badge/-PostgreSQL-rgb(10%2C%2032%2C%2039)?style=plastic&logo=postgresql>)

### Prerequisites

PostgreSQL should be installed before using this. Make sure that it is install by entering the following command on the terminal `postgres --version`</br>
If no version provided you will need to install it. [Get PostgreSQL](https://www.postgresql.org/download/).

## Getting Started

To get started first clone this project by using the following command `git clone https://github.com/ad9311/re-former.git`</br>
Then change directory into the project's directory `cd re-former`</br>
Before starting the application you will need to run a few commands:</br>

```
bundle install
```

After this it is required to create a new database and migrate it:

```
rails db:create
rails db:migrate
```

After this the database should correctly set up.

Now access the project using the following link http://127.0.0.1:3000</br>

You will be presented with a form and where you can create a new user. Please keep in mind that the username and the email must be unique and the username and password must have between 6 to 16 characters.</br>

To edit a user type in the address bar /[user_id]/edit. It should look something like this http://127.0.0.1:3000/users/4/edit where 4 is the id of the user you wish to edit.</br>

To the id of all users you can use Rails console, like this:

```
rails c
User.all
```

This will display all user and their id's.</br>

If you want to delete the datatable completely run the following command:

```
rails db:drop
rails db:create
rails db:migrate
```
## Authors

**Ángel Díaz**

- GitHub: [@ad9311](https://github.com/ad9311)
- Twitter: [@adiaz9311](https://twitter.com/adiaz9311)
- LinkedIn: [Ángel Díaz](https://www.linkedin.com/in/ad9311/)

## Show your support

Give a ⭐️ if you like this project!

## 📝 License

This project is [MIT](./LICENSE) licensed.