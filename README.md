# Django-Vue-Template

## Installing the Application
1. Install the base requirements, run the command:
   ```commandline
   $ pip install -r requirements.txt
   ```
2. Migrate all the default db tables, schema, etc., run the command:
   ```commandline
   $ python manage.py migrate
   ```
3. Install Vue globally, run the command:
   ```commandline
   $ npm install -g vue-cli
   ```
   
## Running the Application
1. Navigate to the head directory of the project
2. Run the following command:
    ```
    $ python manage.py runserver
    ```
3. In a separate terminal window, navigate to the directory titled "frontend"
    ```commandline
    $ cd frontend
    ```
4. Run the following command:
    ```commandline
    $ npm run dev
    ```