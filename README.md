# PWII---Melissa.souza
Aula de programação web II com o professor João Salles

---

Intuito
Repositório para guardar conteúdos e atividades da disciplina **Programação Web III**.

---

Laravel
Framework usado no projeto.  
Aqui você encontra instruções básicas para instalar, rodar e entender a estrutura.

---

 Instalação
- PHP >= 8.1  
- Composer  
- MySQL  
- Node.js / NPM  

```bash
composer create-project laravel/laravel nome-do-projeto
cd nome-do-projeto
php artisan serve
php artisan key:generate
```

---

Estrutura
- Rotas → `routes/web.php`  
- Controllers → `app/Http/Controllers`  
- Models → `app/Models`  
- Views → `resources/views`  

---

Front-end
```bash
npm install
npm run dev
```

---

Comandos
```bash
php artisan make:controller NomeController
php artisan make:seeder NomeSeeder
php artisan db:seed
```

---

Instalação rápida
1. Colocar pasta no `htdocs` (XAMPP)  
2. Copiar `.env.example` → `.env`  
3. `composer install`  
4. `npm install && npm run build`  
5. `php artisan key:generate`  
6. `php artisan migrate`  
7. `composer run dev`  

---

Quer que eu já monte isso em formato de **README.md** pronto para colar no GitHub?
