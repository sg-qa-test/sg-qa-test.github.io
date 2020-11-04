# QA Analyst Task

Welcome to the StarsGroup QA Analyst Task. The task is designed to be an interactive exercise, where communication and collaboration is key. It as important to us to see how you think, as much as it is to review how you appraise requirements.

It is supposed to be a fun, no pressure exercise. We encourage you to relax, be yourself, ask questions and think aloud.

---

## Expectations

The task is split into 3 parts, outlined below, but there are some common requirements for all 3 stages:

1. All the pages should follow our <a href="/style-guide.html" target="_blank">Global Style Guide</a>
2. Issues don't need to be explicitly writted down/recorded. Simply pointing them out will suffice.
3. Additional credit will be given for pointing out/flagging design issues/glitches/usability problems throughout the exercise.

---

### **Task 1** - <a href="/home" target="_blank">Home page</a>

A simple home page which will contain:

1. A Heading: "Welcome!"
2. A paragraph containing the text "Please register your account and you can download our mobile version here" with 2 links inside:
   1. `register` should link to the `registration.html` page.
   2. `here` should link to the `mobile.html` page.

---

### **Task 2** - <a href="/mobile" target="_blank">Mobile page</a>

This page contains information regarding our mobile applications, along with 2 icons at the bottom of the page.

The icons should:

1. Contain the relevant Store Icons
2. Link to the relevant app store pages, with links to be opened in a new tab.

---

### **Task 3** - <a href="/registration" target="_blank">Registration page</a>

This page allows users to regsiter with our system. The page should:

1. Contain 4 input fields: `username`, `email`, `password` & `confirm password`
2. Contain 2 Buttons: `Register` and `Cancel`
3. Clicking `Register` should validate the form, according to the [validation rules](/#validation-rules)
4. When clicking the `Register`, with a valid form, the form should be cleared and a green success message should appear on the top of the form.
5. When clicking the `Register`, with an invalid form, the first encountered field error will appear on the top of the form in red color.
6. Clicking `Cancel` should take you to the homepage.
7. The page should align with the <a href="/style-guide.html" target="_blank">Global Style Guide</a>, but also needs to match the below designs:

#### **Desktop**

1. The label should on the top of the inputs
2. Inputs should be 270px wide.
3. Action buttons should be horizontally aligned, on a the same row with 15px gap between them.
4. `Register` should be the primary button
5. `Cancel` button should be the secondary button
   <img src="images/desktop-design.png" />

#### **Mobile**

1. The label should on the top of the inputs
2. Inputs should be fill 100% of the remaining page width, after the global page spacing has been included.
3. Action buttons should be on seprate rows, with 15px gap between them.
4. `Register` should be the primary button
5. `Cancel` button should be the secondary button
   <img src="images/mobile-design.png" />

---

#### Validation Rules

1. Validation messages should appear under the relevant input in red color
2. Vaidation messages should only appear when the user changes the field value
3. Validation rules for each input are below:

Username:

- Required (must not be empty)
- Must start with letter</li>
- Should contains only letters or numbers
- Minimum length of 6 symbols

Email:

- Required (must not be empty)
- Must be a valid email address

Password:

- Required (must not be empty)
- Should contains only letters or numbers
- Minimum of 8 characters

Confirm Password:

- Required (must not be empty)
- Should be equal to password field
