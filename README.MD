# 📱 FixPoint – Hostel Complaint Management App

FixPoint is a SwiftUI-based mobile application designed to make hostel complaint management simple, fast, and organized.  
Students can submit complaints, assign priority levels, and track their status — all within a clean and modern interface.

---

##  Features

- 📝 Submit hostel complaints with title & description  
- 🎚️ Choose priority levels (Low, Medium, High)  
- 📋 View all submitted complaints in a clear list  
- 📄 Detailed view for each complaint  
- 🔄 Track complaint progress (Pending / In Progress / Resolved)  
- 🎨 Modern SwiftUI interface  
- ⚡ Smooth and intuitive user experience  

---

## 📂 App Structure (Page-by-Page Explanation)

### 🏠 1. Home Page (Dashboard)

**Displays:**
- Welcome message  
- Overview of complaints  
- Button to add a new complaint  

**Purpose:**  
Acts as the landing page and helps users quickly navigate to important sections.

---

### ➕ 2. Add Complaint Page

**Includes fields for:**
- Complaint Title  
- Description  
- Priority Level  
  - 🔵 Low  
  - 🟠 Medium  
  - 🔴 High  

**Purpose:**  
Allows students to create a new complaint with a clear priority indicator for hostel authorities.

---

### 📋 3. Complaints List Page

**Shows a list of all complaints with:**
- Title  
- Priority badge  
- Status badge  

**Purpose:**  
This is the main list of all registered complaints. Users tap a complaint to view full details.

---

### 📄 4. Complaint Details Page

**Displays full information:**
- Title  
- Detailed description  
- Priority level with color  
- Status (Pending / In Progress / Resolved)  
- Date of submission  

**Purpose:**  
Gives complete insight into each complaint for both students and authorities.

---

### ⚙️ 5. Settings / Profile Page (If included)

**May include:**
- User profile  
- Logout option  
- Theme toggle  

---

## 🧠 Tech Stack

- **SwiftUI** — UI development  
- **MVVM Architecture** — Clean separation of UI and logic  
- **AppStorage / Local Storage** — For storing complaint data  
- (Optional) **Firebase** — If used for authentication or backend  

---

## 🏗️ How the App Works

1. User opens the app  
2. Adds a new complaint with priority  
3. Complaint is saved and displayed in the list  
4. User can view complaint details  
5. Status updates as authorities review and resolve complaints  

---

## 📦 Future Enhancements

- 🔔 Push notifications for status updates  
- 📸 Add images to complaints  
- 🧑‍💼 Admin/warden panel  
- 🔗 Backend integration (Firebase/Supabase)  
- 📊 Analytics dashboard for hostel authorities  

---

Just tell me, and I will generate a pro-level README for GitHub.
