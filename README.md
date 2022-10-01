# Setup

### 1. Create App
```Node js
npx create-react-app my-project
cd my-project
```

### 2. Install Tailwind
```Node js
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

### 2. Setting Tailwind Config
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
### 3. Add in index.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 4. Run Project
```
npm run start
```
