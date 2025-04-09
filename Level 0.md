# **Level 0**
>### https://l0-super-deploy.vercel.app/
>### https://coruscating-peony-ace7a8.netlify.app/
>### https://aaryan-dadu.surge.sh/

**I deployed the Level 0 project on vercel, netlify and surge. For vercel and netlify GUI is present using which deploying the Level 0 was like a piece of cake. Just login chose the project and deployed. For surge it has a shell using its basic 2 commands one can deploy their website and can even provide custom domain names. CI/CD pipeline is auto established for vercel and netlify so just push and the work is done it will deploy too. For surge I created a deploy.yml file to deploy to surge which basically in the virtual machine provided by the github copies our repo and cd to the dir we want to deploy or build and then using my surge credentials deploys using the surge command on my custom domain site every time I push the code (using triggers). It uses SURGE_LOGIN and SURGE_TOKEN.**
