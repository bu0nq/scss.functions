# SCSS.Functions

Package for integrating `SCSS.Functions` in a web environment.

![npm](https://img.shields.io/npm/v/@bu0nq/scss.functions?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@bu0nq/scss.functions?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @bu0nq/scss.functions
```

## Usage

```scss
@use "@bu0nq/scss.functions/functions";
```

### Em

```scss
@use "@bu0nq/scss.functions/functions";

.example {
    font-size: functions.em(16px);
}

// Result
.example {
    font-size: 1em;
}
```

### Rem

```scss
@use "@bu0nq/scss.functions/functions";

.example {
    font-size: functions.rem(16px);
}

// Result
.example {
    font-size: 1rem;
}
```
