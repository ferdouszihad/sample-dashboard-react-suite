# React Suite Quick Start Guideline

### Basic installation

1. Import react-suite

```bash
npm install rsuite --save
```

2. Import CSS on main jsx

```bash
import 'rsuite/dist/rsuite.min.css';
```

### demo code with provider

```jsx
import React from 'react';
import ReactDOM from 'react-dom/client';
 import { CustomProvider } from 'rsuite';
import App from './App.tsx';
import 'rsuite/styles/index.less';

ReactDOM.createRoot(document.getElementById('root')!).render(
  <React.StrictMode>  <CustomProvider theme="dark">
      <App />
   </CustomProvider>
  </React.StrictMode>
);
);
```
