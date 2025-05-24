💼 **Jobby App – Job Search Platform (React JS)**
**Description:** Developed a responsive job search web application with secure login, dynamic job listings, filtering options, and detailed job views using React.js, REST APIs, and JWT-based authentication.

### Key Features:

🔐 **Authentication & Route Protection:**

* Implemented secure login using JWT token authentication.
* Protected routes (Home, Jobs, Job Details) accessible only to authenticated users.
* Redirected authenticated users away from the Login route.

🏠 **Home Page:**

* Provided navigation to the Jobs page through a "Find Jobs" button.
* Restricted access for unauthenticated users.

📋 **Jobs Listing Page:**

* Fetched profile and jobs data via API with query parameters: employment type, salary range, and search term.
* Displayed loaders while data fetched and views for success, failure, or empty responses.
* Enabled filter combinations and implemented Retry feature on failed API requests.

🔍 **Search and Filter Functionality:**

* Enabled real-time job filtering using:

  * Search input (triggered by search icon click)
  * Employment type checkboxes (multi-select)
  * Salary range radio buttons (single-select)
* Automatically updated job list based on selected filters.

📄 **Job Details Page:**

* Fetched specific job details and similar jobs using job ID and JWT token.
* Displayed comprehensive job description, skills, company info, and life at company.
* Provided Retry feature and external company website link via "Visit" button.
* Navigated unauthenticated users to Login route.

🚫 **Not Found Page:**

* Displayed a 404 Not Found view for invalid URL paths.

🧭 **Header Navigation:**

* Navigated to Home/Jobs routes via logo and links.
* Implemented Logout button functionality to clear session and redirect to Login.

### 🌐 Tech Stack Used:

React JS, React Router, Context API, REST API, JWT Authentication, CSS
