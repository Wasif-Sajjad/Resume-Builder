resume builder with basic html css
Objective: Develop a web-based resume builder that allows users to input their personal
information, education, work experience, and skills into a form, and then generate a
downloadable PDF version of a resume from this data.
Key Features:
Home Page with a "Create Resume" Button:
● Implement a welcoming home page with minimal design, featuring a prominent "Create
Resume" button.
● Utilize state management to handle user interactions and navigate to the resume form
page upon clicking the button.
Resume Form Page:
● Design a multi-section form that captures various details necessary for a resume, such
as:
1. Personal Information (Name, Email, Phone Number)
2. Education (Degree, Institution, Year)
3. Work Experience (Company, Role, Responsibilities, Duration)
4. Skills (List of skills)
● Implement form validation to ensure that all required fields are filled out before
submission.
● Use local storage to save the form data persistently, so users can return to their work if
the browser refreshes.
● On submission, navigate to a preview page displaying the formatted resume information.
● Incorporate state management to facilitate the flow of data across components/pages.
Resume Preview Page with Download PDF Button:
● Display all submitted information in a structured and styled resume format.
● Include a "Download PDF" button that generates a PDF file of the resume, utilizing a
library such as jsPDF.
● Ensure the generated PDF mirrors the on-screen preview in terms of layout and content.
Technical Requirements:
● Frontend Framework: Use React (or a similar framework) for building the user interface,
emphasizing the use of hooks for state management.

● State Management: Employ context or a state management library (e.g., Redux,
Zustand) to manage the application's state, particularly for handling form data and
navigation.
● Local Storage: Utilize the browser's local storage to save and retrieve the user's form
data, ensuring data persistence across sessions.
● PDF Generation: Integrate a JavaScript library like jsPDF to convert the resume preview
into a downloadable PDF file.
● Styling and Layout: Apply CSS or a CSS framework (e.g., Bootstrap, Tailwind) for styling,
ensuring the application is responsive and visually appealing.
Judging Criteria:
● Functionality: Does the application perform all the specified features correctly and
efficiently?
● Code Quality: Is the code clean, well-organized, and following best practices for the
chosen stack?
● User Experience: Is the application easy to use, with intuitive navigation and a pleasing
design?
● Innovation: Are there any additional features or creative elements that enhance the
overall functionality or user experience?
Submission Guidelines:
Participants should submit their code via a public GitHub repository, including a README file
with an overview of the project, setup instructions, and any notable features. A live demo hosted
on platforms like Netlify, Vercel, or GitHub Pages should also be provided.
