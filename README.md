## Shadow dockers
* Holding configuration for DB

## Getting support
If there are any problems, please feel free to contact to me or create new pull request  
* Email: trungvu.inside@gmail.com
## Check out sources
* git clone git@github.com:chariot9/shadow-docker.git
## Compile and run API
Build all images:
* Execute: /bin/build.sh 
Push to repository:
* docker tag db-news:database chariot9/db-news:database
* docker push chariot9/db-news:database
Start containers:
* docker-compose up -d
## License
Created by Trung, Yokohama Japan 2017 
