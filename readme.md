<div align="center">
  <h1>✍️ Django Blogging System</h1>
  <p>A fully-featured blogging application built with Python and Django.</p>
</div>

---

<!-- 🎥 DEMO VIDEO SPACE -->
> **Demo Video Placeholder:**
> *[Manually attach your demo video or GIF here!]*
<br/>

## 📖 Overview
This robust platform provides an engaging frontend for readers to explore content and a comprehensive administrative dashboard for authors to manage the platform. 

Whether you're looking to share your thoughts, build a categorized knowledge base, or foster community discussions through comments, this blogging system has you covered.

## ✨ Key Features

### 🏢 Frontend Experience
- **Dynamic Homepage:** Features top-featured posts, latest posts, and "About Us" information.
- **Categorized Reading:** Seamlessly browse posts filtered by specific categories.
- **Rich Search Functionality:** Quickly find specific blogs by title, description, or content.
- **Integrated Comments:** Authenticated users can leave and share comments on individual blog posts.

### 🛡️ Secure Dashboard & Admin Panel
- **User Authentication:** Secure registration, login, and logout functionalities built natively with Django.
- **Manage Categories:** Intuitive interface to add, edit, or delete blog categories.
- **Manage Posts:** Create rich blog posts with featured image uploads, automatic slug generation based on titles, publish/draft statuses, and featured flags.
- **Manage Users:** Admin privileges allowing you to view, add, edit, or remove users from the platform.

## 🛠️ Technology Stack
- **Backend:** Python, Django 4.x
- **Database:** SQLite (default for development)
- **Frontend UI:** HTML, CSS, Django Templates Structure
- **File Management:** Django's native media handling for images and uploads.

## ⚙️ Installation & Setup

Want to run this project locally? Follow these steps:

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd blogging-system-yt
   ```

2. **Create a virtual environment (optional but highly recommended):**
   ```bash
   python -m venv venv
   # On macOS/Linux:
   source venv/bin/activate
   # On Windows:
   venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```
   *The application will now be accessible at `http://127.0.0.1:8000/`*

## 🗂️ Project Structure High-Level View

- `blog_main/`: Core Django configurations, base URLs, and primary authentication views.
- `blogs/`: The heart of the platform handling core models (`Category`, `Blog`, `Comment`), dynamic views, and the search engine.
- `dashboards/`: The dedicated admin author panel providing straightforward CRUD interfaces to take control of your content.
- `assignments/`: Specialized app handling static-like data instances like 'About Us'.
- `templates/`: Centralized hub for all unified user-facing HTML structure pages.

