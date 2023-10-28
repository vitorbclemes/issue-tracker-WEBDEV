# Issue Tracker

This project was develop for studying different concepts on Web Developing. It explores several different libraries that can be used with NextJS.  
The main libraries and technologies studied during this development were:  
  - Tailwind CSS  
  - Prisma integration with MySQL  
  - ZOD  
  - RadixUI  
  - React Hook Forms

In my opinion, RadixUI takes the winner trophy from this project, as I observed how easy it is to make beautifull components that would take long time styling.

# How to run it

First, you must setup you database. For that, be sure that you are running a MySQL server in your background, Then, create a ```.env``` file inside the project root folder and provide the following key:  
  
```DATABASE_URL="mysql://<your.username>:<your-password>@localhost:3306/issue-tracker"```  
  
Do not forget to replace your username and password in the URL.  
  
Following, remember to run ```npm i``` to install all dependencies you will need. Then, you are ready to try it by running:  

  ```npm run dev```

And access it in your local port 3000.
