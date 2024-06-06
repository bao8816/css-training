# Answers of the questions in section 1

(https://sharedoc.atlassian.net/wiki/spaces/~huy-nguyen/pages/3118989496/CSS+Training)

### Question 1: 
How to add external CSS in an HTML?
    
Answer:

    html
    <link rel="stylesheet" href="style.css">

### Question 2: 
What will happen if the system does not have the ```Roboto``` font?

    body {
    font-family: Roboto, Arial, sans-serif;
    }

**Answer:**
*The system will use the default font of the browser.*

### Question 4: 
Box model: What is the actual width and height of the ```.block``` element?

    .block {
    width: 100px;
    height: 32px;
    padding: 6px 12px;
    margin: 12px 16px;
    border: 2px solid #000;
    }

**Answer:**

* Width: 100 + 12x2 + 16x2 + 2x2 = 160px
* Height: 32 + 6x2 + 12x2 + 2x2 = 72px