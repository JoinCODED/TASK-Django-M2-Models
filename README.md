# Task

For the task below, take advantage of this [model field reference](https://docs.djangoproject.com/en/4.0/ref/models/fields/).

1. Set up a `virtual environment`.
2. Create a `Django` project.
3. Create a `requirements` file.
4. Initialize a local `Git` repository.
5. Create a `.gitignore` file (make sure wherever you copy the contents from, it includes `.venv`).
6. Create and install an app called `restaurants`.
7. Create a model called `Restaurant` with the following fields:
   - `name`: string field type with a maximum of 30 characters.
   - `description`: string field type with no character limitations that defaults to an empty string.
   - `opening_time`: time field type.
   - `closing_time`: time field type.
   - `created_at`: datetime field that defaults to the datetime the object was created in.
8. Push your project to a remote repository (`GitHub`).

## Bonus

Open an interactive django shell, import your model, and create some objects.
