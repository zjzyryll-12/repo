# Laravel Portfolio - Zyryll Jemson B. Galang

A personal portfolio website built with Laravel showcasing my educational background, projects, and GitHub repositories. This static portfolio demonstrates web development skills using Laravel Blade templating without database dependencies.

## Features

- **Responsive Design**: Mobile-friendly layout that adapts to different screen sizes
- **Clean Navigation**: Easy navigation between portfolio sections
- **Personal Information**: Contact details and professional bio
- **Educational Timeline**: Complete educational background from elementary to college
- **Project Showcase**: Grid layout displaying portfolio projects
- **GitHub Integration**: Direct links to GitHub repositories

## Tech Stack

| Category | Technology |
| :--- | :--- |
| **Framework** | Laravel 13.8 |
| **Templating** | Blade (`.blade.php`) |
| **Styling** | Custom CSS & Tailwind CSS |
| **Build Tool** | Vite |
| **Database** | None (Static content) |

## Project Structure

```text
repository/
├── resources/
│   ├── views/
│   │   ├── layouts/
│   │   │   └── app.blade.php      # Main layout template
│   │   └── portfolio.blade.php     # Portfolio content
│   ├── css/
│   │   └── app.css                 # Custom styling
│   └── js/
│       ├── app.js                  # JavaScript entry point
│       └── bootstrap.js            # Bootstrap configuration
├── public/
│   └── image/
│       └── me.jpg                  # Profile picture
├── routes/
│   └── web.php                     # Web routes
└── PROMPT_LOG.md                   # AI prompt documentation
