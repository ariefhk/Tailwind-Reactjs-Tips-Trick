# Setup Projekan Tailwindcss + React Js🚀

### 1. Create App di terminal
```Node js
npx create-react-app my-project
cd my-project
```

### 2. Install Tailwindcss
```Node js
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### 2. Tambahkan settingan di tailwind.config.js
```
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
### 3. Tambahkan settingan di ./src/index.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 4. Build projekannya
```
npm run start
```

### 5. Testing dan Jadi Deh!
```React Js
export default function App() {
  return (
    <h1 className="text-3xl font-bold underline">
      Hello world!
    </h1>
  )
}
```
