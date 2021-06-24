# api-quick-start

Template Project for starting up CRUD API with Django Rest Framework

## Customization Steps

- add additional dependencies as needed
- DO NOT migrate yet
- change `cookiestands` folder to the app name of your choice
- Search through entire code base for `CookieStand`,`CookieStands` and `cookiestands` to modify code to use your resource
  - `project/settings.py`
  - `project/urls.py`
  - renamed app's files
    - `views.py`
    - `urls.py`
    - `admin.py`
    - `serializers.py`
- Update CookieStandModel with fields you need
  - Make sure to update other modules that would be affected by Model customizations. E.g. serializers, tests, etc.
- makemigrations/migrate
