# TypeScript

[doc](https://www.typescriptlang.org/)

TypeScript is JavaScript with added syntax for types.
TypeScript is a syntactic superset of JavaScript which adds static typing.

JavaScript 属于动态编程语言，在执行期做类型检查，其代码大部分错误都是类型错误（Uncaught TypeError），增加了找 bug、改 bug 的时间，影响开发效率。
TypeScript 属于静态编程语言，在编译期做类型检查，能提前在编写代码时找到问题，减少了找 bug、改 bug 的时间。

## Installation

```bash
npm i -g typescript
```

Check the version of typescript to confirm if it has been installed successfully

```bash
tsc -v
```

## Usage

a.Create a ts file. E.g. hello.ts

b.Convert ts file to js file

```bash
tsc hello.ts
```

c.Run js file

```bash
node hello.js
```

## Simplify the process of running ts file

```bash
npm i -g ts-node
ts-node hello.ts
```

## Common Types
