# 📘 KërJàng

**KërJàng** est une plateforme web sénégalaise qui connecte des enseignants qualifiés à des élèves et parents à la recherche de cours particuliers, à domicile ou en ligne.

## 🚀 Objectif

Faciliter l’accès à un enseignement personnalisé tout en offrant une opportunité de revenu aux jeunes enseignants qualifiés.

## 🛠️ Tech Stack

- PHP 8+ / Laravel
- MySQL / PostgreSQL
- Bootstrap (frontend web)
- API de paiement : Orange Money, Wave, Free Money

## ⚙️ Installation

```bash
git clone https://github.com/votre-utilisateur/kerjang.git
cd kerjang
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
