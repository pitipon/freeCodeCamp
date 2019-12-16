# MO README

## Setup FFC project


#### Clone Project
```
git clone --depth=1 https://github.com/YOUR_USER_NAME/freeCodeCamp.git
```
Note: `--depth=1` creates a shallow clone of your fork, with only the most recent history/commit.

#### Node 10.x
```
nvm use 10
node -v
```

#### Install Lerna
```
npm i -g lerna
lerna bootstrap
```

#### Install dotenv
```
npm i dotenv
```

#### Setup the environment variable file
```
# macOS / Linux
cp sample.env .env

# Windows
copy sample.env .env
```

Run Client


