# chatgpt-artifacts

Bring Claude's Artifacts feature to ChatGPT

## Preview

<img src="./preview/Screenshot 2024-06-28 at 7.57.19 PM.png" alt="" width="600" />

## Usage

Clone this repository

```
git clone https://github.com/ozgrozer/chatgpt-artifacts.git
```

Install dependencies

```
npm install
```

Duplicate `.env.example` as `.env` and add your OPEN AI API key

```
cp .env.example .env
vim .env
```

Build the app

```
npm run build
```

Start the app

```
npm start
```

with 1Password CLI

```shell
alias op_env='op run --env-file=".env_op" --no-masking --'
alias npm_op='op_env npm'
npm_op start
```

## License

[GPL-3.0](https://github.com/ozgrozer/chatgpt-artifacts/blob/main/license)
