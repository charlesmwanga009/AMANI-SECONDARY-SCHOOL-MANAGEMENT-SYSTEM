# AMANI-SECONDARY-SCHOOL-MANAGEMENT-SYSTEM
Welcome to the Amani School Management System Preview. This prototype demonstrates the core functionality of the system with a fully interactive frontend.

## Getting Started

### Accessing the System
1. Navigate to the `public/` directory in your project folder.
2. Open the file `login_preview.html` in your web browser (Chrome, Edge, Firefox, etc.).

### Login Credentials

By default, the following demo accounts are available:

| Role | Email | Password | Dashboard |
| :--- | :--- | :--- | :--- |
| **System Admin** | `admin@amani.com` | `admin123` | Main Dashboard (`preview.html`) |
| **Head of School** | `head@amani.com` | `head123` | Headmaster's Office (`head_dashboard_preview.html`) |
| **Finance / Bursar** | `finance@amani.com` | `finance123` | Finance Management (`finance_preview.html`) |
| **Teacher** | `teacher@amani.com` | `teacher123` | Teacher Dashboard (`teacher_dashboard_preview.html`) |
| **Librarian** | `library@amani.com` | `library123` | Library Management (`librarian_dashboard_preview.html`) |

*Tip: You can register new users via the Admin "Staff Management" page. The role you select (e.g., "Head of School") will automatically route them to the correct dashboard upon login.*

---

## Features Overview

### 1. Dashboard (`preview.html`)
*   Provides a high-level overview of the school's performance.
*   **Stats:** View real-time Total Students, Fee Collection, and Active Classes.

### 2. Head of School Dashboard (`head_dashboard_preview.html`)
*   **Executive Overview:** High-level details relevant to school leadership.
*   **Announcements:** Post messages to the staff board.

### 3. Student Management (`students_preview.html`)
*   **CRUD:** Enrol, Edit, Delete, and View students.
*   **Data Persistence:** Changes are saved to Local Storage.

### 4. Finance (`finance_preview.html`)
*   **Payments:** Record fee payments.
*   **Procurement:** Manage purchase requests.
*   **Payroll:** View and process salaries.

### 5. Staff Management (`staff_preview.html`)
*   **CRUD:** Add, Edit, and active/suspend staff members.
*   **Roles:** Assign specific roles like "Head of School" or "Librarian" to control dashboard access.

### 6. Library (`librarian_dashboard_preview.html`)
*   **Overview:** Stats on borrowed books and overdue items.
*   **Catalog:** Manage the book inventory.

---

## Technical Notes
*   **Data Storage:** This preview uses `localStorage` to simulate a database. Data remains in your browser until you clear your cache.

