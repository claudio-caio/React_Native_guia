# 📚 Guía de Estudio Completa: React Native con Expo

---

## 🎯 Objetivo

- Aprender a configurar un entorno con Expo
- Ejecutar una app en celular o emulador
- Entender el flujo de desarrollo
- Practicar cambios en tiempo real

---

## 📋 Requisitos

- Node.js instalado
- Editor de código (VS Code recomendado)

Opcional:
- Expo Go (celular)
- Android Studio (emulador)
- Xcode (solo Mac)

---

## ⚙️ Crear proyecto

```bash
npx create-expo-app miApp
```

---

## 📂 Entrar al proyecto

```bash
cd miApp
```

---

## ▶️ Ejecutar proyecto

```bash
npm start
```

Esto abre Expo y muestra un código QR.

---

## 📱 Formas de ejecutar la app

### Celular (más fácil)
- Instalar Expo Go
- Escanear QR

### Android
- Tener emulador
- Presionar `a`

### iOS (solo Mac)
- Tener Xcode
- Presionar `i`

---

## 🧠 Concepto clave: Expo

Expo simplifica React Native:

- No necesitás configurar todo manualmente
- Recarga automática
- Desarrollo rápido

---

## ⚙️ ¿Qué es Metro Bundler?

- Procesa tu código JavaScript
- Lo convierte en app
- Actualiza en tiempo real

---

## 📄 Archivo principal

```bash
App.js
```

---

## ✏️ Ejemplo básico

```jsx
import { Text, View } from 'react-native';

export default function App() {
  return (
    <View>
      <Text>Hola mundo</Text>
    </View>
  );
}
```

---

## 🎨 Estilos

```jsx
<Text style={{ fontSize: 20 }}>
  Hola mundo
</Text>
```

---

## 🔁 Ventaja clave

Cada vez que guardás:

- La app se actualiza automáticamente
- No hay compilación manual

---

## 🧩 Comandos importantes

```bash
npm start
npm run android
npm run ios
npm run web
```

---

## 📦 Componentes básicos

### View
Contenedor (como div)

### Text
Texto

### ScrollView
Scroll

---

## 🚀 Flujo de trabajo

1. Crear proyecto  
2. Ejecutar  
3. Abrir app  
4. Editar código  
5. Ver cambios  

---

## 📌 Qué aprender después

- Componentes
- Estilos
- Navegación
- APIs (Django, Node)

---

## 🧠 Resumen rápido

```bash
npx create-expo-app miApp
cd miApp
npm start
```

👉 Editás  
👉 Guardás  
👉 Ves cambios  

---

## 🏁 Conclusión

Expo permite:

- Aprender fácil
- Desarrollar rápido
- Probar sin complicaciones

🚀 Ideal para empezar en React Native
