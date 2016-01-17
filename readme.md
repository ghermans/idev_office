## iDevelopment Staff portal

This is the current portal for iDevelopment's staff.

## Features

- Application tools
- Blog
- Request application rights.
- Network alerts
- Domain registration
- SSL registration and provisioning in Plesk.


## Installation
- Install nodejs if not intalled (chmod +x install_nodejs.sh and run ./install_nodejs.sh)
- run composer install
- Edit .env_example and save to .env
- Setup cronjob * * * * * php /path/to/artisan schedule:run >> /dev/null 2>&1
