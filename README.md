# JavaScript and React snippets

## VS Code JavaScript (ES6) snippets

---

This extension contains code snippets for Reactjs and JavaScript in ES6 syntax for [Vs Code][code] editor (supports both JavaScript and TypeScript).

## Installation

Install from this [link](https://marketplace.visualstudio.com/items?itemName=MostafaRastegar.js-react-snippets)

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
|    `exc` | Export cons `export const name = 'name'`                                                                              |
|    `exd` | Export default `export default $name`                                                                                 |
|  `excls` | Export default class in ES6 syntax `export default class className {}`                                                |
| `exclse` | Export default class which extends `export default class className extends baseclassName {}`                          |
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

| Trigger | Content                                                                             |
| ------: | ----------------------------------------------------------------------------------- |
|   `con` | adds default constructor in the class `constructor(params) {}`                      |
|  `pget` | Creates a getter property inside a class `get propertyName() { return this.value }` |
|  `pset` | Creates a setter property inside a class `set propertyName(value) { }`              |
|   `met` | Creates a method inside a class `methodName(params) { }`                            |

### Various methods

| Trigger | Content                                                                                        |
| ------: | ---------------------------------------------------------------------------------------------- |
|   `fre` | forEach loop in ES6 syntax `array.forEach(currentItem => {})`                                  |
|  `jmap` | Javascript map `array.map( item => customCode)`                                                |
|   `thc` | Add the .then and .catch methods to handle promises `.then((result) => {}).catch((err) => {})` |
|   `sto` | Set timeout helper method `setTimeout(() => {}, delayInms)`                                    |
|   `sti` | Set interval helper method `setInterval(() => {}, intervalInms)`                               |
|  `deso` | destructing object syntax `const {propertyName} = objectToDestruct`                            |
|  `desr` | destructing array syntax `const [propertyName] = arrayToDestruct`                              |
|   `afn` | creates an anonymous function `(params) => {}`                                                 |
|   `nfn` | creates a named function `const name = (params) => {}`                                         |

### Console methods

| Trigger | Content                                                                               |
| ------: | ------------------------------------------------------------------------------------- |
|    `cm` | Comment Block                                                                         |
|   `cmb` | Comment Big Block                                                                     |
|  `cmbl` | Comment Big Line                                                                      |
|   `clg` | Print Console.log `console.log('object :>> ', object);`                               |
|  `clgo` | Displays an object in the console with its name `console.log('object :>> ', object);` |
|   `clt` | Displays tabular data as a table `console.table(array);`                              |
|   `clc` | Clears the console `console.clear();`                                                 |

### Reactjs

|   Trigger | Content                                                                                         |
| --------: | ----------------------------------------------------------------------------------------------- |
|     `imr` | Import react package `import React from 'react'`                                                |
|    `imre` | Import react Effect `import React, { effectName } from 'react'`                                 |
|     `ims` | Import Styled-Components `import styled from 'styled-components'`                               |
|    `imcn` | Import classNames `import classNames from 'classnames'`                                         |
|    `impt` | Import PropTypes `import PropTypes from 'prop-types'`                                           |
|  `imrdcn` | React useState Hooks `import { connect } from 'react-redux'`                                    |
|     `rpt` | Add propTypes" `componentName.propTypes = {property: Propstypes.value }`                        |
|     `slc` | Stateless Component `const componentName = () => (other styles) export default componentName`   |
|    `slcr` | Stateless Component with return `const componentName = () => () export default componentName`   |
|    `styc` | Styled Component `const componentName = styled.name''`                                          |
| `exdstyc` | Styled Component `export default styled.elementName''`                                          |
|     `rue` | React useEffect Hooks `useEffect(() => {},[dependency])`                                        |
|     `rus` | React useState Hooks `const [value, setValue] = useState(value)`                                |
|     `rrd` | Redux Reducer                                                                                   |
|    `rpfn` | Redux Pure Function                                                                             |
|  `exrdcn` | Export Redux Connect ` export default connect( mapStateToProps mapDispatchToProps )(Component)` |

### Test methods

| Trigger | Content                                              |
| ------: | ---------------------------------------------------- |
|    `tt` | Test method `test('description', () => {})`          |
|  `rdes` | Test describe method `test('describe', () => {})`    |
|  `rdes` | Test describe method `it('should sample', () => {})` |
|   `tit` | Test it method `it('should sample', () => {})`       |

[code]: https://code.visualstudio.com/
