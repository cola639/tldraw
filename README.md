# How to start

Prepare:

```
tldraw v2.1.4
node: 22.0.0 npm: 10.5.1
vite: 5.2.11
chokidar-cli: 3.0.0
chokidar: 3.6.0
concurrently: 8.2.2
tsx: 4.11.0

npm install -g vite
npm install -g chokidar
npm install -g chokidar-cli
npm install -g concurrently
npm install -g tsx
```

Confirm yarn version:

```bash
## 运行 corepack enable 命令会激活 corepack，使其能够用package.json packageManager管理器版本。
corepack enable
```

Install dependencies:

```bash
yarn
```

Start the local development server:

```bash
yarn dev
```

# tldraw

Welcome to the public monorepo for [tldraw](https://github.com/tldraw/tldraw). tldraw is a library for creating infinite canvas experiences in React. It's the software behind the digital whiteboard [tldraw.com](https://tldraw.com).

- Read the docs and learn more at [tldraw.dev](https://tldraw.dev).
- Learn about [our license](https://github.com/tldraw/tldraw#License).

> 🤵 Interested in purchasing a commercial license for the tldraw SDK?
> Fill out [this form](https://forms.gle/PmS4wNzngnbD3fb89).

## Installation

```bash
npm i tldraw
```

## Usage

```tsx
import { Tldraw } from 'tldraw'
import 'tldraw/tldraw.css'

export default function App() {
	return (
		<div style={{ position: 'fixed', inset: 0 }}>
			<Tldraw />
		</div>
	)
}
```

Learn more at [tldraw.dev](https://tldraw.dev).

## Local development

The local development server will run our examples app. The basic example will show any changes you've made to the codebase.

To run the local development server, first clone this repo.

Enable [corepack](https://nodejs.org/api/corepack.html) to make sure you have the right version of `yarn`:

```bash
corepack enable
```

Install dependencies:

```bash
yarn
```

Start the local development server:

```bash
yarn dev
```

Open the example project at `localhost:5420`.

## License

The tldraw source code and its distributions are provided under the [tldraw license](https://github.com/tldraw/tldraw/blob/master/LICENSE.md). This license does not permit commercial use. To purchase a commercial license or learn more, please fill out [this form](https://forms.gle/PmS4wNzngnbD3fb89).

## Trademarks

Copyright (c) 2023-present tldraw Inc. The tldraw name and logo are trademarks of tldraw. Please see our [trademark guidelines](https://github.com/tldraw/tldraw/blob/main/TRADEMARKS.md) for info on acceptable usage.

## Contact

Find us on Twitter/X at [@tldraw](https://twitter.com/tldraw).

## Community

Have questions, comments or feedback? [Join our discord](https://discord.gg/rhsyWMUJxd) or [start a discussion](https://github.com/tldraw/tldraw/discussions/new). For the latest news and release notes, check out our [Substack](https://tldraw.substack.com/).

## Contribution

Please see our [contributing guide](https://github.com/tldraw/tldraw/blob/main/CONTRIBUTING.md). Found a bug? Please [submit an issue](https://github.com/tldraw/tldraw/issues/new).

## Contributors

<a href="https://github.com/tldraw/tldraw/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=tldraw/tldraw&max=400&columns=20" width="100%"/>
</a>

## Star History

<a href="https://star-history.com/#tldraw/tldraw">
	<picture>
	  <source
	    media="(prefers-color-scheme: dark)"
	    srcset="https://api.star-history.com/svg?repos=tldraw/tldraw&type=Date&theme=dark"
	  />
	  <source
	    media="(prefers-color-scheme: light)"
	    srcset="https://api.star-history.com/svg?repos=tldraw/tldraw&type=Date"
	  />
	  <img src="https://api.star-history.com/svg?repos=tldraw/tldraw&type=Date" alt="Star History Chart" width="100%" />
	</picture>
</a>
