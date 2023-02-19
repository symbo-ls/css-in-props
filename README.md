# css-in-props

This repository is merged into https://github.com/symbo-ls/smbls

[![npm version](https://badge.fury.io/js/css-in-props.svg)](https://badge.fury.io/js/css-in-props)

### Setup

1. Installation
```
yarn add css-in-props
```

2. Import the component from Symbols
```
import { setClassname } from 'css-in-props'
```

3. Use it inside your DOMQL code
```
const Box = ({ children, ...props }) => <div className={setClassname(props)}>{children}</div>
```
