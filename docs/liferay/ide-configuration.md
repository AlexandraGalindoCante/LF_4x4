---
sidebar_position: 1
---

# Configuración IDE 



**Liferay Developer Studio** files to `src/pages` to create a **standalone page**:

### ¿Qué es IDE?

El IDE de Liferay es el conjunto oficial de complementos de Eclipse, creados por Liferay Inc. que admiten el desarrollo  de aplicaciones para la plataforma Liferay Portal.

- **[Documentación ](https://liferay.dev/)**
- **[Repositorio GitHub ](https://github.com/liferay/liferay-ide/)**
- **[Instrucciones instalación ](https://liferay.dev/-/ide-installation-instructions/)**


- `src/pages/index.js` → `localhost:3000/`
- `src/pages/foo.md` → `localhost:3000/foo`
- `src/pages/foo/bar.js` → `localhost:3000/foo/bar`


## Configuración variables de entorno

Crear el archivo `D:\user\gradle-set-enmv.properties.`:
***Ejecutar el archivo**

```jsx title="D:\user\gradle.properties"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```

```jsx title="D:\user\gradle.properties"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```


## Configuración gradle

Create a file at `D:\user\gradle.properties.`:

```jsx title="D:\user\gradle.properties"
import React from 'react';
import Layout from '@theme/Layout';

export default function MyReactPage() {
  return (
    <Layout>
      <h1>My React page</h1>
      <p>This is a React page</p>
    </Layout>
  );
}
```

A new page is now available at [http://localhost:3000/my-react-page](http://localhost:3000/my-react-page).

## Create your first Markdown Page

Create a file at `src/pages/my-markdown-page.md`:

```mdx title="src/pages/my-markdown-page.md"
# My Markdown page

This is a Markdown page
```

A new page is now available at [http://localhost:3000/my-markdown-page](http://localhost:3000/my-markdown-page).
