[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

# Greek Lists

![English](https://raw.githubusercontent.com/tpliakas/greek-lists/main/src/assets/en.png)
An attempt to gather greek static lists in one place.

| **Currently supported lists** |
| :---------------------------- |
| Communities                   |
| Decentralized Administrations |
| Municipalities                |
| Municipal Units               |
| Prefectures                   |
| Regional Units                |
| Regions                       |
| Settlements                   |

&nbsp;
---
&nbsp;
&nbsp;

![Greek](https://raw.githubusercontent.com/tpliakas/greek-lists/main/src/assets/gr.png)
Μια προσπάθεια να μαζέψουμε ελληνικές στατικές λίστες σε ένα σημείο.

| **Λίστες που υποστηρίζονται** |
| :---------------------------- |
| Κοινότητες                    |
| Αποκεντρωμένες Διοικήσεις     |
| Δήμοι                         |
| Δημοτικές Ενότητες            |
| Νομαρχίες                     |
| Περιφερειακές Ενότητες        |
| Περιφέρειες                   |
| Οικισμοί                      |

&nbsp;

## Installation

```bash
npm install greek-lists
```

or

```bash
yarn add greek-lists
```

or

```bash
pnpm add greek-lists
```

## Usage/Examples

React example

```javascript
import {regions} from 'greek-lists'

function App() {
  return regions.map((region, index) => <div key={index}>{region}<div>)
}
```

Output

```
Ανατολικής Μακεδονίας και Θράκης
Αττικής
Βορείου Αιγαίου
Δυτικής Ελλάδας
Δυτικής Μακεδονίας
Ηπείρου
Θεσσαλίας
Ιονίων Νήσων
Κεντρικής Μακεδονίας
Κρήτης
Νοτίου Αιγαίου
Πελοποννήσου
Στερεάς Ελλάδας
```

## API

| List                           | Type       |
| ------------------------------ | ---------- |
| `communities`                  | `string[]` |
| `decentralizedAdministrations` | `string[]` |
| `geographicalAreas`            | `string[]` |
| `municipalities`               | `string[]` |
| `municipalUnits`               | `string[]` |
| `prefectures`                  | `string[]` |
| `regionalUnits`                | `string[]` |
| `regions`                      | `string[]` |
| `settlements`                  | `string[]` |

## Contributing

Contributions are always welcome!

Feel free to add your list and create a pull request.

## Contributors

- [@tpliakas](https://www.github.com/tpliakas)
