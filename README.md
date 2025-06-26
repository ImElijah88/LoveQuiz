# Our Shared Journey: A Love & Vision Questionnaire

This is a personal, interactive HTML questionnaire designed to help couples explore their perspectives on important aspects of a long-term relationship. It features pre-filled answers for one partner (Elijah), allowing the other (your girlfriend) to provide her responses interactively. The document can be filled out digitally, and then saved as a PDF or sent via email.

## Features

* **Interactive Design:** Easy-to-use text areas that expand automatically as you type.
* **Pre-filled Answers:** Initial answers provided by Elijah to guide reflection. These disappear when the user types and reappear if the field is left blank.
* **Collapsible Sections:** "A Gentle Guide" and "Legal Terms & Conditions" sections can be expanded/collapsed for better readability, using a custom plus/minus icon.
* **Dynamic Acknowledgment:** A signature box appears only after the user agrees to the terms and conditions.
* **Email Integration:** Allows the user to compile their answers, review them in a modal, copy them to the clipboard, and then automatically open their email client with responses pre-filled to `iliemagureanu2023@gmail.com`.
* **PDF Download:** Easily save the completed questionnaire as a PDF via the browser's print function, accessible via a dedicated "Download as PDF" button.
* **Cute Animation:** A subtle pulsing heart animation is present in the design for a romantic touch.
* **Romantic Design:** Uses a romantic color palette and "Dancing Script" and "Comic Sans MS" fonts for a heartfelt, personalized feel.

## How to Use

### Offline (on your computer/device)

1.  **Save the file:** Ensure you have the `lovequiz.html` file saved on your computer or device.
2.  **Open in Browser:** Simply double-click the `lovequiz.html` file. It will open in your default web browser (Chrome, Firefox, Safari, Edge, etc.).
3.  **Fill out:**
    * Read "A Gentle Guide" for instructions and Elijah's pre-filled answers.
    * Click on each question's text area to see the pre-filled answer. Type your own response directly into the box.
    * Review the "Final Agreement & Acknowledgment" section. Expand "Click to review Terms & Conditions" to read the legal terms.
    * Check the "I have read, understood, and agree..." box.
    * Type your full name in the provided signature box.
    * Enter your email address in the designated field within the guide section.
4.  **Save/Send:**
    * **Download as PDF:** Click the "Download as PDF" button. This will open your browser's print dialog, where you can select "Save as PDF" (or similar) as the destination and save the file. You can then **send this PDF via email** by attaching the saved file to a new email and sending it to `iliemagureanu2023@gmail.com`.
    * **Send via Email (as text):** First, make sure you've filled in your email address. After completing the questionnaire, click "I've Completed the Questionnaire" at the bottom of the page. A review box with all your answers will appear. Copy the text, and then click "Send Email to Elijah" to attempt to open your email client. A confirmation will appear before sending.
    * **Manual Email (if auto-open fails):** If your email client doesn't open automatically, or if you're not logged in with the email address you entered, you can still send your text answers. Just copy all the text from the review box, then manually open your preferred email service (like Gmail, Outlook, etc.), create a new email, and paste the answers into the body. Please send it to: `iliemagureanu2023@gmail.com`.

### Online (Hosting the File)

To share the questionnaire online via a URL, you'll need to host the `lovequiz.html` file on a web server. Here are a couple of popular free options:

#### Option 1: GitHub Pages

1.  **Create a GitHub Account:** If you don't have one, sign up at [github.com](https://github.com/).
2.  **Create a New Repository:** Log in, click the '+' icon, and select "New repository." Give it a public name (e.g., `our-love-quiz`).
3.  **Upload Your File:** On your new repository page, click "Add file" -> "Upload files," then drag and drop `lovequiz.html`. Commit the changes.
4.  **Enable GitHub Pages:** Go to `Settings` -> `Pages`. Under "Build and deployment," choose "Deploy from a branch." Select `main` (or `master`) as the source and `/ (root)` for the folder. Click "Save."
5.  **Access Your Site:** After a few minutes, your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME/lovequiz.html`. Share this URL!

#### Option 2: Netlify Drop

1.  **Go to Netlify Drop:** Visit [app.netlify.com/drop](https://app.netlify.com/drop).
2.  **Drag and Drop:** Simply drag your `lovequiz.html` file onto the page.
3.  **Site Deployed:** Netlify will instantly deploy your site and give you a temporary URL (e.g., `https://random-name-12345.netlify.app`).
4.  **Rename (Optional):** You can sign up for a free Netlify account and link the deployed site to your account to get a more memorable custom subdomain (e.g., `our-journey-of-love.netlify.app`).
5.  **Share Your URL:** Share the generated URL with your girlfriend.

## Development Notes

* **Dependencies:** The file is self-contained HTML with inline CSS (Tailwind CSS CDN) and JavaScript. No external build tools are required.
* **Customization:** The pre-filled answers are stored in the `prefilledAnswers` JavaScript object at the bottom of the HTML file. You can easily modify these answers by editing the JavaScript directly.
* **Print Styles:** Specific `@media print` CSS rules ensure a clean, readable output when saving to PDF. Animations and certain interactive elements are hidden for print.
