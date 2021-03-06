# Open-eREACT

## Clone this repo

```shell
git clone git@github.com:AppertaFoundation/Open-eREACT.git
cd Open-eREACT
```

## Front-end development environment

The front-end is built in React. The following instructions should help get the development environment up and running.

Once complete, this will not be required.

## Prep / deps

Install and set up yarn - note that the last step may take a while

```shell
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update
sudo apt install yarn
yarn
```

### Install dependencies

```shell
yarn
```

#### Start with backend auth

(not supported now)

```shell
yarn start
```

#### Start without backend auth

```shell
REACT_APP_NO_BACKEND=true yarn start
```
