## Windows Sail Guide

Problem development windows in wsl. because modify code with [remote development](https://laravel.com/docs/10.x/installation#getting-started-on-windows).

## Tutorial

- Activated Windows Subsystem Linux
- Install Ubuntu
- Install Docker and Start Docker
- create project laravel and install laravel sail on project
- open docker desktop -> settings -> resources -> wsl integration -> choose your ubuntu -> apply and restart

![alt text](https://github.com/mrtampan/windows-sail-guide/blob/main/wslconfig.png?raw=true)

- open wsl ubuntu -> symlink location windows to wsl with command `ln -s \mnt\c\your_project` . example location "\mnt\c\mrtampan-pc\laravel10" 
- run command `./vendor/bin/sail up`


## About repository

Only My research. solving slow development in windows


## Source

https://www.youtube.com/watch?v=JgzSVAQjIkY
