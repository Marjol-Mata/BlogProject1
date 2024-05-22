# BlogProject1

BlogProject1 is a Django-based blogging platform that allows users to create, edit, publish, and delete blog posts. Users can also comment on posts, and comments can be approved or removed by authenticated users.

## Features

- User authentication
- Create, edit, publish, and delete posts
- Comment on posts
- Approve or remove comments
- Draft and publish functionality

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Marjol-Mata/BlogProject1.git
    cd BlogProject1
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Create a `.env` file for environment variables:
    ```env 
    DEBUG=True
    SECRET_KEY=your-secret-key
    DATABASE_URL=sqlite:///db.sqlite3
    ```

4. Apply migrations and start the server:
    ```bash
    python manage.py migrate
    python manage.py runserver
    ```

## Usage

1. Open your browser and go to `http://127.0.0.1:8000/` to view the blog.
2. Use the admin interface at `http://127.0.0.1:8000/admin/` to manage posts and comments.
