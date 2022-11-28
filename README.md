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
![Create Post](https://user-images.githubusercontent.com/89891460/204321501-1fd65cb4-c3ee-4d09-b579-8fe4ca242799.png)
- Untuk Menampilkan Seluruh Artikel ```GET``` 
    ```
    http://127.0.0.1:8000/api/article
    ```
![Menampilkan Post](https://user-images.githubusercontent.com/89891460/204322582-de661f21-08cd-4392-955b-c77a2ffa73ce.png)
- Untuk Menampilkan Masing-Masing Artikel ```GET``` 
    ```
    http://127.0.0.1:8000/api/article/{id}
    ```
![Masing2 Artikel](https://user-images.githubusercontent.com/89891460/204321973-574d5cf2-aa3f-4e0f-a958-32effd1ed8e4.png)
- Untuk Update Artikel ```PUT``` 
    ```
    http://127.0.0.1:8000/api/article/{id}
    ```
![Update Artikel](https://user-images.githubusercontent.com/89891460/204322052-8eae6f3f-93ac-4ab9-9d5f-c3fff944bfb2.png)
- Untuk Menghapus Artikel```DELETE``` 
    ```
    http://127.0.0.1:8000/api/article/{id}
    ```
![Hapus Artikel](https://user-images.githubusercontent.com/89891460/204322169-3057ff23-ed8c-4898-9448-9571fcd81099.png)
