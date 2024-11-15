 **The Pawject**

Welcome to **The Pawject**—an interactive, responsive website chronicling the adventures of Jason, a quirky and mischievous cat. This site features Jason's blog, Instagram integration, and a contact page, all wrapped in a clean and accessible design.

---

## **Features**
- **Interactive Blog Section**:
  - Follow Jason's adventures through his monthly blog posts.
  - Filter and navigate blog posts easily.
  
- **Instagram Feed**:
  - Dynamic Instagram integration to display Jason’s latest posts.
  
- **Responsive Navigation**:
  - Mobile-friendly navigation with a hamburger menu for smaller screens.

- **Contact Page**:
  - Includes social links and a feature to copy Jason's email address directly to the clipboard.

- **Humorous Easter Egg Page**:
  - A playful OnlyFans-themed page adds a touch of humor.

## **Technologies Used**
### **Frontend**
- **HTML5**: Semantic and accessible markup for all pages.
- **CSS3**:
  - Custom styling for each section.
  - Media queries for responsive design.
- **JavaScript**:
  - Dynamic interactivity, such as fetching Instagram photos.
  - Toggle menu and copy-to-clipboard functionality.

### **APIs**
- **Instagram Graph API**:
  - Fetches and displays Jason's latest Instagram posts dynamically.

### **Frameworks and Libraries**
- **Bootstrap**: Used for styling and layout consistency.
- **FontAwesome**: Icons for navigation and social links.

---

## **Setup and Installation**
### Prerequisites
- A modern browser (Chrome, Firefox, Edge, Safari).
- Internet connection for fetching API data.

### Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/the-pawject.git
   ```
2. Navigate to the project directory:
   ```bash
   cd the-pawject
   ```
3. Open the `index.html` file in your browser:
   ```bash
   open index.html
   ```

---

## **Deployment**
The project is deployed on GitHub Pages and accessible at:
[https://yourusername.github.io/the-pawject](https://yourusername.github.io/the-pawject)

### Deployment Steps
1. Push the project to the `main` branch on GitHub.
2. Enable GitHub Pages under the repository settings.
3. Select the branch containing your site files (e.g., `main`).
4. Your site will be available at `https://yourusername.github.io/the-pawject`.

---

## **Usage Guide**
- **Navigating the Site**:
  - Use the navigation bar to move between the homepage, blog, about, and contact pages.
- **Following Jason on Instagram**:
  - Scroll down on the homepage to see Jason's latest Instagram posts.
- **Sending Fan Mail**:
  - Use the contact page to copy Jason's email or connect via Instagram.

---

## **API Configuration**
### Instagram Graph API
1. Obtain an access token by setting up an Instagram developer account.
2. Replace the placeholder access token in `index.html`:
   ```javascript
   const accessToken = 'your-access-token';
   ```

---

## **Known Issues**
- **Instagram Feed**: May not load if the access token expires.

---

## **Accessibility**
- All images include descriptive `alt` attributes.
- Keyboard navigation is fully supported.
- Color contrast has been tested for readability.

---

## **Performance**
- Lighthouse Performance Score: (Insert the performance score or report here).
- Optimization measures include:
  - Minimized CSS and JavaScript.
  - Responsive images and lazy loading for faster page load times.

---

## **License**
This project is licensed under the MIT License. Feel free to use and modify it as you wish.

