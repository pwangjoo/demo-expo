# README.md
React starting guide for MacOS (M1).
<br />Result of this page can be seen [here](https://pwangjoo.github.io/demo-react/).

## Preparation
### 1. Using `nvm`
```zsh
% brew install nvm #Homebrew installation
% nvm list #show list of installed nodes
% nvm install [VERSION] #install certain version of node
% nvm use v[VERSION] #temporarily use certain version of node
% nvm alias default v[VERSION] #permanently use certain version of node
```

## Initializing
### 1. Generating new project
```zsh
% npm install --global eas-cli #install eas-cli
% npx create-expo-app -t expo-template-blank-typescript #generate new typescript project
% eas init --id [APPID] #link existing project
```
### 2. Modify
1. Modify `package.json`.
    ```json
    {
      "scripts": {
        ...
        "ts:check": "tsc"
      }
    }
    ```

## Running
1. Start server.
    ```zsh
    % npm run start #development & debug mode
    ```
1. Scan QR using your phone.