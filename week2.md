# BSCCS2003: Week-2 HTML Lab Assignment

In this assignment, you have to create a website consisting of five HTML pages. Separate sets of instructions have been given for common features and page-specific features. First, we list below some general instructions which must be followed while submitting your solution.

## General instructions

- Submit a single `.zip` file containing all your submission files. (All the HTML files must reside in the root directory of your submission zip file.)
- The name of the zip file should be `<rollnumber>.zip`. (E.g.: `21f1000000.zip`)
- The pages should be HTML5 compliant, e.g., the file should begin with the declaration `<!DOCTYPE html>`.
- Use of any HTML code generator may lead to rejection of your submission.
- You are allowed to use only those tags mentioned in the question (in the body of HTML page) and only as many times as specified (using any other tags than the mentioned ones will lead to deduction in marks).
- No CSS should be used in this assignment.

## Common instructions

- Each page must have three sections generated using `div` tags:
  1. Header section with links to other pages  
  2. Main section with the main content  
  3. Footer section with your name, batch, copyright, year  

- For each webpage, you must create one HTML page. The name of the HTML file for each page must be as given in Table 1.
- The content of headers and footers for each of the webpage in the website is also listed in Table 1.

### Table 1: Common content specifications

| Page      | Home        | Academics    | Personal     | Contact      | Resume       |
|-----------|-------------|-------------|-------------|-------------|-------------|
| HTML file name | `index.html` | `academics.html` | `personal.html` | `contact.html` | `resume.html` |
| Headers – Links | Academics, Personal, Contact, Resume | Home, Personal, Contact, Resume | Home, Academics, Contact, Resume | Home, Academics, Personal, Resume | Home, Academics, Personal, Contact |
| Footer information | Your name, batch, copyright and year (you can decide the format of this content). |

- There are restrictions on the number of each type of tag that can be used in the body of each HTML page. Table 2 lists the exact count of each tag expected in the respective pages.

[http://www.onlinedegree.iitm.ac.in](http://www.onlinedegree.iitm.ac.in/)

## Table 2: Tag frequency for each page

| Tag      | Home | Academics | Personal | Contact | Resume |
|----------|------|-----------|----------|---------|--------|
| `div`    | 3    | 3         | 3        | 3       | 3      |
| `h5`     | 1    | 1         | 1        | 1       | 1      |
| `h1`     | 1    | 1         | 1        | 1       | 1      |
| `a`      | 4    | 4         | 5        | 4       | 5      |
| `p`      | 3    | 0         | 0        | 0       | 0      |
| `table`  | 0    | 1         | 0        | 0       | 0      |
| `td`     | 0    | 12        | 0        | 0       | 0      |
| `tr`     | 0    | 7         | 0        | 0       | 0      |
| `th`     | 0    | 2         | 0        | 0       | 0      |
| `br`     | 0    | 0         | 2        | 5       | 0      |
| `img`    | 0    | 0         | 2        | 0       | 0      |
| `address`| 0    | 0         | 0        | 1       | 0      |

## Page-specific instructions

1. **Home Page**  
   This is the first page to be accessed by a user of your website.  
   The main section should display your name, your onlinedegree roll number and an introduction about yourself (in a maximum of 50 words) under the heading **“Student data”**. The display format is as shown in Figure 1.

2. **Academics Page**  
   On clicking the academics link, the user should be directed to the academics page.  
   The main section of this page should display your marks in tabular format under the heading **“Mark sheet”** as shown in Figure 2. The same table data should be used in your webpage (you could change subject names and corresponding marks but the number of records and table headers should remain same).

3. **Personal Page**  
   On clicking the personal link, the user should be directed to `personal.html`.  
   The main section must have two images and an external link as shown in Figure 3. The images to be displayed can be downloaded from: **Images to download**. Each image should be of `width = 250` and `height = 250`.  
   The external link should be directed to the onlinedegree webpage (`http://www.onlinedegree.iitm.ac.in`) with the text:  
   **“Click here to view the Online Degree webpage”**.

4. **Contact Page**  
   On clicking the contact link, a new page with address and e-mail id should be displayed using the `address` tag under a heading **“Contact Us”** in the main section as shown in Figure 4. (Note that you need not enter your real address or e-mail id).

5. **Resume Page**  
   On clicking the resume link, a new page should open whose main section should contain a link **“download resume”** allowing the user to view your CV. You can refer to the image shown in Figure 5.

## Figures (descriptions from PDF)

- Figure 1: Home page  
- Figure 2: Academics page  
- Figure 3: Personal page  
- Figure 4: Contact page  
- Figure 5: Resume page  
- Figure 6: Figures to be used in personal page  
  - (a) Image 1  
  - (b) Image 2
