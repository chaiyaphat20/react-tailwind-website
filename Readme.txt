1.tailwind

2.another lib
npm i react-icons react-burger-menu react-responsive react-responsive-carousel react-scroll

3.ตัวจัดการ styled-components คือ twin.macro
npm i twin.macro styled-components

4.เพิ่ม code ที่package.json
  "babelMacros":{
    "twin":{
      "config":"./tailwind.config.js",
      "preset":"styled-components"
    }
  },

	5.เพิ่ม code ที่ craco.confog.js
		babel:{
		plugins:["babel-plugin-macros"]
	},