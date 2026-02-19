# Node Simple Polyfills

Simple node polyfills that exports `undefined` for the browser environment

# Usage

```ts
import path from 'node-simple-polyfills/path';

if (path === undefined) {
  // browser environment
} else {
  // node environment
}
```

# Third-Party Licenses

[Read Here](/third_party_licenses.md)

# Contributors

[Read Here](/CONTRIBUTORS.md)

# Copyrights

- Copyright (c) 2026 Grigorii Lutkov \<friend.lga@gmail.com\>
- Copyright (c) [Node Simple Polyfills Contributors](/CONTRIBUTORS.md)

# License

Licensed under the [MIT License](/LICENSE.md)

<!----------------------------------------------------------------------------->

<!-- <style>
p:has(+ ul),
p:has(+ ol) {
  margin-bottom: 0;
}
p + ul,
p + ol {
  margin-top: 0;
}
ul,
ol {
  list-style-position: inside;
}
ul:not(ul ul):not(ol ul),
ol:not(ol ol):not(ul ol) {
  padding-left: 0;
}
ul ul,
ul ol,
ol ol,
ol ul {
  margin: 0;
  padding-left: 1.5rem;
}
</style> -->
