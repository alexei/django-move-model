# django-move-model
Django management command for moving a model between two Django apps

## Usage

 1. Move the actual code from one app to the other
 2. Update foreign keys to point to the new model
 3. Run:

        $ python manage.py movemodel ModelName source_app destination_app
