# depand.io

example #1

> ~$dp create myprj1 by zhuangbiaowei/rails-warden-mongodb
> 
> download template zhuangbiaowei/rails-warden-mongodb ... 100%
> 
> create project by template
> 
> install rails ... 100%
> 
> install mongodb ... 100%
> 
> install warden ... 100%
> 
> mkdir myprj1
> 
> cp files ... 100%
>
> done!

example #2

> ~$mkdir myprj2
> 
> ~$cd myprj2
> 
> ~/myprj2$dp using zhuangbiaowei/rails-warden-mongodb
> 
> download template zhuangbiaowei/rails-warden-mongodb ... 100%
> 
> install rails ... 100%
> 
> install mongodb ... 100%
> 
> install warden ... 100%
> 
> cp files ... 100%
>
> done!

example #3

> ~/myprj2$dp add-package ruby:rails_warden
> 
> ~/myprj2$dp add-package ruby:oauth
> 
> ~/myprj2$dp register zhuangbiaowei@gmail.com
> 
> ~/myprj2$dp publish rails-warden-mongodb-oauth
> 
> zhuangbiaowei/rails-warden-mongodb-oauth version=0.1 published!  


expamle #4

> ~$dp create myprj3 by zhuangbiaowei/rails-warden-mongodb-oauth
> 
> ~$cd myprj3
> 
> ~/myprj3$dp add-config config/oauth.yml
> 
> ~/myprj3$vim config/oauth.yml
> 
> ~/myprj3$dp modify-config config/database.yml
> 
> ~/myprj3$dp publish rails-warden-mongodb-oauth version=0.2