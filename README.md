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

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

### Import and export

|   Trigger | Content                                                                                       |
| --------: | --------------------------------------------------------------------------------------------- |
|    `exc→` | Export cons `export const name = 'name';`                                                     |
|    `exd→` | Export default `export default $name;`                                                        |
|  `excls→` | Export default class in ES6 syntax `export default class className {};`                       |
| `exclse→` | Export default class which extends `export default class className extends baseclassName {};` |
|  `exnfn→` | Export named function in ES6 syntax `export const functionName = (params) => {};`             |
|   `exnv→` | Export named variable in ES6 syntax `export const exportVariable = localVariable;`            |
|    `edl→` | Module exports from Common JS, node syntax at ES6 `module.exports = {};`                      |
|   `mdex→` | Module exports from Common JS, node syntax at ES6 `module.exports = {};`                      |
|    `edl→` | Eslint Disable Line                                                                           |
|   `ednl→` | Eslint Disable Next Line                                                                      |
|     `cm→` | Comment Block                                                                                 |
|    `cmb→` | Comment Big Block                                                                             |
|   `cmbl→` | Comment Big Line                                                                              |
|    `clg→` | Print Console.log                                                                             |
|   `clgo→` | Displays an object in the console with its name                                               |
|    `clt→` | Displays tabular data as a table                                                              |
|    `clc→` | Clears the console                                                                            |

### Class helpers

| Trigger | Content                                                  |
| ------: | -------------------------------------------------------- |
|  `con→` | adds default constructor in the class `constructor() {}` |

### Various methods

| Trigger | Content                                                       |
| ------: | ------------------------------------------------------------- |
|  `fre→` | forEach loop in ES6 syntax `array.forEach(currentItem => {})` |
|  `thc→` | Add the .then and .catch methods to handle promises           |
|  `sti→` | Set timeout helper method `setTimeout(() => {});`             |
|  `sto→` | Set interval helper method `setInterval(() => {});`           |
| `deso→` | destructing object syntax `const {rename} = fs`               |
| `desr→` | destructing array syntax `const [first, second] = [1,2]`      |
|  `afn→` | creates an anonymous function `(params) => {}`                |
|  `nfn→` | creates a named function `const add = (params) => {}`         |

### Console methods

| Trigger | Content                                                   |
| ------: | --------------------------------------------------------- |
|  `cas→` | console alert method `console.assert(expression, object)` |

[code]: https://code.visualstudio.com/
