# PANGAN API SERVICE

Pangan service merupakan Sistem Informasi guna memperoleh data ketersediaan pangan oleh petani dan jumlah permintaan konsumen agar adanya kesetabilan harga pasar 

## Instalasi

- download repository pangan-service

``git clone https://github.com/hudabikhoir/pangan-service.git``

- download package yang diperlukan melalui composer

``composer install`` 

``composer update``

- setting .env sesuaikan dengan host anda

- jalankan perintah migration lumen

``php artisan migrate``

- run pangan-service kamu

``php -S localhost:8080 -t public``

## Register & Login

| 		URL         | HTTP Method |               Response                |
|:-----------------:| :---------: |:--------------------------------------:|
| /register      |  POST 	      | {" success": true, "message": "Success register!"}   |
| /login      |  POST 	      | {
    "success": true,
    "api_token": "7248f632cf846c9fd34b1085c8d8141ae75f9680",
    "message": {
        "id": 1,
        "username": "huda",
        "email": "huda@mail.com",
        "id_role": 1,
        "remember_token": null,
        "created_at": "2018-03-13 04:49:05",
        "updated_at": "2018-03-13 06:09:37",
        "deleted_at": null
    }
}   |