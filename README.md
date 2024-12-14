# React Calendar Application

## **Summary**
The **React Calendar Application** is an interactive web-based calendar that allows users to:
- View events in different formats (monthly, weekly, daily).
- Add new events with titles, descriptions, and time.
- Edit existing events.
- Delete events after confirmation.
- Save and retrieve events using local storage.
- Highlight Sundays and format event dates for better visibility.

This project is built using **React.js** with the help of the `@fullcalendar/react` library for calendar functionality.

---

## **Features**
- **Add Events:** Create new events by selecting a date and filling in details (title, description, time).
- **Edit Events:** Modify event details directly by clicking on an event.
- **Delete Events:** Easily remove unwanted events with a confirmation prompt.
- **Highlight Sundays:** Dates on Sundays are styled distinctly.
- **Persistent Data:** Events are saved locally, ensuring they remain after refreshing the page.
- **Responsive Design:** Compatible with both desktop and mobile screens.

---

## **Technologies Used**
- **React.js**
- **FullCalendar** (`@fullcalendar/react`, `@fullcalendar/core`, and plugins)
- **CSS/ TailwindCSS** for styling
- **Local Storage** for event persistence

---

## **Getting Started**

### **Prerequisites**
Make sure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn package manager

---

### **Running Locally**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Nihar05032/Dynamic-EventCalendar.git
   
2. **Install dependencies: Ensure all required packages are installed:**
   ```bash
   npm install

### **Dependencies Installation**
To set up the project, you'll need to install the required dependencies. Follow the steps below:

1. Install FullCalendar Libraries
Install FullCalendar and its required plugins:

   ```bash
   npm install @fullcalendar/core @fullcalendar/interaction @fullcalendar/daygrid  
   npm install @fullcalendar/react @fullcalendar/timegrid
@fullcalendar/core: Provides the core functionality of FullCalendar.
@fullcalendar/interaction: Enables user interactions like date selection and drag-and-drop.
@fullcalendar/daygrid: Adds month (grid) views for the calendar.
@fullcalendar/react: React wrapper for integrating FullCalendar into React apps.
@fullcalendar/timegrid: Provides week and day views for time-based scheduling.

2. Initialize Shadcn for UI Components
Shadcn is used for building and managing UI components. Run the following command to set it up in the project:

   ```bash
   npx shadcn@latest init
   During Initialization:

Select the default settings when prompted.
Choose a color scheme (e.g., neutral or another theme).
Allow overwriting the TailwindCSS configuration (select yes).

3. Add Shadcn Dialog Component
Add the Dialog component to your project for creating modal popups:

   ```bash
   npx shadcn@latest add dialog
This will generate the necessary Dialog component files, which will be located in the components/ui/dialog folder. These files are used for modals like the "Add Event" and "Edit Event" forms.

4. Restart the Development Server
After installing the dependencies and components, restart the development server:

   ```bash
   npm run dev
