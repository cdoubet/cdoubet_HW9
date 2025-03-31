# Business Analytics Student Survey

## Project Description
<p>The Business Analytics Student Survey is a web-based form designed to collect information from Business Analytics and Information Systems (BAIS) students about their academic progress, including their year level and completed core courses. The form implements modern web design principles to ensure usability, accessibility, and data integrity.</p>
 
## Form Best Practices
<p>The survey form adheres to several best practices for web forms to enhance user experience and data collection:</p>

<p>The form utilizes Bootstrap's grid system and component styling to create a visually appealing layout with consistent spacing and alignment. Form elements are organized in logical groups with descriptive labels, making it easy for users to understand what information is being requested. Required fields are clearly marked with asterisks, and the page numbering (page 2 of 2) helps users track their progress through the multi-page survey.</p>

<p>Client-side validation is implemented using both HTML5 attributes and JavaScript to ensure that users complete all required fields before submission. The form provides immediate feedback when validation errors occur, highlighting problematic fields with Bootstrap's validation classes. Error messages are descriptive and positioned directly beneath the relevant form controls, helping users understand what corrections are needed.</p>

<p>The form is built with Bootstrap's responsive framework, ensuring it displays properly across different device sizes and screen resolutions. Input elements like radio buttons and checkboxes are sized appropriately to be easily clickable on touch screens, and the submission button is prominently displayed with both text and an icon to improve recognition.</p>

## User Adcessibility
<p>The form is designed with accessibility as a core consideration, implementing several features to ensure all users can complete the survey regardless of ability:</p>
        
<p>The form uses semantic HTML elements making it navigable via screen readers and keyboard controls. All form elements have appropriate ARIA attributes where needed, and color is not used as the sole indicator of meaning (required fields use both color and an asterisk symbol). The form validation provides clear error messages that are accessible to screen reader users, and the layout maintains sufficient color contrast ratios for text readability. Additionally, the submission button uses both text and an icon from Font Awesome, providing multiple ways to understand its purpose, and Bootstrap's focus states ensure that keyboard users can clearly see which element is currently active.</p>
