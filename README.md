# Stripe Payment Gateway Integration in laravel 5.8
<hr>
Please follow the steps to run the above project.<br>
If you want integration details please read <b>"users guide.xlxs"</b> file which describes about packages and installation process.<br><hr>

1. Copy the clone link or you can download zip. <br>
2. Go to xampp/htdocs open cmd window and type below command : <br>
    <b>git clone https://github.com/ashish744737/stripe-payment.git</b>
3. Go to project folder and within project open cmd and update composer : <br>
    <b>update composer</b>
4. Create <b>.env</b> in root directory same as <b>.env.example</b> and set <b>APP_URL=http://localhost/stripe-payment</b> or as per        your localhost environment.<br>
5. Generate <b>APP_KEY</b> by using following command.<br>
    <b>php artisan key:generate</b><br>
6. Go to .env file and set database details <br>
    <b>DB_CONNECTION=mysql</b><br>
    <b>DB_HOST=127.0.0.1</b><br>
    <b>DB_PORT=3306</b><br>
    <b>DB_DATABASE=database name</b><br>
    <b>DB_USERNAME=database username</b><br>
    <b>DB_PASSWORD=database password</b><br>
7. Go to <b>.env</b> and add your Stripe creadentials as follows: <br>
    <b>STRIPE_KEY=</b><br>
    <b>STRIPE_SECRET=</b><br>
8. Now you can run your project.
<hr>
<b>Ashish Avinash Pasekar</b><br>
ashish.pasekar@gmail.com
    
    
