# Symfony Home Nav
Test Routing (Homepage + Navbar) - inside Symfony 5.3

# Change .env file
DATABASE_URL="mysql://root@127.0.0.1:3306/test?serverVersion=mariadb-10.4.21"

# To clone the project
* Go to your work folder with CMD
```bash 
> git clone https://github.com/nadherarroum/Symfony_Home_Nav.git
```
## Launch server
```bash
> symfony serve -d
```

## Requirements
```bash
> composer require symfony/security-bundle
> composer require --dev symfony/profiler-pack
> symfony console make:user
> symfony console make:auth
```
