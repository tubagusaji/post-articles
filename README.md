<h1 align="center">Use Case: Post Article.</h1>


## Cara Menjalankan Progrsm
- Download Folder Melalui 
	``` 
    https://github.com/tubagusaji/post-articles
    ```
- Atau Download Melalui Terminal 
	``` 
    git clone git@github.com:tubagusaji/post-articles.git
    ```
- Selanjutnya Ubah File env.example -> menjadi env saja
	```
    .env.example -> .env
    ```
- Selanjutnya Jalankan/Install Program di Composer Pada Terminal
	```
    composer install
    ```
- Selanjutnya Generate Key 
	```
    php artisan key:generate
    ```
- Setelahnya Jalankan Update Composer
	```
    composer update
    ```
- Jalankan Faker Pada Terminal Untuk Masukan Data Random Pada Program
	```
    php artisan migrate:fresh --seed
    ```
- Selanjutnya Jalankan Program
    ```
    php artisan serve
    ```
## Frontend 
- Program Dapat Berjalan Di Browser Dengan Halaman Dibawah (Frontend)
	```
    http://127.0.0.1:8000
    ```
## Backend
- Untuk Backend Program Dapat Berjalan Dengan
    ```
    http://127.0.0.1:8000/api/(data)
    ```
- Test Backend Dapat Dilakukan Melaui POSTMAN -> Dengan Buka Aplikasi Postman Lalu Import Data Yang Ada Di Folder postman
    ```
    Post Articles - Backend.postman_collection.json   
    ```
## Setelah Diimport melalui POSTMAN
- Untuk Buat Post Dengan Create Post  ```POST``` 
    ```
    http://127.0.0.1:8000/api/article
    ```
- Untuk Menampilkan Seluruh Artikel ```GET``` 
    ```
    http://127.0.0.1:8000/api/article
    ```
- Untuk Menampilkan Masing-Masing Artikel ```GET``` 
    ```
    http://127.0.0.1:8000/api/article/{id}
    ```
- Untuk Update Artikel ```PUT``` 
    ```
    http://127.0.0.1:8000/api/article/{id}
    ```
- Untuk Menghapus Artikel```DELETE``` 
    ```
    http://127.0.0.1:8000/api/article/{id}
    ```

