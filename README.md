# WorkShop: How to Install Vue.js, Typescript , and Taildwind CSS
This workshop provides a step-by-step guide on installing and setting up Vue.js with TypeScript and Tailwind CSS for efficient and modern web development.

First of all, before you can install Vue.js you need to have **node.js** installed on your computer whit an up-to-date version. :warning:

Here is the link if you don't have [**Node.js**](https://nodejs.org/en ) on your computer. 


### How to install Vue.js
The first step will be to open your terminal and enter this command:

``` npm create vue@latest ```

You should see this on your screen:

<img width="517" alt="vueCommandOne" src="https://github.com/user-attachments/assets/d4cd758c-fcdd-442d-8837-03af75bf1e74">



After pressing enter, you should see this: 

<img width="516" alt="vueNameProject" src="https://github.com/user-attachments/assets/c1da549e-7a9f-4573-91da-e54acb2bd9ab">



Here, you can name your project. We will name it "WorkShop Vue.js".
For Mac user: "WorkShopVue.js" 

There will be multiple prompts. We will say "No" to all of them, including Typescript, which we will set up ourselves. :wink:
It should loot like this: 

<img width="518" alt="vuePrompt" src="https://github.com/user-attachments/assets/a63d308c-d8db-412f-864e-ba38b1811ed4">

Don't forget to be in your directory for your npm install
```cd "WorkShop Vue.js" ```

For Mac user:  ```cd "WorkShopVue.js" ```

Now run ``` npm install ```

<img width="518" alt="vueNpmInstall" src="https://github.com/user-attachments/assets/d66bbabe-3c84-40a3-bb5a-4422eeda62d7">



When it's done, you can run ``` npm run dev ```

<img width="518" alt="vueNpmRunDev" src="https://github.com/user-attachments/assets/c20cd66f-6d89-4779-a95c-50541e0cd5e0">



Now, you should see your **localhost** adress, which you can now copy and paste into your browser's address bar.

Congratulation, you did it ! :crown: (You should see this)

<img width="959" alt="vueHomePage" src="https://github.com/user-attachments/assets/aaec2544-8db4-4472-995e-ca48181387b8">

We can go now to the next step. :point_down:

### How to implement Typescript


You can use two lines of code to install TypeScript. **(We will use the first one)**

The first one is to run in your project directory: 

``` npm install typescript --save-dev ```


<img width="519" alt="typescriptInstall" src="https://github.com/user-attachments/assets/593d0709-2065-4d31-9a56-35ab66c6166a">


The second one installs TypeScript globaly:  

``` npm install -g typescript ``` 

See, that was easy! :grin:

We can now move to the next step. :point_down:

### How to implement Taildwind


First, install Tailwind CSS, PostCSS, and Autoprefixer by running:


``` npm install -D tailwindcss@latest postcss@latest autoprefixer@latest ``` 


<img width="556" alt="vueInstalTailwind" src="https://github.com/user-attachments/assets/4e1efb36-1082-4482-85e7-e0b8de41878e">


Next, generate the `tailwind.config.js` and `postcss.config.js` files by running:


``` npx tailwindcss init -p ``` 


<img width="553" alt="vueTailConfig" src="https://github.com/user-attachments/assets/3959f2c1-9e02-436d-9036-41eb5fde6638">



And that's it, it's time to launch your IDE and open the project. 

## Bonus how to implement headless WordPress with Vue.js

[Let's go!](bonus.md)
