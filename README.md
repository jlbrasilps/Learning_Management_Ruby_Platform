🛒📚 Fullstack E-commerce & LMS with Ruby on Rails 7
This repository contains two robust fullstack applications built with Ruby on Rails 7:

E-commerce Platform
Learning Management System (LMS)
Both projects leverage modern Rails features (Hotwire, Tailwind CSS, Stripe, PostgreSQL) and demonstrate best practices for scalable, maintainable, and production-ready web applications.

🚀 Project Highlights
Fullstack architecture with Ruby on Rails 7 (backend & frontend)
Modern frontend: Hotwire (Turbo & Stimulus) for reactive UI, Tailwind CSS for fast styling
Secure authentication: Devise for users and admins (separate flows)
Stripe integration: Secure payments for products and courses
Active Storage: Image and video uploads, S3-ready for production
Admin dashboards: Analytics, inventory, user & order management
Mobile responsive: Fully responsive UI for all devices
Production deployment: PostgreSQL, S3, and Render deployment guides
🛠️ Tech Stack
Backend: Ruby on Rails 7, Devise, Active Storage, Pagy, acts_as_list, groupdate
Frontend: Hotwire (Turbo, Stimulus), Tailwind CSS, Action Text
Payments: Stripe (with webhooks)
Database: PostgreSQL (SQLite for dev), ActiveRecord
Deployment: Render, AWS S3
Other: Importmap, FFMpeg, libvips
📦 Project Structure
plaintext

.
├── ecommerce/
│   ├── app/
│   ├── config/
│   └── ...
├── lms/
│   ├── app/
│   ├── config/
│   └── ...
├── screenshots/
│   ├── ecommerce-dashboard.png
│   ├── lms-courses.png
│   └── ...
└── README.md
🖼️ Screenshots
E-commerce Dashboard	LMS Courses Page
E-commerce Dashboard	LMS Courses
🛒 E-commerce Application
Customer Side
Browse products by category or search
Add/remove items to cart (localStorage)
Checkout with Stripe integration
Order tracking and email notifications
Admin Side
Dashboard with sales analytics and recent orders
Product management: create/edit products, manage inventory by size, upload multiple images
Category management
Order management: view, fulfill, and track orders
Secure admin authentication
Key Features
Hotwire for dynamic UI (cart updates, drag & drop)
Pagy for fast pagination
Active Storage for images
Stripe webhooks for order/payment sync
📚 LMS Application
User Side
Sign up/login (Devise)
Browse free and premium courses
Track course progress
Watch video lessons (Active Storage)
Purchase premium courses via Stripe
Mobile responsive
Admin Side
Dashboard with user, sales, and lesson analytics
Create/edit courses (Action Text for rich descriptions)
Drag & drop lesson ordering (Stimulus, acts_as_list)
Manage users and course enrollments
Paginated user tables and search
Key Features
Hotwire for interactive UI (drag & drop, progress bars)
Active Storage for video/image uploads (S3-ready)
Stripe for course payments
Action Text for rich content editing
⚡ Getting Started
Clone the repository:

Bash

git clone https://github.com/your-user/your-repo.git
cd ecommerce # or lms
Install dependencies:

Bash

bundle install
yarn install # if using JS packages
Setup database:

Bash

rails db:create db:migrate db:seed
Configure environment variables:

Stripe keys, AWS S3, etc. (see .env.example)
Run the server:

Bash

rails server
💡 Best Practices & Tips
Separate authentication for users and admins
Use partials for reusable UI components
Always sanitize user input (SQL injection prevention)
Use webhooks for external event sync (e.g., Stripe)
Store secrets securely (Rails credentials)
Responsive design for all devices
🤝 Contributing
Contributions are welcome!
Open an issue or submit a pull request.

📄 License
MIT License

👤 Author
Your Name
LinkedIn | GitHub
