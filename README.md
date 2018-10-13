# UnivForum
Simple Forum creted using Django to discuss any topics. Ideal for Universities and Schools to discuss Subjects

## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone git@github.com:sibtc/django-beginners-guide.git
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Setup the local configurations:

```bash
cp .env.example .env
```

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.
