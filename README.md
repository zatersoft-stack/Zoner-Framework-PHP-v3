# Zoner-Framework-PHP-v3
Framework PHP minimalista, rápido e extensível, com sistema de rotas próprio, MVC organizado, suporte a plugins, layout padrão moderno e pronto para apps profissionais. Criado pela ZaterSoft.

[![PHP Version](https://img.shields.io/badge/PHP-%3E=8.1-777BB4.svg?logo=php)](https://www.php.net/)
[![Status](https://img.shields.io/badge/status-active-success.svg)](#)
[![Made by ZaterSoft](https://img.shields.io/badge/made%20by-ZaterSoft-0b7285.svg)](#)

Micro framework PHP moderno em arquitetura MVC, com roteamento próprio (sem necessidade de `.htaccess`), template padrão inspirado no Laminas, suporte a plugins e estrutura pensada para aplicações SaaS.

Desenvolvido por **ZaterSoft**  
Engenheiro responsável: **Melquisedeque C. Campos**

---

## ✨ Principais recursos

- ✅ Arquitetura **MVC** simples e organizada  
- ✅ **Router próprio** (sem dependência de `.htaccess`)  
- ✅ **Template padrão** pronto (Bootstrap 5), estilo Moderno  
- ✅ **Views em `.phtml`** com partes fatiadas (`shared/`)  
- ✅ Estrutura preparada para **plugins/módulos** (`plugins/`)  
- ✅ Organização pensada para **SaaS**, dashboards e painéis administrativos  
- ✅ Compatível com **PHP 8.1+**  
- ✅ Autoload PSR-4 via `Composer` (opcional)

---

## 📁 Estrutura do projeto

```text
Zoner-Framework-PHP-v3/
├── app/
│   ├── Controllers/
│   ├── Models/
│   ├── Middlewares/
│   ├── Services/
│   └── Helpers/
│
├── config/
│   ├── app.php
│   ├── database.php
│   └── routes.php
│
├── public/
│   ├── index.php
│   ├── assets/
│   │   ├── css/
│   │   ├── js/
│   │   └── img/
│   └── uploads/
│
├── shared/
│   ├── header.phtml
│   ├── footer.phtml
│   ├── menu.phtml
│   └── components/
│       └── alerts.phtml
│
├── template/
│   ├── layout.phtml
│   └── home/
│       ├── index.phtml
│       └── sobre.phtml
│
├── plugins/
│   └── forms/
│       └── config.php
│
├── zoner/
│   ├── Autoload.php
│   ├── Router.php
│   ├── Zoner.php
│   ├── Request.php
│   └── Response.php
│
├── storage/
│   ├── logs/
│   ├── cache/
│   └── sessions/
│
├── .env.example
├── composer.json
├── router.php
├── index.php
└── README.md
