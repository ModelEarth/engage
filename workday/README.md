# Workdak/Accenture Resume Template

## Application System Fixes for Workday

Primary Issue: The standard Harvard resume template (used by the majority of college grads) is not parsed effectively by the myworkdayjobs.com application system.

### QUICK FIX

Use a simple .txt file with minimal fields.
Example: [workday.txt](https://model.earth/cv/LorenHeyns/resume/LorenKevinHeyns-workday.txt)

[Additional tips for Workday Resume Parsing](https://www.reddit.com/r/recruitinghell/comments/1kt16ib/tips_for_workday_resume_parsing/) (reddit):


### OVERVIEW

Provide a link to sample templates that the Accenture/Workday site will properly parse.
Where the Workday site states supported formats, add a link on each to the template:
"Upload either DOC, DOCX, HTML, PDF, or TXT file types (5MB max) - click to view templates"

From the third tab ("My Experience") backup to the first tab and reattach.

IMPORTANT: Use the "Back" button in the website. (Not the browser back button)

To upload a fresh resume for parsing, you can delete the application for a specific job.

Avoid periods in organization names (no domains)

### PROGRAMMING

1. When a resume is deleted and reattached, allow the user to return to the parsing process.

2. And/or provide an external stand-alone page where the applicant can pre-test the parsing engine.

- Isolate the parsing engine in a GitHub repo where users can contribute improvements.

- Implement a test process that uses a large set of resumes to confirm processing works for all.

3. Provide a means for the applicant to delete their account so they can start with a clean resume upload.

### ADDITIONAL TO DOs

4. "How Did You Hear About Us?" needs to include: "From my Employer"

5. Allow the skills to be reordered by the applicant since the default parsing gives priority to less technical skills. 

6. In the Resume/CV section on the My Experience tab, include: "Updating your resume here will not impact the populated fields."