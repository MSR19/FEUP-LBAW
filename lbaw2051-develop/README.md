# lbaw2051

LBAW's repository for Group 51

## Theme 7 - Project management
Our project aims to provide a reliable solution for effective Project Management. Users may use our Application as a tool for managing their projects during their development, taking advantage of our provided features, such as task assignments and revision, forums for discussion and others.

### Group Members:
* João Filipe Carvalho de Araújo, up201705577@fe.up.pt
* Maria Carolina Furtado Soares, up201605010@fe.up.pt
* Mark Timothy Vasconcelos Meehan, up201704581@fe.up.pt
* Miguel Silveira Rosa, up201706956@fe.up.pt

### Install local dependencies
```
composer install
```

### Run pgadmin and postgres docker services
```
docker-compose up
```


### Seed the database and start development server

```
php artisan db:seed
```
```
php artisan serve
```

### Access the project locally
Access http://localhost:8000 to see the app running, after running the commands described above.
The database has been seeded and populated previously.

### Access the project remotely
Access http://lbaw2051.lbaw-prod.fe.up.pt/ to access the app remotely. All the user's credentials are enumerated in the project's wiki page, but here are also a couple:
- Admin of all projects created by the seed:
```
email: jcl@fe.up.pt
password: jclfeup
```
- Normal member:
```
email: markmeehan@hotmail.com
password: jclfeup
```

***

GROUP2051, 03/06/2020