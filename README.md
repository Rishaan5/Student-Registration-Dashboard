# Student-Registration-Dashboard
Simple student registration dashboard made with HTML
Here is a clean and informative **README.md** file for your Student Registration Dashboard HTML project:

## Student Registration Dashboard

A clean, modern, single-page **Student Registration Dashboard** with role-based access (Student & Admin), dark/light theme support, form validation, localStorage persistence, and CSV export functionality.

Built with **HTML** — no frameworks or backend required.




## Features

- 🌗 **Light / Dark mode** toggle (persisted in localStorage)
- 👤 **Two roles**: Student & Admin
- 🔐 Simple admin login (username: `admin` / password: `admin2026`)
- 📝 Student registration form with validation
- 🛡️ Duplicate prevention (email & roll number)
- 📋 Admin panel to view, edit, delete student records
- 📤 Export student list as **CSV**
- 💾 Data persistence using **localStorage**
- 📱 Responsive design (mobile-friendly layout)
- 🎨 Modern card-based UI with smooth animations & hover effects
- ℹ️ Contact modal & footer



## How to Use

1. Open `student_registration_dashboard.html` (or whatever you named the file) in any modern browser
2. Choose your role:
   - **Student** → fill the registration form
   - **Admin** → login with:
     ```
     Username: admin
     Password: admin2026
     ```
3. Students can register themselves
4. Admins can:
   - View all registrations
   - Edit student details
   - Delete records
   - Export data as CSV
   - Add new students manually

## Tech Stack

- HTML5
- CSS3 (custom variables + modern layout techniques)
- Vanilla JavaScript (ES6+)
- Font Awesome 6 (icons)
- localStorage (data persistence)

No build tools, no node_modules, no frameworks.

## Default Credentials

```text
Admin:
  Username : admin
  Password : admin2026
```

> **Important**: This is a frontend-only demo. Credentials are hardcoded in JavaScript — do **not** use in production.

## Project Structure

```
student-dashboard/
├── sdb.html          ← main file (rename if needed)
├── README.md         ← this file
└── (no other files — everything is inline)
```

## Future Improvements (Ideas)

- Add search/filter in admin table
- Input for profile picture upload (base64 in localStorage)
- Better password handling for admin
- Pagination for large student lists
- Print/student ID card generation
- Import students from CSV
- Move admin credentials to a more secure pattern (even for demo)

## License

MIT License

Feel free to use, modify, and share.  
Created with ❤️ in 2026.

---

Made as a learning / portfolio project  
Last updated: February 2026
```

Happy coding!
