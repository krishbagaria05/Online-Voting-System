# 🗳️ Online Voting System (PHP & MySQL)

A secure and user-friendly online voting system built using PHP, MySQL, HTML, CSS, JavaScript, and Bootstrap. This project allows administrators to manage elections and lets registered voters cast votes in a fair and streamlined way.

---

## Features

###  Admin
- Admin login/logout
- Add/edit/delete candidates
- Add/edit/delete voters
- Export voters list and election reports (Excel)
- View activity logs
- Monitor live vote tally

### Voter
- Secure login
- Cast one vote per election (vote duplication is blocked)
- Simple, intuitive UI

---

## Technologies Used

- **Backend**: PHP (Procedural)
- **Database**: MySQL
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap
- **Utilities**: PHPExcel (for report export)

---

## Installation Instructions

1. **Install XAMPP** or any web server stack with PHP & MySQL support.
2. Start **Apache** and **MySQL** via the control panel.
3. Extract the project folder to:  
   `C:\xampp\htdocs\Online_voting_system`
4. Open **phpMyAdmin** and create a new database named: `ovs`
5. Import the SQL file:
   - Go to `phpMyAdmin` > `ovs` > `Import`
   - Select the file: `/db/ovs.sql`
6. Open the project in your browser:  
   `http://localhost/Online_voting_system`

---

## Default Admin Credentials

Username: admin
Password: admin

Name: Krish Bagaria
Institution: Amity University
Date: 19-07-2025
