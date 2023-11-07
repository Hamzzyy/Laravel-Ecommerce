## Installation

Clone Repository

```
https://github.com/ch-hamzzyy/Laravel-Ecommerce.git
```

Change Directory And Setup Environment
```
cd Laravel-Ecommerce
```
```
cp .env.example .env
```
### Database

`Create a Database Named "ecommerce" which is Default but you can change it in .env file`
* Set your database credentials in your `.env` file

Install Dependencies 

```
composer install
```
```
npm install
```

Populate Database 

```
php artisan migrate --seed
```

Generate Application Key
```
php artisan key:generate
```


### Mail

You need to configure your **Mail** credentials in your '.env' file, in order to enable the registration process and checkouts. if you are using the gmail service
make sure the [less secure app access](https://myaccount.google.com/lesssecureapps) is turned on.

* Set your mail credentials in your `.env` file
* make sure your machine has turned off outbound mail scanning(if you're using antivirus or some kind of firewall)

Launch the app
```
 php artisan serve
```
```
npm run dev
```

### Note: 
* Before Pushing In Production Make Sure To Run `npm run build`
## Screenshots

### home page :point_down:
<kbd>![home page](https://github.com/kunal254/laravel-8-ecommerce/blob/main/public/screens/home.png)</kbd>
### Cart :point_down:
<kbd>![cart](https://github.com/kunal254/laravel-8-ecommerce/blob/main/public/screens/cart.png)</kbd>
### user order :point_down:
<kbd>![user profile](https://github.com/kunal254/laravel-8-ecommerce/blob/main/public/screens/user_order.png)</kbd>
### admin dashboard :point_down:
<kbd>![admin dashboard](https://github.com/kunal254/laravel-8-ecommerce/blob/main/public/screens/admin_dashboard.png)</kbd>

### responsive :tired_face:

<kbd><img src="https://github.com/kunal254/laravel-8-ecommerce/blob/main/public/screens/orders_on_phone.jpg" alt="drawing" height="350"/></kbd>&nbsp;&nbsp;&nbsp;<kbd><img src="https://github.com/kunal254/laravel-8-ecommerce/blob/main/public/screens/adminORD_on_phone.jpg" alt="drawing" height="350"/></kbd>&nbsp;&nbsp;&nbsp;<kbd><img src="https://github.com/kunal254/laravel-8-ecommerce/blob/main/public/screens/cart_on_phone.jpg" alt="drawing" height="350"/></kbd>&nbsp;&nbsp;&nbsp;<kbd><img src="https://github.com/kunal254/laravel-8-ecommerce/blob/main/public/screens/shop_on_phone.jpg" alt="drawing" height="350"/></kbd>

