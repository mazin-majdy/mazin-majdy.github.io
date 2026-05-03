<div align="center">

```
███╗   ███╗ █████╗ ███████╗██╗███╗   ██╗
████╗ ████║██╔══██╗╚══███╔╝██║████╗  ██║
██╔████╔██║███████║  ███╔╝ ██║██╔██╗ ██║
██║╚██╔╝██║██╔══██║ ███╔╝  ██║██║╚██╗██║
██║ ╚═╝ ██║██║  ██║███████╗██║██║ ╚████║
╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝╚═╝╚═╝  ╚═══╝
```

# Mazin Almaswaby
### Backend Developer · PHP & Laravel Specialist

[![Email](https://img.shields.io/badge/Email-mazinmajdy2001%40gmail.com-c8f04e?style=flat-square&labelColor=0a0a0f&color=c8f04e)](mailto:mazinmajdy2001@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-mazin--majdy-c8f04e?style=flat-square&labelColor=0a0a0f&logo=github&logoColor=white)](https://github.com/mazin-majdy)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B972592691590-c8f04e?style=flat-square&labelColor=0a0a0f&logo=whatsapp&logoColor=white)](https://wa.me/972592691590)
[![Portfolio](https://img.shields.io/badge/Portfolio-mazin--majdy.github.io-c8f04e?style=flat-square&labelColor=0a0a0f)](https://mazin-majdy.github.io)

> *Building scalable APIs, SaaS platforms & real-time systems — from Palestine 🇵🇸, fully remote.*

</div>

---

## About Me

I'm a Backend Developer with **3+ years** of professional experience designing and building production-grade web applications. I specialize in **PHP & Laravel**, with a focus on clean architecture, database optimization, and systems that scale.

I don't just build CRUD apps. I think about data integrity, failure modes, concurrency, and performance from the first line of code.

```php
$mazin = [
    'role'       => 'Backend Developer',
    'stack'      => ['PHP', 'Laravel', 'MySQL', 'Redis', 'REST API', 'WebSocket'],
    'focus'      => ['SaaS Architecture', 'API Design', 'Real-time Systems'],
    'location'   => 'Palestine 🇵🇸',
    'available'  => true,
    'remote'     => true,
];
```

---

## Tech Stack

**Backend**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Auth & APIs**

![Sanctum](https://img.shields.io/badge/Sanctum-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-0a0a0f?style=flat-square&logo=postman&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socket.io&logoColor=white)

**Frontend**

![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

---

## Featured Projects

### 🏗️ Multi-Tenant Restaurant SaaS Platform
> *The most complex system I've built — production-grade, architected from scratch*

A headless, multi-tenant SaaS platform where each restaurant gets a fully isolated database, a branded API, and a real-time kitchen display — all served from a single Laravel codebase.

**Key technical decisions:**
- **Database-per-tenant** isolation using `spatie/laravel-multitenancy` — not shared tables with `tenant_id` (true data isolation, easier backups, better query performance)
- **WebSocket broadcasting** via Laravel Reverb — order status changes broadcast instantly to kitchen displays and customer tracking pages without polling
- **Feature-gating middleware** tied to subscription plans — `CheckFeature::class` enforces plan limits at the route level
- **Idempotent webhook handling** — every incoming payment event gets stored with a unique constraint before processing; duplicates return `200 OK` without reprocessing
- **Automated DB provisioning** — `TenantService` creates a new database, runs tenant migrations, and seeds default data on registration in one transaction

```
Stack: Laravel 11 · MySQL (per-tenant DB) · Redis · Laravel Reverb (WebSocket)
       Laravel Sanctum · Spatie Multitenancy · Tailwind CSS · Alpine.js
```

---

### 🛒 E-Commerce Platform
Multi-vendor store with cart management, Stripe payment integration, real-time inventory tracking, order management pipeline, and admin analytics dashboard.

```
Stack: Laravel · MySQL · Stripe API · REST API · Tailwind CSS · Sanctum
```

---

### 🏥 Hospital Management System
Healthcare platform managing patients, doctors, appointments, prescriptions, and billing. Role-based access control (Admin / Doctor / Receptionist) with real-time notifications and PDF report generation.

```
Stack: Laravel · Livewire · MySQL · Bootstrap · RBAC · PDF Generation
```

---

### 📱 Social Platform REST API
Scalable backend API with JWT authentication, follow system, posts with S3 media uploads, likes, comments, and real-time messaging. Fully documented with Postman collections.

```
Stack: Laravel Sanctum · JWT · MySQL · S3 Storage · Postman
```

---

### 🏡 Real Estate Listings Platform
Property listing platform with advanced search/filter, Google Maps geolocation, agent profiles, appointment scheduling, favorites, and SEO-optimized structure.

```
Stack: Laravel · MySQL · Google Maps API · jQuery · Bootstrap · SEO
```

---

### 🎓 Learning Management System
LMS with course creation, video processing via FFmpeg, quizzes, student progress tracking, certificate generation, and Stripe subscription billing.

```
Stack: Laravel · PHP · MySQL · Stripe · Tailwind · FFmpeg
```

---

## Work Experience

| Period | Role | Company |
|--------|------|---------|
| Jan 2024 – Present | Backend Developer (Freelance) | Remote — Self-Employed |
| Mar 2023 – Oct 2023 | Backend Developer — PHP | CodePress IT Solutions |
| Jun 2021 – Dec 2021 | Junior PHP Developer | Web Development Agency |

---

## Education

**B.Sc. Computer Science / Software Engineering**  
University of Palestine · 2019 – 2023 · **GPA: 85.71 / 100**

---

## How I Think About Hard Problems

**Preventing double spending in a wallet system:**
```
1. SELECT ... FOR UPDATE (pessimistic lock) inside a DB transaction
2. Deduction + transaction record in a single atomic operation
3. Idempotency key with UNIQUE constraint on the payments table
4. Version column (optimistic lock) as a safety net for high concurrency
```

**Handling duplicate webhook events:**
```
1. Store event ID in processed_webhooks with UNIQUE constraint
2. INSERT attempt — if duplicate key, return 200 immediately
3. Business logic runs only on successful insert
4. ShouldBeUnique job interface prevents queue duplicates
```

---

## Let's Connect

I'm currently open to **remote backend roles** and freelance projects.

📧 **mazinmajdy2001@gmail.com**  
💬 **WhatsApp:** +972 592 691 590  
🐙 **GitHub:** [github.com/mazin-majdy](https://github.com/mazin-majdy)  
🌐 **Portfolio:** [mazin-majdy.github.io](https://mazin-majdy.github.io)

---

<div align="center">
  <sub>Built with precision · Deployed with confidence · From Palestine 🇵🇸</sub>
</div>
