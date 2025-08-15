📚 Fullstack LMS (Learning Management System) with Ruby on Rails 7
Markdown

# 📚 Fullstack LMS with Ruby on Rails 7

This project is a complete Learning Management System (LMS) built with Ruby on Rails 7, Hotwire, Tailwind CSS, Stripe, and PostgreSQL. It allows users to access free and paid courses, track their progress, and enables administrators to manage content, users, and sales.

---

## 🚀 Features

- User registration/login (Devise)
- View free and premium courses
- Course progress bar
- Video lessons (Active Storage)
- Purchase premium courses via Stripe
- Admin dashboard with user, sales, and lesson analytics
- Create/edit courses with rich text (Action Text)
- Drag & drop lesson ordering (Stimulus, acts_as_list)
- User and enrollment management
- User pagination and search
- 100% responsive interface

---

## 🛠️ Tech Stack

- Ruby on Rails 7
- Hotwire (Turbo & Stimulus)
- Tailwind CSS
- Stripe
- PostgreSQL
- Active Storage
- Devise
- Action Text
- acts_as_list
- Pagy
- groupdate

---

## ⚡ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-user/lms-rails7.git
   cd lms-rails7
Install dependencies:

Bash

bundle install
yarn install
Set up the database:

Bash

rails db:create db:migrate db:seed
Configure environment variables:

Stripe, AWS S3, etc. (see .env.example)
Start the server:

Bash

rails server
🧪 Tests
Bash

bundle exec rspec
🖼️ Screenshots
Admin Dashboard	Courses Page
Dashboard	Courses
💡 Best Practices
Separate authentication for admin and user
Use of partials for reusable UI components
SQL injection prevention
Webhooks for Stripe integration
Fully responsive design
