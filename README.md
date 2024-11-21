
# Laravel-Vue Essentials  

Welcome to the **Laravel-Vue Essentials** GitHub repository! 🎉  

This repository complements my LinkedIn series [Laravel-Vue Essentials](www.linkedin.com/in/kandarp-trivedi-62a3112a6) (check my LinkedIn profile for conceptual insights). It serves as a hands-on resource for developers looking to master the integration and usage of **Laravel** and **Vue.js** together effectively.  

## 🚀 Series Overview  

The Laravel-Vue Essentials series covers the following topics:  

1. **Integrating Vue.js with Laravel**  
   - How to set up Vue.js within a Laravel application.  
   - Code snippet: [Link to file](Day1-VueLaravel_Integration.md)  

2. **Vue Router in Single Page Application (SPA)**  
   - Implementing Vue Router for seamless SPA navigation.  
   - Code snippet: [Link to file](Day2-VueRouter_SinglePageApplication.md)  

4. **Authentication and Authorization**  
   - Secure authentication with JWT and Laravel Sanctum.  
   - Code snippet: [Link to file](Day3-Laravel_Authentication_Authorization.md)  

5. **Vue Composition API**  
   - Simplifying complex component logic using Vue Composition API.  
   - Conceptual discussion in [LinkedIn](www.linkedin.com/in/kandarp-trivedi-62a3112a6)  

…and more! Check the [LinkedIn series](www.linkedin.com/in/kandarp-trivedi-62a3112a6) for the complete list.  

---
## 💻 Getting Started  

### Prerequisites  
- PHP 8+  
- Node.js 16+  
- Composer  
- Laravel 10+  
- Vue.js 3+  

### Installation  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/laravel-vue-essentials.git  
   cd laravel-vue-essentials  
   ```  

2. Install dependencies:  
   ```bash  
   composer install  
   npm install  
   ```  

3. Run development server:  
   ```bash  
   php artisan serve  
   npm run dev  
   ```  

---

## ✨ Featured Code Snippets  

1. **Setting Up Vue in Laravel**  
   ```javascript  
   import { createApp } from 'vue';  
   import App from './App.vue';  

   const app = createApp(App);  
   app.mount('#app');  
   ```  

2. **Vue Router Example**  
   ```javascript  
   import { createRouter, createWebHistory } from 'vue-router';  

   const routes = [  
       { path: '/', component: Home },  
       { path: '/about', component: About },  
   ];  

   const router = createRouter({  
       history: createWebHistory(),  
       routes,  
   });  

   export default router;  
   ```  

## 📖 Follow the Series  

I am also sharing my learning journey on [LinkedIn](www.linkedin.com/in/kandarp-trivedi-62a3112a6).  

---

## 📝 Contributing  

Contributions are welcome! Feel free to open an issue or submit a pull request.  

---

## 📜 License  

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.  
