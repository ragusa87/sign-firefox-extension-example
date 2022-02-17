
# Setup
Copy the env file

> cp .env.dis .env

Install npm packages

> npm install

## Edit .env

- Adapt the version based on the src/manifest.json of the main project
- Be sure you own the UUID that is on the manifest, or generate a new one <https://duckduckgo.com/?&q=uuid&ia=answer>
- Get your JWT Credentials on <https://addons.mozilla.org/developers/addon/api/key/>

# Sign the app
> npm run sign

# Install the app manually
Open firefox > extension > install from file

