# 🧠 Inventhoria

**Inventhoria** is a next-gen intelligent marketplace platform that allows anyone to effortlessly create, personalize, and manage their own online store — powered by AI-driven tools and automation. Sellers can extract products directly from Instagram, beautify them with smart enhancement tools, and launch their online shop with full identity control.

---

## 🚀 Features (MVP)

- 🧠 **AI-Assisted Product Creation** from Instagram posts (image + caption analysis)
- 🛍️ **Multi-vendor Marketplace** architecture
- 🎨 **Highly customizable storefronts**
- 🔐 **Secure authentication** via Laravel Breeze
- 📦 **Modular Laravel + React architecture**
- 🛡️ **Built-in fraud detection system**

---

## 🧱 Tech Stack

| Layer       | Technology        |
|-------------|-------------------|
| Backend     | Laravel 11 (PHP)  |
| Frontend    | React + Vite      |
| Auth        | Laravel Breeze    |
| Database    | MySQL/PostgreSQL  |
| AI Service  | Python Microservice (Flask or FastAPI) |
| Dev Tools   | Composer, NPM, Artisan CLI |
| Deployment  | Docker (optional), VPS or PaaS |

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-org/inventhoria.git
cd inventhoria
```

### 2. Backend Setup (Laravel)

```bash
composer install
cp .env.example .env
php artisan key:generate

php artisan migrate
```

### 3. Frontend Setup (React + Vite)

```bash
npm install
npm run dev
```

### 4. Launch the App

```bash
php artisan serve
```

Visit: [http://localhost:8000](http://localhost:8000)

---

## 📦 Folder Structure

```
├── app/             # Laravel backend code
├── resources/js/    # React frontend components
├── routes/          # Web and API routes
├── database/        # Migrations, seeders
├── public/          # Public assets
├── .env             # Environment variables
```

---

## 🔐 Environment Variables (.env)

```
APP_NAME=Inventhoria
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_DATABASE=inventhoria
DB_USERNAME=root
DB_PASSWORD=
```

---

## 🧪 Testing

```bash
php artisan test
```

---

## 🛠️ Planned Features (Phase 2)

- PDF/Image-based product extraction
- Headless mode for embedding stores anywhere
- Complete analytics dashboard
- Drag-and-drop storefront editor
- Subscription plans + checkout integration

---

## 🧠 AI Microservice (Instagram Parser)

A Python microservice is used to extract product data from Instagram posts. It analyzes:

- **Image**: Category, color, style
- **Caption**: Name, price, keywords
- **Hashtags/Location**: Product tags, geodata

> Microservice details will be in `ai-parser/README.md`.

---

## 🧾 License

[MIT](LICENSE)

---

## ✨ Tagline

**Shape your product. We shape the world around it.**