# SuperDeployment
L0
https://l0-super-deploy.vercel.app/
https://coruscating-peony-ace7a8.netlify.app/
https://aaryan-dadu.surge.sh/

I deployed the Level 0 project on vercel, netlify and surge.
For vercel and netlify GUI is present using which deploying the Level 0 was like a piece of cake. Just login chose the project and deployed.
For surge it has a shell using its basic 2 commands one can deploy their website and can even provide custom domain names.
CI/CD pipeline is auto established for vercel and netlify so just push and the work is done it will deploy too.
For surge I created a deploy.yml file to deploy to surge which basically in the virtual machine provided by the github copies our repo and cd to the dir we want to deploy or build and then using my surge credentials deploys using the surge command on my custom domain site every time I push the code (using triggers). It uses SURGE_LOGIN and SURGE_TOKEN.



L1
https://l1-super-deploy.vercel.app/
https://adl1-super-deploy.netlify.app/
https://l1-superdeploy.onrender.com/
https://aaryan-dadu-l1.surge.sh/

Similar things as in Level 0. But the vercel.json required fixes like it was having function and build together but either one of them is expected by vercel not both. Also routes was redirecting every request to index.html that's why all the requested resources in the end had html as payload. Also site.webmanifest had wrong path so it also needed a fix.
CI/CD pipeline is auto in vercel and netlify and used similar .yml file for surge to establish a CI/CD pipeline.


L2
https://l2-super-deploy.vercel.app/
https://aaryan-dadu-l2.surge.sh/
https://l2-super-deploy-ad.netlify.app/

There were few errors in package.json like 'react-scripts' and all were not added but used. Also older react syntax of react-dom was used in index.js. The nqueenComponent was misspelled in many areas leading to inconsistency and undefined behaviour.
In deployment Vercel had auto detection of react application and minor settings change was required for netlify. For surge, build folder was specified to be deployed and for CI/CD pipeline required dependencies installation command is also passed in deploy.yml.


L3
https://l3-superdeploy.onrender.com/todos
Many minor bugs were present. A db folder is required to create the todos.db and add table in it which was missing. Minor fixes were required in db.run query, an extra comma was present. Nodemon was used but was not present in package.json. The functionality of put request was wrong as the value of completed was getting set at title and that of title was setting at completed.
Deployed on render


L4
