# QRAlliymi Website – News Page Task

This repository contains the **QRAlliymi News Page (QR알리미 소식)**, which provides a carousel-style news section aligned with the design and navigation standards of the QRAlliymi site.

## 📁 Project Directory: `QR/`

Here is the complete structure and explanation of the `QR/` directory:

```bash

QR/
├── css/                   
├── docs/               
├── fonts/                
├── Home_Images/         
├── Home_Video/           
├── imgs/
├── News_Page/
       ├── News_Images/    # ✅ All images used for News slider and sections
       ├── index.html      # ✅ Final Newspage file (all inline CSS/JS)          
├── js/                  
├── PHPMailer/             
├── QRUserGuide/           
├── term/                
├── vendor/               
├── composer.json         
├── composer.lock         
├── index.html              
├── index_old_design.html  
├── reset.css             
```

## 🎯 Key Features Implemented

✅ Fully responsive news page design
✅ Interactive image carousel with left/right navigation
✅ Popup functionality on card click to display full-size images
✅ Consistent styling with QRAlliymi branding and navigation
✅ All content styled with inline CSS for easy deployment
✅ Navigation bar and footer consistent with other QRAlliymi pages

## 📥 How to Use

### Clone or download the repository.

Move the folder into `C:\xampp\htdocs\` (or your server directory).

### Open your browser and go to:

```bash
http://localhost/QRAlliymi_website-main/News/index.html
```

### Make sure to also download all contents inside:

* `News_Images/`

## 📝 Additional Notes

* Design is based on existing QRAlliymi visual guidelines.
* News images can be updated by replacing or adding `.png` files inside the `News_Images/` directory and updating the `data-popup-image` attributes accordingly.
* All functionality (popup, carousel scroll) is handled via inline JavaScript for maximum portability.
* This page can be integrated seamlessly into any existing QRAlliymi layout due to consistent navigation structure and class naming.

---

Let me know if you also want a Korean version of this README or need to generate a GitHub-style `README.md` file directly.
