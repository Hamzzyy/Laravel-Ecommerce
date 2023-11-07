## Installation

### Clone Repository

```
https://github.com/ch-hamzzyy/Laravel-Ecommerce.git
```

### Change Directory And Setup Environment
```
cd Laravel-Ecommerce
```
```
cp .env.example .env
```
### Database

`Create a Database Named "ecommerce" which is Default but you can change it in .env file`
* Set your database credentials in your `.env` file

### Install Dependencies 

```
composer install
```
```
npm install
```

### Populate Database 

```
php artisan migrate --seed
```

### Generate Application Key
```
php artisan key:generate
```


### Mail

You need to configure your **Mail** credentials in your '.env' file, in order to enable the registration process and checkouts. if you are using the gmail service
make sure the [less secure app access](https://myaccount.google.com/lesssecureapps) is turned on.

* Set your mail credentials in your `.env` file
* make sure your machine has turned off outbound mail scanning(if you're using antivirus or some kind of firewall)

### Launch the app
```
 php artisan serve
```
```
npm run dev
```

### Note: 
* Before Pushing In Production Make Sure To Run `npm run build`


