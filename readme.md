# Pulumi AWS TypeScript by CangleCode

## Link to video tutorial on YouTube

[Jamstack Contact Form Microservice with Pulumi & AWS Serverless / Infrastructure as Code [PART 2]](https://youtu.be/oyzutcIVypg)

## Required Pulumi Config

```
originDomain // example: https://localhost:8000
```

## To deploy run

```bash
yarn deploy:development
// or npm run deploy:development
```

or

```bash
yarn deploy:production
// or npm run deploy:production
```

> Those package.json scripts are convenience helpers and configure Pulumi to use Yarn, set NODE_ENV and select the right Pulumi stack.
