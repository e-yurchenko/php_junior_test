# Task to Test Junior Symfony Developer Skills

### Basically, u'll need to bring a small project to manage companies and their employees. Mini-CRM.

**There are a few steps to accomplish this task:**
* Basic Symfony Auth: ability to log in as administrator.
* Use database seeds to create first user with email admin@admin.com and password “password”.
* CRUD functionality (Create / Read / Update / Delete) for two menu items: Companies and Employees.
* Companies DB table consists of these fields: Name (required), email, logo (minimum 100×100), website.
* Employees DB table consists of these fields: First name (required), last name (required), Company (foreign key to Companies), email, phone.
* Use `bin/console doctrine:schema:update --force` to create those schemas above.
* Use validation, using Symfony validation component.
* Use pagination for showing Companies/Employees list, 10 entries per page.
* Use default bootstrap design theme.

**Create REST API**
* Create simple REST API with register,login,etc. functionality.
* Use jwt-token based auth.
* CRUD functionality to Companies and Employees via API methods.

### Extra Task for “Advanced” Juniors
**If you feel like this task is too small and simple, you can add these things on top:**

* Use Datatables.net library to show table – with or without server-side rendering.
* Use more complicated front-end theme like AdminLTE.
* Email notification: send email whenever new company is entered (use Mailgun or Mailtrap).
* Make the project multi-language.
* Basic testing with phpunit.
