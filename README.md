# Blog Site with Django

Welcome to our Blog Site built using Django! This README will guide you through the features of our blog, how to set it up, and how to contribute to its development.

## Features

1. **User Authentication:** Users can register, login, and logout securely to access the blog features.
2. **Record Views:** The site records views for each post, helping to understand the popularity of posts.
3. **Create and Publish Posts:** Authenticated users can create, edit, and publish their own posts.
4. **Responsive Design:** The site is designed to be responsive, ensuring a smooth user experience across devices.

## Setup

1. **Clone the Repository:**
   ```
   git clone https://github.com/KalminX/blog_sitemap.git
   cd blog_sitemap
   ```

2. **Install Dependencies:**
   ```
   pip install -r requirements.txt
   ```

3. **Apply Migrations:**
   ```
   python manage.py migrate
   ```

4. **Create a Superuser:**
   ```
   python manage.py createsuperuser
   ```

5. **Run the Server:**
   ```
   python manage.py runserver
   ```

6. **Access the Site:**
   Visit `http://localhost:8000` in your browser.

## Contributing

We welcome contributions from the community to make our blog site even better! Here's how you can contribute:

1. **Fork the Repository:** Click the 'Fork' button on the GitHub page.
2. **Clone Your Fork:** Clone the forked repository to your local machine.
3. **Make Changes:** Make your desired changes to the codebase.
4. **Commit Changes:** Commit your changes and push them to your fork.
5. **Open a Pull Request:** Submit a pull request with your changes for review.
