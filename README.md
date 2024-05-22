# Laravel 10 with inertia and Vue JS 3 - Ecommerce
## Feature: 
- shipping with Raja Ongkir https://rajaongkir.com
- Paymentgateway with Midtrans https://midtrans.com

## Screenshots Frontend
![Screenshot_2023-12-02_03-41-20](https://github.com/titoyudha/Vcommerce/blob/master/screenshot/287423656-491689ac-f518-4f1c-b1c8-7593028c6be3.png)



## Donwload

Clone Projek

```bash
  git clone https://github.com/titoyudha/Vcommerce.git
```

Masuk ke folder dengan perintah

```bash
  cd `project_directory`
```

-   Copy .env.example menjadi .env kemudia sesuaikan dengan konfigurasi local database dan api key nya

```bash
    composer update
    composer install
    npm install
```

```bash
    php artisan key:generate
```

```bash
    php artisan artisan migrate:fresh --seed
```

#### Login User
- email = user@gmail.com
- psswrd = 1245678

#### Login Admin

-   email = admin@gmail.com
-   password = 87654321
