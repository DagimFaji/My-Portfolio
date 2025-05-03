# My-Portfolio
Dagim Faji Portfolio Website
Overview
This is a personal portfolio website for Dagim Faji, designed to showcase images and professional information. The site features a responsive design, a gallery for displaying pictures, and a client-side image upload feature. It is built using HTML, CSS (via Tailwind CSS), and JavaScript, making it lightweight and easy to deploy.
Features

Responsive Design: Adapts to various screen sizes using Tailwind CSS.
Image Gallery: Displays images in a grid layout with hover effects.
Image Upload: Allows users to upload images client-side, which are displayed in the gallery (images are not persisted without a backend).
Navigation: Includes sections for Home, Gallery, About, and Contact.
Professional Information: Highlights Dagim's IT background and contact details.

Setup Instructions

Clone or Download:
Download the project files or clone the repository to your local machine.


File Structure:
The main file is index.html, which contains the HTML, CSS (via Tailwind CDN), and JavaScript.
No additional dependencies are required since Tailwind CSS is loaded via CDN.


Run the Site:
Open index.html in a web browser (e.g., Chrome, Firefox) to view the site locally.
Alternatively, serve the file using a local server (e.g., npx live-server or Python’s http.server) for a better development experience.


Customization:
Update the text in the About and Contact sections to reflect your personal details.
Replace placeholder images in the gallery (<img src="https://via.placeholder.com/300x200">) with your own images by updating the src attribute or uploading via the site.
Modify colors and styles by adjusting Tailwind classes or adding custom CSS in the <style> tag.



Usage

Navigating the Site:
Use the navigation bar to jump between Home, Gallery, About, and Contact sections.


Uploading Images:
In the Gallery section, click "Choose File" to select an image from your device.
Click "Upload Image" to add the image to the gallery.
Note: Uploaded images are displayed client-side and will not persist after a page refresh without a backend.


Adding Permanent Images:
To add images permanently, include additional <div> elements in the #galleryGrid with <img> tags pointing to your image files (e.g., store images in a local images/ folder and reference them like src="images/your-image.jpg").



Deployment

Static Hosting:
Deploy the site to platforms like GitHub Pages, Netlify, or Vercel by uploading the index.html file and any associated image assets.


Adding a Backend (Optional):
To enable persistent image uploads, integrate a backend (e.g., Node.js with Express or Firebase) to handle file storage.
Contact me or consult documentation for your preferred backend to set this up.



Technologies Used

HTML5: Structure of the website.
Tailwind CSS: Styling and responsive design (loaded via CDN).
JavaScript: Handles image upload and dynamic gallery updates.

Notes

The image upload feature is client-side only, using the FileReader API to display images. For production, consider adding a backend to store images.
Ensure an internet connection to load Tailwind CSS from the CDN. For offline use, download Tailwind CSS and host it locally.
Tested on modern browsers (Chrome, Firefox, Edge).

Contact
For questions or support, reach out to Dagim Faji:

Email: dagimfaji@gmail.com
Phone: +251 937996667
LinkedIn: linkedin.com/in/dagm-faji-3484121ba

