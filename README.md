# LMS Frontend

### Setup instruction 

 
```

1 . clone the project
```
git clone https://github.com/prajapati21/lms-Project
```

2. move into the directory
```
cd lms-frontend 

```
3. install dependencies

```
npm i
```
4. run the Server

```
npm run dev
```



### set up instruction for tailwind

[https://tailwindcss.com/docs/guides/vite]

1.Install tailwindcss

```
npm install -D tailwindcss
```

2.Create tailwind config file 
```
npx tailwindcss init 
```

3. Add file extension to tailwind config file in content property 

```
   "./src/**/*.{html,js,ts,jsx,tsx}"
```

4. Add the tailwind directive at the top 'index.css'


```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
5. Add the following details in the plugin property of tainwind config

```
    [require("daisyui"), require("@tailwindcss/line-clamp")]
```

### Adding plugins and dependencies 

```
npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axi
os react-hot-toast @tailwindcss/line-clamp
```