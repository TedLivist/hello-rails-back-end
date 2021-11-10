![](https://img.shields.io/badge/Microverse-blueviolet)

# Hello World with two apps: Rails Backend

> This app provides an API endpoint for a randomly generated greeting. It also has two ends: the backend and the front end. The backend is set up with Rails and the front end is set up with React. Both are independent of each other.

## Built With

- Rails

## Getting Started

### Setup

#### To get a local copy up and running follow these simple example steps.

- Click the green `Code` button on the repo
- In your local PC, open your terminal in the folder you would like to clone the project.
- Clone the repo with the command: `git clone (copied link)`; like so: `git clone https://github.com/TedLivist/hello-rails-back-end.git`
- On the terminal, navigate into the directory like so: `cd hello-rails-back-end`
- Checkout to branch name like so: `git checkout [branch name]`

### Installation

- Run `bundle install` to install gems
- Run `yarn install` to install the Javascript dependencies dependencies
- Run `rails db:create` to create Postgres database
- Run `rails db:migrate` to run migrations
- Run `rails db:seed` to populate database with pre-defined seed data
- Run `rails s` to start the application
- Visit the `/api/v1/greeting` to view endpoint

### Usage
This app was built in tandem with another React application. The React is used to make API request to the endpoint provided in this application. The link to the React repo can be found [here](https://github.com/TedLivist/hello-react-front-end)
- Make sure to run this Rails application before running the React app so that it takes up the **3000** port while the React app takes up the **3001** port. This is important for the API call to work
- On the other hand, you can run the React app before the Rails one provided you provide a different port for the Rails app by running this command: `rails server -p <port number>` like so: `rails server -p 3001`. This would mean changing the API call URL to **3001** in the React Application

## Author

👤 **Teddy-Livingstone Ememandu**

- [GitHub](https://github.com/TedLivist)
- [LinkedIn](https://linkedin.com/in/tememandu)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Inspiration