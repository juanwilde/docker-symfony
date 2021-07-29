# docker-symfony

This repository contains all the code explained in this [**YouTube playlist**](https://www.youtube.com/playlist?list=PLWpsZlKx38t9SEQu6_AbzBoHeQbApIcjJ)

### Scripts
*Using **Makefile***: https://makefiletutorial.com/

Installs composer dependencies

```shell
make prepare
```

Build the containers

```shell
make build
```

Start the containers

```shell
make run
```

Stop the containers

```shell
make stop
```

Restart the containers

```shell
make restart
```

### Steps to follow

Init the bash shell into the **Backend container**

```shell
make ssh-be
```

Update packages

```shell
composer update
```

Install packages

```shell
composer install
```


### Optional
*Use dry to manage docker*: https://github.com/moncho/dry#installation

```shell
curl -sSf https://moncho.github.io/dry/dryup.sh | sudo sh
sudo chmod 755 /usr/local/bin/dry
```

Listen docker containers

```shell
dry
```