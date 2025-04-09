# **Level 1**
>### https://l1-super-deploy.vercel.app/
>### https://adl1-super-deploy.netlify.app/
>### https://l1-superdeploy.onrender.com/
>### https://aaryan-dadu-l1.surge.sh/

**Similar things as in Level 0. But the vercel.json required fixes like it was having function and build together but either one of them is expected by vercel not both. Also routes was redirecting every request to index.html that's why all the requested resources in the end had html as payload. Also site.webmanifest had wrong path so it also needed a fix. CI/CD pipeline is auto in vercel and netlify and used similar .yml file for surge to establish a CI/CD pipeline.**
