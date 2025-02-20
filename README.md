# Vue 3 + Vite + Tailwindcss
**Crear proyecto vue + vite**
```
npm create vite@latest
```

### https://tailwindcss.com/docs/installation/using-vite

**instalador dentro del proyecto sirve vue, react, probar si sirve para otro framework**
```
npm install tailwindcss @tailwindcss/vite
```

**en config.vite **
```
import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'// incorporar esta importacion 
export default defineConfig({
  plugins: [
    tailwindcss(), // agregar esta linea
  ],
})
```

**en en archivo css y listo probar si funciona**
```
@import "tailwindcss";
```

**para hacer deploy una vez terminado el proyecto el siguiente comando**
```
npm run build
```