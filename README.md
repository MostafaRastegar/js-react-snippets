# JavaScript and React snippets

## VS Code JavaScript (ES6) snippets

---

This extension contains code snippets for Reactjs and JavaScript in ES6 syntax for [Vs Code][code] editor (supports both JavaScript and TypeScript).

## Installation

Install from this [link](https://google.com)

## Supported languages (file extensions)

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)
- Vue (.vue)

## Snippets

Below is a list of all available snippets and the triggers of each one.

### Import and export

|  Trigger | Content                                                                                                               |
| -------: | --------------------------------------------------------------------------------------------------------------------- |
|    `exc` | Export cons `export const name = 'name';`                                                                             |
|    `exd` | Export default `export default $name;`                                                                                |
|  `excls` | Export default class in ES6 syntax `export default class className {};`                                               |
| `exclse` | Export default class which extends `export default class className extends baseclassName {};`                         |
|  `exnfn` | Export named function in ES6 syntax `export const functionName = (params) => {};`                                     |
|   `exnv` | Export named variable in ES6 syntax `export const exportVariable = localVariable;`                                    |
|    `edl` | Module exports from Common JS, node syntax at ES6 `module.exports = {};`                                              |
|   `mdex` | Module exports from Common JS, node syntax at ES6 `module.exports = {};`                                              |
|    `ima` | Imports a specific portion of the module by assigning a local alias `import { originalName as alias } from 'module';` |
|    `ime` | Imports everything as alias from the module `import * as alias from 'module';`                                        |
|    `imp` | Imports entire module statement `import moduleName from 'module';`                                                    |
|  `imdes` | Imports only a portion of the module `import { } from 'module';`                                                      |
|    `imn` | Import No Module Name `import 'module';`                                                                              |

### Class helpers

| Trigger | Content                                                  |
| ------: | -------------------------------------------------------- |
|   `con` | adds default constructor in the class `constructor() {}` |
|  `pget` | Creates a getter property inside a class                 |
|  `pset` | Creates a setter property inside a class                 |
|   `met` | Creates a method inside a class                          |

### Various methods

| Trigger | Content                                                       |
| ------: | ------------------------------------------------------------- |
|   `fre` | forEach loop in ES6 syntax `array.forEach(currentItem => {})` |
|  `jmap` | Javascript map `arr.map( item => item.id)`                    |
|   `thc` | Add the .then and .catch methods to handle promises           |
|   `sti` | Set timeout helper method `setTimeout(() => {});`             |
|   `sto` | Set interval helper method `setInterval(() => {});`           |
|  `deso` | destructing object syntax `const {rename} = fs`               |
|  `desr` | destructing array syntax `const [first, second] = [1,2]`      |
|   `afn` | creates an anonymous function `(params) => {}`                |
|   `nfn` | creates a named function `const add = (params) => {}`         |

### Console methods

| Trigger | Content                                                   |
| ------: | --------------------------------------------------------- |
|   `cas` | console alert method `console.assert(expression, object)` |
|    `cm` | Comment Block                                             |
|   `cmb` | Comment Big Block                                         |
|  `cmbl` | Comment Big Line                                          |
|   `clg` | Print Console.log                                         |
|  `clgo` | Displays an object in the console with its name           |
|   `clt` | Displays tabular data as a table                          |
|   `clc` | Clears the console                                        |

### Reactjs

| Trigger | Content                                                                                                 |
| ------: | ------------------------------------------------------------------------------------------------------- |
|   `imr` | Import react package `import React from 'react'`                                                        |
|   `ims` | Import Styled-Components `import styled from 'styled-components'`                                       |
|  `imcn` | Import classNames `import classNames from 'classnames'`                                                 |
|  `impt` | Import PropTypes `import PropTypes from 'prop-types'`                                                   |
|   `rpt` | Add propTypes" `ComponentName.propTypes = {propsName: Propstypes.string}`                               |
|   `slc` | Stateless Component `const componentName = () => () export default componentName;`                      |
|  `slcr` | Stateless Component with return `const componentName = () => {return ()} export default componentName;` |
|  `styc` | Styled Component `const StyledName = styled.TagName'margin:0' `                                         |

[code]: https://code.visualstudio.com/
