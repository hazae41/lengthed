# Lengthed

Typed length for TypeScript

```bash
npm i @hazae41/lengthed
```

[**Node Package 📦**](https://www.npmjs.com/package/@hazae41/lengthed)

## Features
- 100% TypeScript and ESM
- Rust-like patterns

## Usage

```tsx
import { Lengthed } from "@hazae41/lengthed"

function f(x: Uint8Array & Lengthed<32>) {
  const length: 32 = x.length
}
```