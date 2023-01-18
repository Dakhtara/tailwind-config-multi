
# Tailwind multi @config with native files

## Install 

``
yarn
``


## How to reproduce the error

Just launch 

``
yarn dev
``


## How to fix for now

Go to assets/admin/scss/main.scss : 

add the config 
``
@config "../../../tailwind.admin.config.js";
``