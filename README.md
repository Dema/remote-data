# remote-data

> This is an abstraction over remote data that needs to be fetched from backend. It based on
> "Slaying UI Antipattern In X" article

[![NPM](https://img.shields.io/npm/v/@dmitry.olyenyov/remote-datas.svg)](https://www.npmjs.com/package/@dmitry.olyenyov/remote-datas) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
yarn add @dmitry.olyenyov/remote-data
```

## Usage

```tsx
let data = initialized();

data = success("server response");

data = failure(someError);
```

## License

MIT © [Dema](https://github.com/Dema/)
