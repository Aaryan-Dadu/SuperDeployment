# **Level 2**
>### https://l2-super-deploy.vercel.app/
>### https://aaryan-dadu-l2.surge.sh/
>### https://l2-super-deploy-ad.netlify.app/

**There were few errors in package.json like 'react-scripts' and all were not added but used. Also older react syntax of react-dom was used in index.js. The nqueenComponent was misspelled in many areas leading to inconsistency and undefined behaviour. In deployment Vercel had auto detection of react application and minor settings change was required for netlify. For surge, build folder was specified to be deployed and for CI/CD pipeline required dependencies installation command is also passed in deploy.yml.**
