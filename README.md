# Fylo Cloud Storage

### Introduction

In this blog post, we will walk through the creation of a feature-rich cloud storage website using React. The site, inspired by Fylo, offers sections such as Home, Features, How It Works, Testimonials, and a Footer. Along the way, we will discuss the structure, components, and styling used to build this fully responsive website.


### Project Overview

This project consists of multiple sections aimed at showcasing a cloud storage service. Each section is built with React components for modularity and ease of maintenance. We will cover the following sections:
- Navbar
- Home
- Features
- How It Works
- Testimonials
- Footer


### Features
- **Responsive design**: The website adjusts to different screen sizes.
- **Modular Components**: Each section of the website is a separate React component, making it easy to maintain and extend.
- **Reusable Assets**: Images and other assets are imported once and reused across components.
- **CSS Styling**: The website uses custom CSS to style each component.


### Technologies Used

- **React**: Component-based front-end library.
- **CSS**: For styling the layout and appearance.
- **JavaScript**: Core logic for React components.
- **SVG Images**: Used for icons and graphics to enhance the UI.


### Project Structure

```bash
fylo-cloud-storage-website/
│
├── public/
│   ├── index.html
│
├── src/
│   ├── assets/
│   │   ├── images/
│   │   │   ├── icon-access-anywhere.svg
│   │   │   ├── icon-security.svg
│   │   │   ├── illustration-intro.png
│   │   │   └── ...
│   ├── components/
│   │   ├── Navbar.js
│   │   ├── Home.js
│   │   ├── Features.js
│   │   ├── Working.js
│   │   ├── Testimonials.js
│   │   └── Footer.js
│   ├── App.js
│   ├── App.css
│   └── index.js
```


### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/abhishekgurjar-in/fylo-cloud-storage.git
   ```

2. **Install dependencies**:
   ```bash
   cd fylo-cloud-storage-website
   npm install
   ```

3. **Run the application**:
   ```bash
   npm start
   ```

The website will be available on `http://localhost:3000/`.



### Live Demo
You can check out the live demo of this project [here](https://fylo-cloud-storage.netlify.app).

### Screenshots

![Screenshot 2024-09-11 062811](https://github.com/user-attachments/assets/e8daee4f-1ea7-4433-940c-c068a9e9e016)
![Screenshot 2024-09-11 062851](https://github.com/user-attachments/assets/bd05da09-3705-4ff0-84c2-fff004521bfd)
![Screenshot 2024-09-11 062906](https://github.com/user-attachments/assets/fcd1e936-8293-4ba2-a557-131c1c14fcf7)
![Screenshot 2024-09-11 062918](https://github.com/user-attachments/assets/6132341c-a592-44d8-9285-484ec9a64b2d)
![Screenshot 2024-09-11 062928](https://github.com/user-attachments/assets/3efed8d7-bcca-4cbb-a138-90a078d98fc7)


### Conclusion

In this post, we created a feature-rich, responsive website using React, showcasing a cloud storage service. We covered how to structure the project, break down the components, and style them using CSS. This modular approach makes it easy to add or update features as needed.


### Credits
This project is inspired by the Fylo cloud storage service design.


### Author

**Abhishek Gurjar** is a dedicated web developer passionate about creating practical and functional web applications. Check out more of his projects on [GitHub](https://github.com/abhishekgurjar-in).
