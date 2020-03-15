# Readme

We are using Github-pages to host the site.
Beause is an organization page (not a project), it requires to be deployed to Master (can't use the `gh-pages` branch).

So, when you develop you will have to checkout the `dev` branch.

Other than the above is just a React Create App static page.

---

To develop:

```
npm install
npm start
```

To deploy to Master (from `dev` branch):

```
npm run deploy
```