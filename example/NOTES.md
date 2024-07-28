## Original Code
- had to go back to Node 16 to do an npm run build
- used npm ci instead of npm install due to mismatched environments
- had to use 127.0.0.1:5000 instead of localhost:5000
  - this is due to Airplay receiver running on port 5000 on MacOS monterey+
  - see [post](https://stackoverflow.com/questions/70913242/access-to-localhost-was-denied-you-dont-have-authorization-to-view-this-page-h) for more details

## Code after merging in PR https://github.com/firebase/firebaseui-web-react/pull/173
- Now automatically switches to port 5005
- had to build actual package locally (still using ci)
- seems to still be working