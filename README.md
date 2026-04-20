# Bloggit

A simple blog application built with Ruby on Rails as a learning project.

## Overview

Bloggit is a lightweight blogging platform developed to explore and understand the fundamentals of Rails web development. This project demonstrates core concepts including MVC architecture, database management, user authentication, and dynamic content rendering.

## Features

- **Create & Manage Posts** - Write, edit, and delete blog posts
- **Responsive Design** - Clean, user-friendly interface
- **Rails Backend** - Robust server-side logic with Rails framework
- **Modern Frontend** - HTML, CSS, and JavaScript for interactive features

## Technology Stack

- **Backend:** Ruby on Rails
- **Frontend:** HTML, CSS, JavaScript, CoffeeScript
- **Database:** Rails default (SQLite/PostgreSQL)

## Project Structure

```
bloggit/
├── app/
│   ├── controllers/     # Application controllers
│   ├── models/          # Data models
│   ├── views/           # HTML templates
│   └── assets/          # CSS, JavaScript, CoffeeScript
├── config/              # Configuration files
├── db/                  # Database migrations
└── README.md            # This file
```

## Getting Started

### Prerequisites

- Ruby (version compatible with Rails)
- Rails framework
- SQLite3 or PostgreSQL

### Installation

1. Clone the repository:
```bash
git clone https://github.com/rbalogic/bloggit.git
cd bloggit
```

2. Install dependencies:
```bash
bundle install
```

3. Set up the database:
```bash
rails db:create
rails db:migrate
```

4. Start the development server:
```bash
rails server
```

5. Open your browser and navigate to `http://localhost:3000`

## Usage

- Navigate to the home page to view existing blog posts
- Click "New Post" to create a new blog entry
- Edit or delete posts as needed
- Posts are displayed with timestamps and full content

## Learning Objectives

This project was built to gain hands-on experience with:

- Rails routing and controllers
- ActiveRecord ORM and database migrations
- View templating and asset management
- CSS styling and responsive design
- JavaScript/CoffeeScript interactions

## Contributing

This is a personal learning project. Feel free to fork and experiment!

## License

This project is open source and available under the MIT License.

## Author

[rbalogic](https://github.com/rbalogic)

---

**Note:** This is a learning project and may not include all features of a production-ready blog application.
