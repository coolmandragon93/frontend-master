# unitedpos

> United POS

## Installation

```sh
$ git clone git@github.com:coolmandragon93/frontend.git
$ cd frontend/
$ npm install
$ npm run dev
```

## Server SSH Login
```sh
$ ssh ubuntu@18.218.55.26
```
> show database and list down collections
```sh
$ mongo
$ use UnitedPOS
$ show collections
```
> check logs of backend service
```sh
$ tail /var/log/post_system.log
```
> restart backend service
```sh
$ sudo service pos_system restart
```
> check nginx configuration 
```sh
$ cat /etc/nginx/sites-enabled/default
```