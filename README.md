# GlowBlog - Multi-Theme Blog Platform

A modern, feature-rich blog posting platform with authentication, multiple themes, and multimedia support. Built with pure HTML, CSS, and vanilla JavaScript.

## 🌟 Features

### Authentication System
- **Sign Up**: New user registration with username, email, and password
- **Login**: Secure login system with credential validation
- **Session Management**: Tracks logged-in users and restricts post creation to authenticated users
- **Logout**: Clean session termination

### Blog Posting
- **Create Posts**: Logged-in users can create blog posts with:
  - Title (required)
  - Text description/content (required)
  - Image URL (optional)
  - Video URL (optional - supports YouTube embeds and direct video links)
- **View Feed**: Browse all posts from all users in a beautiful card-based layout
- **Author Information**: Each post displays the author's name and timestamp
- **Multimedia Support**: Full support for images and embedded videos

### Theme Switcher (3 Themes)
1. **Glow Theme** (Default)
   - Dark cyberpunk aesthetic with neon cyan/purple glowing effects
   - Stunning glow effects on cards, buttons, and interactive elements
   - Perfect for a futuristic, immersive experience

2. **Light Theme**
   - Clean, professional white background
   - Soft shadows and high readability
   - Ideal for daytime browsing

3. **Dark Theme**
   - Comfortable dark gray color scheme
   - Muted purple accents
   - Easy on the eyes for nighttime reading

### Responsive Design
- Mobile-first approach
- Adaptive layouts:
  - **Desktop**: 3-column grid
  - **Tablet**: 2-column grid
  - **Mobile**: Single column
- Touch-friendly interface

## 🚀 Getting Started

### Installation
1. Download the `index.html` file
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. No installation or dependencies required!

### Usage

#### For New Users
1. Click the "Sign Up" link on the login page
2. Fill in the registration form:
   - Username (unique identifier)
   - Email address
   - Password
   - Confirm password
3. Click "Sign Up" to create your account
4. You'll be redirected to the login page

#### For Existing Users
1. Enter your email/username and password
2. Click "Login"
3. You'll be redirected to the main blog feed

#### Creating Blog Posts
1. After logging in, click the "Create New Post" button
2. Fill in the post creation form:
   - **Title**: Give your post a catchy title
   - **Description**: Write your blog content
   - **Image URL** (optional): Paste a direct image URL to include a featured image
   - **Video URL** (optional): Paste a YouTube URL or direct video link
3. Click "Post" to publish your blog
4. Your post will appear instantly in the feed

#### Switching Themes
- Use the theme switcher dropdown in the header
- Choose from Glow, Light, or Dark themes
- Your theme preference is saved for the current session

#### Logging Out
- Click the "Logout" button in the header
- You'll be redirected to the login page

## 📋 Sample Data

The platform comes pre-loaded with sample users and posts to demonstrate functionality:

### Sample Users
- `tech_explorer` - Posts about web development and technology
- `creative_mind` - Shares creative and design content
- `story_teller` - Focuses on storytelling and narratives

### Sample Posts
- Posts with images
- Posts with embedded videos
- Text-only posts
- Mix of different content types

## 🎨 Theme Customization

Each theme has its own color scheme defined in the CSS:

### Glow Theme
- Background: Deep blue-black (#0a0e27)
- Cards: Dark blue (#1a1f3a)
- Accent: Cyan (#00f3ff)
- Special: Neon glow effects

### Light Theme
- Background: Light gray (#f5f5f5)
- Cards: White (#ffffff)
- Accent: Blue (#2196F3)
- Special: Soft shadows

### Dark Theme
- Background: Dark charcoal (#1a1a1a)
- Cards: Medium gray (#2d2d2d)
- Accent: Purple (#bb86fc)
- Special: Subtle elevation

## 💾 Data Storage

**Note**: This is a client-side application using in-memory storage (JavaScript objects/arrays). All data is stored in the browser's memory and will be reset when you refresh the page.

### Stored Data
- **Users**: Array of user objects (id, username, email, password, createdAt)
- **Posts**: Array of post objects (id, authorId, title, description, imageUrl, videoUrl, createdAt)
- **Session**: Current user and theme preference

## 🔒 Security Note

This is a demonstration/educational project. In a production environment, you should:
- Use proper backend authentication with encrypted passwords
- Implement HTTPS for secure communication
- Use database storage instead of in-memory arrays
- Add CSRF protection
- Implement rate limiting
- Sanitize user inputs to prevent XSS attacks
- Use secure session management with tokens

## 🌐 Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (v90+)
- Firefox (v88+)
- Safari (v14+)
- Opera (v76+)

## 📱 Mobile Support

Fully responsive and optimized for:
- Smartphones (320px - 767px)
- Tablets (768px - 1023px)
- Desktops (1024px+)

## 🎯 Key Technical Features

- Pure vanilla JavaScript (no frameworks required)
- CSS3 animations and transitions
- Flexbox and Grid layouts
- CSS custom properties for theming
- Form validation
- Responsive images and videos
- Accessible HTML5 semantics
- Cross-browser compatible

## 🛠️ Customization

You can easily customize the platform by modifying:

### Colors
Edit the theme-specific CSS classes (`.glow-theme`, `.light-theme`, `.dark-theme`)

### Layout
Adjust the grid columns in the `.posts-grid` media queries

### Sample Data
Modify the `initializeSampleData()` function to change or add sample posts and users

### Features
Add new functionality by extending the JavaScript code sections

## 📝 Code Structure

```
index.html
├── HTML Structure
│   ├── Login Page
│   ├── Sign Up Page
│   ├── Main Feed Page
│   └── Post Creation Modal
├── CSS Styles
│   ├── Theme Definitions
│   ├── Layout Styles
│   ├── Component Styles
│   └── Responsive Media Queries
└── JavaScript
    ├── Data Management
    ├── Authentication Logic
    ├── Post Management
    ├── Theme Switching
    └── UI Interactions
```

## 🤝 Contributing

This is an educational project. Feel free to:
- Fork and modify for your own use
- Add new features
- Improve the design
- Enhance security for production use

## 📄 License

Free to use for educational and personal projects.

## 🎓 Learning Outcomes

This project demonstrates:
- Authentication flow implementation
- State management in vanilla JavaScript
- CSS theming with custom properties
- Responsive web design principles
- Form handling and validation
- Dynamic content rendering
- Event-driven programming
- Modern CSS techniques (Grid, Flexbox, animations)

## 💡 Future Enhancement Ideas

- Add comment system for posts
- Implement like/reaction functionality
- Add user profiles with bio and avatar
- Search and filter posts
- Post categories/tags
- Image/video upload (not just URLs)
- Rich text editor for post content
- Pagination for large number of posts
- User following system
- Notification system
- Dark mode auto-detection based on system preferences

---

**Enjoy blogging with GlowBlog!** ✨

For questions or issues, feel free to modify the code to suit your needs.
