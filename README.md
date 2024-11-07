# Steps

- Create and navigate inside a directory: `ls`, `mkdir`, `cd`, `code .`
- To create html and open it using `live-server`
- Add some content and link `new-css`
- Render current year using the Date class
- We want to host this website to make it available on the internet
- Services: github pages, netlify, pages.dev
- I want to store this code on github
- A repository on github is a like a folder on your system

# Steps for Deployment

1. Pehle hmne vs code use karke ek website banai
2. Uska code github pe upload kar diya (drag)
3. Uska sharable link generate karna hoga
4. We will use github pages
5. Go into your repository settings
6. Search for Pages and then select branch
7. That's it you'll have a sharable deployed link of your website: https://gliese-sketch.github.io/headphones-test/

# To install Parcel

1. `pnpm init`: This will create a new file called package.json
1. `pnpm install --save-dev parcel`: This will install parcel as a dev dependency
1. In our package.json file, add the following line to the scripts section:

```json
"scripts": {
  "start": "parcel index.html"
}
```

3. In the terminal, navigate to the root directory of your project and run the following command:

```bash
pnpm start
```

This command will start the development server and open your website in a new browser tab.
