a. Clone the GitHub repository
Inside the root folder of your local web development environment, open a new terminal window.
Enter the command :

git clone https://github.com/liridonkrasniqi13/liridon-app.git
Change directory into the newly created project folder.

b. Install Composer Dependencies
Enter the command : 

composer install

c. Install NPM Dependencies
Enter the commands : 

npm install
npm run dev

c. Install NPM Dependencies
Enter the commands : 

npm install
npm run dev


e. Generate an App Encryption Key
Enter the command :
php artisan key:generate

f. Create an empty database for our application
Use your favorite database management tool to create an empty database.
Configure a username and password.

g. Configure the .env file
Open the .env file for editing :
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=liridon-app
DB_USERNAME=root
DB_PASSWORD=


h. Migrate the database
Enter the command : :
php artisan migrate


Finish 

php artisan serve

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
