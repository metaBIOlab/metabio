
## Documentation

[▶️ Get Started](https://github.com/greenelab/lab-website-template/wiki/Get-Started)

[🗚 Basic Formatting](https://github.com/greenelab/lab-website-template/wiki/Basic-Formatting)

[📝 Basic Editing](https://github.com/greenelab/lab-website-template/wiki/Basic-Editing)

[🤖 Automatic Citations](https://github.com/greenelab/lab-website-template/wiki/Automatic-Citations)

[⚙️ Advanced Editing](https://github.com/greenelab/lab-website-template/wiki/Advanced-Editing)

[🧱 Components](https://github.com/greenelab/lab-website-template/wiki/Components)

[🧠 Background Knowledge](https://github.com/greenelab/lab-website-template/wiki/Background-Knowledge)

[💡 Tips](https://github.com/greenelab/lab-website-template/wiki/Tips)

[❓ Support](https://github.com/greenelab/lab-website-template/wiki/Support)


## Local build

Dependencies:
  [Ruby](https://www.ruby-lang.org/pt/downloads/)
  [NodeJS](https://nodejs.org/en/)

Ruby gems:
  gems install bundle

There are many more dependencies but should be indirectly installed already.

Before runing the server locally, go to the containing web folder and run:
  bundle install
  bundle add webrick

Now for the Node server-side local solution:
  npm install netlify

After doing this, there are many options.
  1- Create a new webpage
  2- Clone this repo (git clone http://link.to.this.repo)

For the first option, follow [Netlify guide](https://docs.netlify.com/cli/get-started/). For the second case, follow the same guide but use the manual set-up:
  npm init --manual

and accept the default options (you might need to create an account at [Netlify](https://app.netlify.com)). Skip the build (netlify build) and try to create a local server:
  netlify dev

If it was succsseful, go to your browser and and type in one of the following:
  - localhost:4000/lab-website-template
  - localhost:8000/lab-website-template
  - localhost:8888/lab-website-template
