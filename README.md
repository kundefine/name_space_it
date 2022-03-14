#Shorting Url
# name_space_it

#.env setup
```
cp .env.example .env
```
#setup database (name, username, password)
```
DB_DATABASE=namespace_it_url_short
DB_USERNAME=root
DB_PASSWORD=
```


 
#Intall all the Dependencies
- please run
    
 ```
composer install 
php artisan key:generate
php artisan migrate
npm install && npm run dev
```
