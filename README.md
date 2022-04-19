# Image Optimzation Test Bed for Hugo & Netlify CMS

## Getting started
```git clone https://github.com/nate-walters-grafana/image-opt```

## Netlify site address
[https://golden-chimera-697c1e.netlify.app/](https://golden-chimera-697c1e.netlify.app/)

## Running locally
```hugo server```

Site location:
[http://localhost:1313](http://localhost:1313)

Using CMS:
[http://localhost:1313/admin](http://localhost:1313/admin)
- Click "Login with Netlify Identity" button and then choose "Continue with Github"
- If it works, you should be redirected to the netlify site homepage where you'll see a modal "Logged in as YOUR_NAME"
- Go to [https://golden-chimera-697c1e.netlify.app/admin/#/](https://golden-chimera-697c1e.netlify.app/admin/#/)
  - You're in! Not sure, yet, why the redirect doesn't go directly to the CMS
- NOTE: The first time you log in, you may need to enter ```https://golden-chimera-697c1e.netlify.app``` as the URL

## Updating the site
Pushing to master triggers an automatic build

## Netlify functions

Netlify functions are be placed in the "functions" directory.

More (possibly helpful) info on Netlify functions can be found here:
- [How to run Express.js apps with Netlify Functions](https://www.netlify.com/blog/2018/09/13/how-to-run-express.js-apps-with-netlify-functions/)
- [GitHub repo Firebase SDK with Netlify Functions](https://github.com/apotox/firebase-sdk-with-netlify-functions)
- [Firebase Admin SDK with Netlify Lambda Functions](https://jackwhiting.co.uk/posts/using-firebase-admin-sdk-with-netlify-lambda-functions/)


## Other potentially useful info

Hyas -- The [Hyas Hugo template](https://gethyas.com/) has some interesting-looking code for image optimization built-in, might be worth a look-in