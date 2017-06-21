# ecs_s3_scraper_start
This repo is the starter for [ecs_s3_scraper](https://github.com/anishk123/ecs_s3_scraper). The idea being that if you clone this repo and follow the setup steps below, then it becomes super easy to follow along the hands-on coding in the ecs_s3_scraper.

## How to get the most out of this repo
Just follow the steps below, and if you notice any failures, then please log an [issue](https://github.com/anishk123/ecs_s3_scraper_starter/issues)

0. [Install node and npm](https://nodejs.org/en/download/package-manager/)

   *Note: v6 or v7 should be fine*

1. Install yarn package manager
```$ npm install -g yarn```

2. Git clone this repo in a directory of your choice, if you haven't already.
    
    ```$ git clone https://github.com/anishk123/ecs_s3_scraper_starter.git```

3. Get to the working directory
```$ cd ecs_s3_scraper_starter```

4. Run yarn install
```$ yarn install```

   *Note: the above will install the libraries and dependencies required for the project*

5. Run index.js
```$ node index.js```

   *Note: the above will open up a web browser written in electron, that will search the keyword "code and coffee vancouver"*

6. [Download Docker](https://www.docker.com/get-docker) - Docker CE is the free version

7. Download a nightmare docker image
```$ docker pull ivanvanderbyl/docker-nightmare```

   *Note: We will be adding our own web scraper code to this image.*
   
8. Download a fake S3 docker image
```$ docker pull lphoward/fake-s3```

   *Note: This image will be used to run a mock S3 service that we can develop our code against, instead of using actual AWS S3*

**You are DONE! and ready to rock on over to [ecs_s3_scraper](https://github.com/anishk123/ecs_s3_scraper)**
 
