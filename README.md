# 📸 Media Sharing Platform – Ruby on Rails

This is a web application built with Ruby on Rails, designed to let users share visual content, interact with other posts, and manage their own profile information. The goal is to provide a rich user experience and all the essential features for a modern media sharing platform.

---

## 🚀 Features

- **User Authentication:**  
  - Sign up, log in, and log out.
  - Edit profile details (bio, username, profile photo).

- **Post Management:**  
  - Create, read, update, and delete posts.
  - Each post includes a title, description, and keywords.

- **Image Uploads:**  
  - Support for uploading multiple images per post using integrated storage.

- **User Profiles:**  
  - Each user has a profile displaying email, username, bio, and profile photo.

- **Comments:**  
  - Users can add and view comments on posts.

- **Like System:**  
  - Like and unlike posts, with a visible like counter.
  - Each user can like a post only once.

- **Follow System:**  
  - Users can follow and unfollow others.
  - Option to auto-accept follow requests.
  - View lists of followers and following.

- **Content Navigation & Discovery:**  
  - **My Posts:** Section to view only your own posts.
  - **User Search:** Search bar to find users by username.
  - **Discovery Page:** Explore new posts, including those from users you don’t follow.

- **Admin Dashboard:**  
  - Exclusive panel for admins to view, edit, and delete all posts, users, likes, and comments.
  - Only users with admin permissions can access.

- **Traffic Analytics:**  
  - Integrated analytics tool to track page views, sources, and navigation.
  - Privacy-focused: no cookies or third-party tracking.

- **Dynamic Pagination:**  
  - Posts are loaded as needed for a seamless infinite scroll experience.

- **Static Pages:**  
  - Support for fixed content pages, such as an "About" page.

---

## 🛠️ Tech Stack

- **Ruby on Rails:** Main web framework for rapid development.
- **Ruby:** Underlying programming language.
- **HTML (ERB):** For web content structure with embedded Ruby.
- **CSS (Bootstrap):** Responsive UI design using the Bootstrap CSS library.
- **PostgreSQL:** Relational database management system.
- **Puma:** Default web server for Rails applications.

### **Key Gems & Libraries**

- **Devise:** Robust user authentication system.
- **Active Storage:** Integrated file upload management (images, attachments).
- **Followability:** Easy implementation of follow/unfollow system.
- **Ransack:** Advanced search and filtering.
- **Rails Admin:** Customizable admin dashboard.
- **Pagy:** Lightweight gem for optimized pagination and content loading.
- **Active Analytics:** Private traffic metrics collection.

---

## ⚡ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-user/media-sharing-rails.git
   cd media-sharing-rails
Install dependencies:

Bash

bundle install
yarn install
Set up the database:

Bash

rails db:create db:migrate db:seed
Configure environment variables:

(e.g., storage, analytics, etc. – see .env.example)
Start the server:

Bash

rails server
Access the app:
Open http://localhost:3000 in your browser.

🧪 Tests
Bash

=
💡 Best Practices
Secure authentication and authorization
Modular, DRY codebase with partials and helpers
Privacy-focused analytics (no cookies/third-party)
Responsive design for all devices
Admin-only access to sensitive features
📄 License
MIT License

Thank you for visiting! If you like this project, please star the repo and follow me on GitHub.
Happy coding! 🚀
