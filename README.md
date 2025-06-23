# MovieZone - Entertainment Hub

MovieZone is a Flask-based web application that serves as an entertainment hub for movies and web series. It features a modern UI with content categorization, search functionality, and an admin panel for content management.

## Features

- 🎬 **Movie & Web Series Catalog**
  - Trending content section
  - Latest movies and web series
  - Coming soon section
  - Detailed view for each content
- 🔍 **Search Functionality**
  - Search across all content
- 📱 **Responsive Design**
  - Works on mobile and desktop
- 🔒 **Admin Panel**
  - Add/edit/delete content
  - Manage advertisements
  - Basic authentication
- 📢 **Advertisement System**
  - Multiple ad types (banner, interstitial, native)
  - Position-based ad placement
  - Ad activation/deactivation

## Technology Stack

- **Backend**: Python with Flask
- **Database**: MongoDB (using PyMongo)
- **Frontend**: HTML5, CSS3, JavaScript
- **External APIs**: TMDb (for movie metadata)
- **Deployment**: Can be deployed on any WSGI-compatible server

## Installation

1. **Prerequisites**
   - Python 3.7+
   - MongoDB Atlas account or local MongoDB instance
   - TMDb API key (optional)

2. **Setup**

   ```bash
   # Clone the repository
   git clone https://github.com/yourusername/moviezone.git
   cd moviezone

   # Create and activate virtual environment (recommended)
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

   # Install dependencies
   pip install -r requirements.txt
