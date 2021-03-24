![](https://img.shields.io/badge/Microverse-blueviolet)

# Stay-in-Touch

> This project puts your knowledge of Advanced Topics of Ruby on Rails, among other rail skills to the tests. The aim of the project is to build a Social Media Web-App called "Stay in Touch" that allows users create account, see the timeline, send, recieve or reject friend requests, create posts and comments, like & dislike and be able profiles theirs and those of other users while logged-in.

## Live Demo

[Stay-in-Touch](https://agile-ocean-12616.herokuapp.com/users/sign_in)

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Ruby: 2.6.3
Rails: 5.2.3
Postgres: >=9.5
heroku

### Setup

Clone repository

```
$ git clone `$ git clone https://github.com/jebitok-dev/stay-in-touch`
```

Instal gems with:

```
$ bundle install
```

Setup database with:

```
$ rails db:create
$ rails db:migrate
```

### Usage

Start server with:

```
    rails server
```

Open `http://localhost:3000/` in your browser.

### Run tests

```
    rpsec --format documentation
    rspec spec/models/comment_spec.rb
    rspec spec/models/post_spec.rb
    rspec spec/models/user_spec.rb
```

## Author

👤 **Sharon Jebitok**

- Github: [jebitok-dev](https://github.com/jebitok-dev)
- Twitter: [@jsebitok](https://twitter.com/jsebitok)
- LinkedIn: [Sharon Jebitok](https://www.linkedin.com/in/sharon-jebitok/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/jebitok-dev/stay-in-touch/issues/).
issues).

### How to Contribute

To get a local copy up and running follow these simple example steps.

````
- Fork the repository
- git clone https://github.com/your_username/stay-in-touch
- git checkout develop
- git checkout -b branch name
- run ```$ bundle install```
- $ rails db:create
- $ rails db:migrate
- git remote add upstream https://github.com/jebitok-dev/stay-in-touch
- git pull upstream develop
- git commit -m "commit message"
- git push -u origin HEAD
````

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

[Microverse](microverse.org) and initial forked-project [repository](https://github.com/microverseinc/ror-social-scaffold)

## 📝 License

TBA
