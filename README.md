# Bastion styles for Bootstrap

Changing Bootstrap theme to Bastion Company Styles.

## 1. Install packages

`npm install @bs-solutions/bootstrap-styles`

## 2. Add styles

Add Bastion company style imports `@bs-solutions/bootstrap-styles/styles` to your project.

### 2.1 Into your common (root) *.scss file

Example:

```scss
@import '@bs-solutions/bootstrap-styles/styles';

// your awesome styles
```

### 2.2 Into your common (root) *.js, *.jsx, *.ts, *.tsx file

Example:

```tsx
import { StrictMode } from "react";
import { createRoot } from "react-dom/client";

import "@bs-solutions/bootstrap-styles/styles.scss";

// your awesome code
```
