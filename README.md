# Sales Management Portal

This project is a **Sales Management Portal** that enables users to manage clients, sales, proposals, and various administrative operations. The portal has different sections for Admin, Managers, and Sales personnel, each with specific functionalities. The project is developed using ASP.NET with C# for server-side operations and uses a combination of HTML, CSS, and JavaScript for the frontend.

## Folder Structure

```plaintext
C:\USERS\AQWSA\DESKTOP\SALES MANAGEMENT PORTAL
├── Comments.aspx                # Page for managing comments
├── Comments.aspx.cs             # Backend logic for Comments.aspx
├── CreateClient.aspx            # Page for creating a new client
├── CreateClient.aspx.cs         # Backend logic for CreateClient.aspx
├── CreateManager.aspx           # Page for creating a new manager
├── CreateManager.aspx.cs        # Backend logic for CreateManager.aspx
├── CreateSales.aspx             # Page for creating new sales personnel
├── CreateSales.aspx.cs          # Backend logic for CreateSales.aspx
├── Home.aspx                    # Landing page after login
├── Home.aspx.cs                 # Backend logic for Home.aspx
├── Login.aspx                   # Login page for users
├── Login.aspx.cs                # Backend logic for Login.aspx
├── MainMaster.master            # Main master page for layout
├── MainMaster.master.cs         # Backend logic for MainMaster.master
├── OppType.aspx                 # Page for managing opportunity types
├── OppType.aspx.cs              # Backend logic for OppType.aspx
├── Projects.aspx                # Page for managing projects
├── Projects.aspx.cs             # Backend logic for Projects.aspx
├── Proposals.aspx               # Page for managing proposals
├── Proposals.aspx.cs            # Backend logic for Proposals.aspx
├── web.config                   # Configuration file for the web application
├── _Common Login.png            # Common login image
│
├── AdminLogin                   # Images related to Admin UI
│   ├── 2AdminHome.png
│   ├── 3ManagerManagement.png
│
├── Content                      # CSS stylesheets for UI design
│   ├── bootstrap.css
│   ├── bootstrap.min.css
│   ├── landing-page.css
│   ├── signin.css
│   ├── Site.css
│
├── Images                       # Project image resources
│   ├── intro-bg.jpg
│   ├── lib.jpeg
│
├── ManagerLogin                 # Images related to Manager UI
│   ├── 4ManagerHome.png
│   ├── 5SalesManagement.png
│   ├── 6SalesAnnouncement.png
│
├── SalesLogin                   # Images related to Sales UI
│   ├── 7SalesHome.png
│   ├── 8OpportunityType.png
│   ├── 9OpportunityManagement.png
│   ├── 10ProposalsManagement.png
│   ├── Announcement.png
│   ├── Project.png
│
└── Scripts                      # JavaScript and validation scripts
    ├── ai.0.15.0-build58334.js
    ├── ai.0.15.0-build58334.min.js
    ├── bookvalidation.js
    ├── bootstrap.js
    ├── bootstrap.min.js
    ├── dashboard-validation.js
    ├── jquery-1.10.2.intellisense.js
    ├── jquery-1.10.2.js
    ├── jquery-1.10.2.min.js
    ├── jquery-1.10.2.min.map
    ├── jquery-1.11.2.js
    ├── jquery.validate-vsdoc.js
    ├── jquery.validate.js
    ├── jquery.validate.min.js
    ├── jquery.validate.unobtrusive.js
    ├── jquery.validate.unobtrusive.min.js
    ├── modernizr-2.6.2.js
    ├── respond.js
    ├── respond.min.js
    └── _references.js
```

Key Features
+ Login: Separate login pages for Admin, Managers, and Sales personnel.
+ Client Management: Allows admins and managers to create and manage clients.
+ Project Management: Supports project management, including proposal submissions and opportunity tracking.
+ Role-Based Access: Different functionality for Admin, Managers, and Sales users.
+ Validation: Client-side validation using JavaScript and jQuery.
+ Responsive Design: CSS files ensure the application is mobile-friendly.

## How to Run

### Prerequisites

Before you can run this project, make sure you have the following installed:

- **Visual Studio** (2019 or later)
- **.NET Framework 4.x**
- **IIS Express** (comes with Visual Studio)

### Steps to Run Locally

1. **Clone the Repository**  
   Open a terminal and clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/aluriDevAnanth/SalesManagementPortal.git
   ```

   ## How to Run

    ### Open the Project in Visual Studio
    
    1. Once the repository is cloned, launch **Visual Studio**.
    2. Navigate to the cloned project folder and open the solution file.
    
    ### Build the Project
    
    1. In **Visual Studio**, use the **Build** option in the top menu, or press `Ctrl+Shift+B` to compile the solution.
    2. Ensure there are no build errors before proceeding to run the project.
    
    ### Run the Project
    
    1. Select **IIS Express** from the dropdown menu at the top of **Visual Studio**.
    2. Press `F5` to run the project in debug mode, or use the **Start Debugging** option from the **Debug** menu.
    
    ### Access the Application
    
    Once the application is running, open your web browser and use the following routes:
    
    - Navigate to `/Login.aspx` to access the login page.
    - Navigate to `/Home.aspx` to view the dashboard after logging in.
    
    ---
    
    ## Technologies Used
    
    - **ASP.NET Web Forms**: Used for building the UI and managing server-side logic.
    - **C#**: Backend programming language to handle the business logic and functionality.
    - **JavaScript/jQuery**: For client-side validation, form handling, and other interactive features on the frontend.
    - **Bootstrap**: A CSS framework for creating responsive and mobile-friendly web design.
    - **HTML/CSS**: Core structure and styling of the web application pages.

