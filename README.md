# 🏥 Clinic Management System

A comprehensive clinic management solution built with PHP Laravel framework, designed to streamline medical operations and patient care.

## ✨ Key Features

### 🎛️ Admin Dashboard
![Admin Panel](1.png)
- Complete system control
- User role management
- Automated backups

### 👨‍⚕️ Doctor & Patient Management
![Doctors Interface](2.png)
![Patients Interface](3.png)
- Electronic health records
- Staff scheduling
- Treatment history tracking

### 📅 Appointment System
![Scheduling](2.png)
- Interactive calendar
- Automated reminders
- Resource allocation

## 🛠️ Technology Stack

| Backend | Frontend | Database |
|---------|----------|----------|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="40" title="PHP"> PHP 8 | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="40" title="Bootstrap"> Bootstrap | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="40" title="MySQL"> MySQL |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" width="40" title="Laravel"> Laravel 10 | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" title="JS"> JavaScript | |

## ✏️ Author <a name="author"></a>

[![GitHub](https://img.shields.io/badge/-Ingrid_Vasconcelos-181717?logo=github&logoColor=white)](https://github.com/Ingridvasc)
[![LinkedIn](https://img.shields.io/badge/-Linkedin-0A66C2?logo=linkedin)](https://www.linkedin.com/in/ingrid-karoline-vasconcelos-da-silva-18635a230/)


## 🚀 Installation

```bash
# Clone repository
git clone https://github.com/ingridvasc/clinic-management-system.git
cd clinic-management-system

# Install dependencies
composer install
npm install

# Setup environment
cp .env.example .env
php artisan key:generate

# Run migrations
php artisan migrate --seed

# Start server
php artisan serve
