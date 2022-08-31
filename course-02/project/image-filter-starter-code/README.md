# Udacity - TDD Course

## Project Rubrik

### Engineering Process and Quality
- > The project demonstrates an understanding of a good cloud git process
    - Project has been stored in the forked repository aristotelissym/cloud-developer. Moreover, the DEV branch is named **dev-symeoa**, since there where two additional branched (dev, stg)
- > The project demonstrates an ability to use typescript and Nodejs
    - Variabled for the finishing project were not used. Either than that, good coding practices are followed.

### Development Server
- > The project demonstrates the ability to develop using the NodeJS framework
    - DEV server is working as expected. First run `npm i` to install the required packages.
- > The project demonstrates an understanding of RESTFUL design
    - The stubbed `@TODO1` endpoint is completed and does the expected actions. 
        - https://cdn.dribbble.com/users/4194891/screenshots/10564920/media/046862ed5f82420ec925933ceca255c2.png
- > The project demonstrates an understanding of HTTP status codes
    - It returns a statusCode of _400_ if an **image_url** is not provided, with a display message. Also, it returns a statusCode of _200_ when a URL is provided.

### Elastic Beanstalk Deployment
- > The project demonstrates the ability to create functional cloud deployments
    - http://image-filter-starter-code-dev2222222222222222222222222.us-east-1.elasticbeanstalk.com/
- > The project demonstrates an understanding of AWS Elastic Beanstalk’s CLI and Console Dashboard
    - The project was built with the command `npm run build` which I had to customize because I use Windows 10 and I don't have the zip command. So I use the **7zip** tool. Moreover, the paths with the backslashes couldn't be used in Window's *cmd*. 
        - `npm run clean && tsc && cp package.json www\\package.json && mkdir www\\tmp\\ && cd www && '%PROGRAMFILES%\\WinRAR\\WinRAR.exe' a -afzip .\\www\\Archive.zip && cd ..`

        ![EB Screenshot](deployment_screenshots\EB-screenshot-Aristotelis-Symeonidis.png)