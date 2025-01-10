# django-db-utilities

A utility library for Django to reset databases, models, and primary keys.

## Installation

To install the library, use pip:

```bash
pip install django-db-utilities
```

## Configuration

Add `django_db_utilities` to your `INSTALLED_APPS` in your Django settings:

```python
INSTALLED_APPS = [
    # ...existing apps...
    'django_db_utilities',
]
```

## Usage

### Reset Primary Keys

This command resets the primary keys for a specific model in a selected app by deleting data and resetting primary keys.

```bash
python manage.py reset_primary_keys
```

## Delete Model Data

This command deletes the data for a specific model in a selected app.

```bash
python manage.py delete_model_data
```

### Reset Database

This command resets the database by running migrations and clearing data.

```bash
python manage.py reset_database
```

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
