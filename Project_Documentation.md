# TasteHaven - Project Documentation

## Section 1: Detailed Explanation

### Project Overview
TasteHaven is a responsive food delivery website frontend built using HTML, CSS, and JavaScript. The project demonstrates modern web design principles with a focus on user experience and mobile responsiveness. This documentation provides a beginner-friendly explanation of the project's structure, functionality, and code organization.

### Project Structure
The project consists of the following key files:

1. **index.html** - Main HTML file containing the website structure
2. **style.css** - CSS file for styling the website elements
3. **app.js** - JavaScript file containing interactive functionality
4. **images/** - Directory containing food item images

### Detailed Code Breakdown

#### HTML Structure (index.html)

The HTML file is structured into several main sections:

1. **Head Section**
   - Contains metadata, viewport settings, and CSS/font links
   - Sets the document title "Food Delivery Services"
   - Links to Google Fonts for the Open Sans font family
   - Links to the external style.css file

2. **Sidebar**
   - Logo: Displays the brand name "TasteHaven"
   - Menu: Navigation links with Ionicons (Home, Bills, Wallet, etc.)
   - Logout: Option to log out with an icon

3. **Main Content**
   - Navbar: Contains mobile menu toggle, search bar, and profile icons
   - Recommendations: Horizontal scrollable section with food cards
   - Menu Categories: Filtering options with icons for food types
   - Choose Order: Grid display of food items with details

#### CSS Styling (style.css)

The CSS file uses a modular approach with variables for consistent theming:

1. **CSS Variables**
   - Color scheme using CSS custom properties (--primaryColor, --secondaryColor, etc.)
   - Makes theme changes easy to implement site-wide

2. **Base Styling**
   - Reset styles (margin, padding, box-sizing)
   - Basic layout with flexbox for the main container

3. **Sidebar Styling**
   - Fixed position sidebar with brand colors
   - Hover effects for menu items
   - Icon and text alignment

4. **Main Content Styling**
   - Responsive grid layouts for food items
   - Card styling with shadows and hover effects
   - Search bar and button styling

5. **Responsive Design**
   - Media queries for different screen sizes
   - Mobile-first approach with adjustments for larger screens
   - Hamburger menu for mobile navigation

#### JavaScript Functionality (app.js)

The JavaScript file handles the interactive elements:

1. **Mobile Menu Toggle**
   - Shows/hides the sidebar on mobile when the hamburger icon is clicked
   - Adds/removes active classes for animation

2. **Horizontal Scrolling**
   - Controls the recommendation carousel navigation
   - Uses jQuery to animate scrolling when arrows are clicked

3. **Menu Category Navigation**
   - Horizontal scrolling for the filter categories
   - Back and next button functionality

### Step-by-Step Functionality Explanation

1. **Website Loading**
   - When the site loads, it displays the sidebar (on desktop) or just the navbar (on mobile)
   - The recommendations carousel and menu categories are populated

2. **Navigation**
   - Users can navigate using the sidebar links
   - On mobile, the hamburger menu toggle reveals/hides the sidebar

3. **Search Functionality**
   - Users can enter food items in the search bar
   - The search button initiates the search (frontend only in this version)

4. **Browsing Food Items**
   - Recommendations section shows featured items with horizontal scrolling
   - Menu categories allow filtering by food type
   - The "Choose Order" section displays all available menu items

5. **Mobile Responsiveness**
   - The layout adjusts based on screen size
   - On smaller screens, the sidebar becomes hidden and accessible via the hamburger menu
   - Grid layouts change to accommodate different screen sizes

## Section 2: CV Entry

**TasteHaven Food Delivery Website | HTML5, CSS3, JavaScript | jQuery, Responsive Design, Flexbox/Grid | 2023**

- *Designed and developed a responsive food delivery website frontend with an intuitive and visually appealing UI for browsing and ordering food online.*
- *Implemented key functionalities including responsive navigation, search system, food category filtering, scrollable recommendations carousel, and detailed menu display.*
- *Created a mobile-first design with CSS variables for consistent theming, Flexbox/Grid layouts, and jQuery for enhanced UI interactions.*
- *Incorporated modern web design principles to ensure seamless user experience across all device sizes, improving engagement and accessibility.*
- *Utilized semantic HTML, modular CSS, and efficient JavaScript to create a scalable and maintainable codebase.*

### Technical Achievements:
- Built a fully responsive layout that adapts to various screen sizes
- Implemented interactive UI elements like carousels and filtering system
- Created a visually consistent design using CSS variables and custom properties
- Designed an intuitive navigation system for both desktop and mobile users
- Optimized for performance with minimal dependencies 