# List-of-languages-with-ISO-Alpha-2-codes
This repository contains a list of languages including Alpha-2 codes, The data is based on the ISO database, and the codes are updated accordingly.

## Data Structure
The data is structured in TypeScript interface, as follows:
```
interface Language {
  code: string;
  name: string;
  native: string;
  rtl?: number;
}
```
## Contributing
If you find any errors or have suggestions for improvements, please open an issue or submit a pull request. We welcome any feedback that can help make this data more accurate and useful.
