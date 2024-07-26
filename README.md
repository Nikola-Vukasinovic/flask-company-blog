# Company blog demo project with Flask

## Demo company blog in Flask demonstrating features like creating &amp; updating blog posts

### Prerequisites

Please find attached *requirements* file inside project for needed packages.

Development was made with Python version 3.6 and tested with version up to 3.8.

Currently project used Boostrap version 4 but with limited scope of use it is easy to port this to version 5.

For any align meta tag please note that this is depracted and should be removed.

### Running the app

Project comes with presetup SQLite with SQLAlchemy and Migrate. If you want to start fresh feel free to delete *migrations* and *database* file and reinit with **flask db** commands.

```
flask db init
flask db migrate -m "<text>"
```

Running on localhost with Python version 3.6.

Recommended is venv setup with requirements file.
