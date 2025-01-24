# 📚 Bookshelf Buddy

## 🌟 Project Overview

Bookshelf Buddy is a full-stack web application for managing your personal book collection. Easily add, edit, delete, and track your favorite books with a simple and intuitive interface.

## ✨ Features

- 📖 Add new books to your collection
- 🖊️ Edit book details
- 🗑️ Remove books from your library
- 🌐 Dynamically fetch book cover images
- 📊 Rate and track your books

## 🛠️ Technologies Used

- Node.js
- Express.js
- PostgreSQL
- EJS Templating
- Body-Parser
- OpenLibrary API (for book covers)

## 🚀 Getting Started

### Prerequisites

- Node.js
- PostgreSQL
- npm

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/bookshelf-buddy.git
   ```

2. Install dependencies
   ```bash
   cd bookshelf-buddy
   npm install
   ```

3. Setup Database
   - Create a PostgreSQL database named 'books'
   - Run the queries from `queries.sql`

4. Configure Database Connection
   - Update database credentials in `index.js`

5. Start the server
   ```bash
   node index.js
   ```

## 🖥️ Usage

- Add a new book by filling out the form
- View your book collection
- Edit book details
- Delete books from your collection
- Book covers automatically fetch from OpenLibrary


Happy Reading! 📖✨
