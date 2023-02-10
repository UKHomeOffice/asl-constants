# asl-constants

Provides a home for any commonly used values shared across the ASL project.

## Usage

[Authenticate with GitHub packages](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-npm-registry#authenticating-with-a-personal-access-token)


Install the package:

```bash
npm install @ukhomeoffice/asl-constants --save-prod
```

Import as necessary:

```js
const { establishmentCountries, establishmentStatuses } = require('@ukhomeoffice/asl-constants');
console.log(establishmentCountries);
```

result:
```bash
[
  'england',
  'scotland',
  'wales',
  'ni'
]
```
