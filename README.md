# K.S.R. College Complaint Management System – Frontend

Pure HTML + CSS + JavaScript. No install, no build step.

## Run
Double-click `index.html`, or serve the folder:
    python -m http.server 5500      # then open http://localhost:5500
(VS Code: "Live Server" extension also works.)

## Pages
| File | Screen |
|---|---|
| index.html | 1. Home page |
| login.html | 2. Login (Student / Admin) |
| register.html | 3. Register |
| dashboard.html | 4. Student dashboard |
| submit-complaint.html | 5. Submit complaint |
| track-complaint.html | 6. Track complaint |
| my-complaints.html, profile.html, feedback.html | Sidebar pages |
| admin.html, admin-feedback.html, admin-users.html | Admin panel |

## Demo login
Admin: admin@ksrce.ac.in / admin123
Students: register on register.html first.

## Data
Everything is stored in the browser's localStorage (see the DATA LAYER section in js/app.js).
To connect a real backend (Node / Spring / PHP), replace the Auth, Complaints and Feedback
functions with fetch() calls to your API.

## College photo
Put your campus photo at assets/campus.jpg – it replaces the illustration on the home page automatically.
