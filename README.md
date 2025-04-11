<!-- How To Edit And Host The Portfolio Website -->

**OVERVIEW**

This project is a portfolio website where all content is dynamically rendered using JavaScript. Users can update the content by modifying the files in the data folder, and all styling is managed in the style folder.

Directory Structure

📂 data
 ├── **personal-data.js**      # Personal information data
 ├── **projects-data.js**      # Data for projects
 ├── **services-data.js**      # Data for services
 ├── **meowish resume.pdf**    # Resume file

📂 images-and-icons
 ├── **icons**                 # Icon assets
 ├── **images**                # General images
 ├── **projects-logos**        # Logos for projects

📂 script
 ├── **gsap**                  # GSAP animations
 ├── **animations.js**         # Animation scripts
 ├── **header.js**             # Header scripts
 ├── **main.js**               # Main script file
 ├── **project-fullview.js**   # Full project view scripts
 ├── **render-contents.js**    # Dynamically renders content

📂 style
 ├── **sections-style**        # Section-specific styles
 ├── **background.css**        # Background styles
 ├── **footer.css**            # Footer styles
 ├── **global.css**            # Global styles
 ├── **header.css**            # Header styles
 ├── **project-fullview.css**  # Full project view styles

📄 **page.html**                # Main HTML file
📄 **project-fullview.html**     # Full project view HTML



**HOW TO UPDATE CONTENT**

🔹 Modify Data:

Navigate to the data folder.

Update the respective JavaScript files:

personal-data.js → Modify personal information.

projects-data.js → Update project details.

services-data.js → Change service offerings.

All updates will be automatically reflected since they are dynamically rendered in render-contents.js.

🎨 Update Styles:

Open the style folder.

Modify the CSS files to adjust the website’s design and appearance.

Notes

✅ Do not remove render-contents.js, as it dynamically loads data from the data folder.
✅ Ensure that the JavaScript object structures in the data folder remain consistent to prevent errors.


**HOST THE WEBSITE**

📌 Watch the tutorial here👉 [Easy Way to Host Your Website](https://youtu.be/3e_FVE4piEM?si=Zs3fJf6QOZm2LnBW)

**CONTACT ME**
📩 Need Help?
If you have any questions or need assistance, feel free to contact me at puyongharvey@gmail.com. I'm happy to help! 😊

Happy coding! 🚀