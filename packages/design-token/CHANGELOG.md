# @karrotmarket/design-token

## 1.0.2

### Patch Changes

- 26bdbf9: Update nanobundle

## 1.0.1

### Patch Changes

- 15d4e96: fix manifest to respect yarn's publishConfig field coverage

## 1.0.0

### Major Changes

- b1152bd: Prepare first major release

  - Switch to esbuild based bundle, reduce boilerplate
  - Make ESM first, support CommonJS conditionally
  - Drop AMD, use ES Module instead
  - Drop legacy bundler support (Parcel 1, Webpack 4, CRA 4)
    - Resolver should supports Node.js conditional export resolution

## 0.2.0

### Minor Changes

- minor bump
