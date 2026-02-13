# Day -1 HTML BASICS
# Introduction to HTML

### 🎯 **What I Learned Today**
### **What is HTML?** ###
### **HTML Document Structure** ###
### **Important HTML Tags : html,head,body,h1 – h6,p,a,img,div,span** ###

### **Create a Simple Profile Page.** ###

---

### 🧠 **Theory: Understanding HTML**
### 🔹1. **What is HTML?**

**HTML (HyperText Markup Language) is the standard language used to create web pages.**

**👉 It provides the structure of a webpage.**

**👉 It tells the browser how to display content.**

**Think of HTML as the skeleton of a website.**

**Example:**

<h1>Hello World</h1>




### **2. HTML Document Structure.** ###

-Every HTML page follows a basic structure:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
</head>
<body>

    <h1>Welcome</h1>
    <p>This is a simple HTML page.</p>

</body>
</html>

**🔍 Explanation** :

-<!DOCTYPE html> → Defines HTML5-
-<html> → Root element
-<head> → Contains meta information
-<body> → Contains visible content





### **3.🏷️ Important HTML Tags** ###

**1️⃣ <html>**
 -Root element of the webpage.

**2️⃣ <head>**
 -Contains title, meta, links, scripts.

**3️⃣ <body>**
 -Contains all visible content.

**4️⃣ <h1><h6>**
-Heading tags used for titles and subtitles.

**5️⃣ <p>**
-Used to write paragraph text in a webpage.

**6️⃣ <a>**
-Anchor tag used to create links.

**7️⃣ <img>**
 -Image Tag used to display images on a webpage.

**8️⃣ <div>**
 -Block-level container for grouping elements.

**9️⃣ <span>**
 -Inline container for styling small parts of text.

 ### **4.Create a Simple Profile Page**
 
 **✅ STEP 1: Create Project Folder**
 
 - 📁I Create a new folder on your my computer:
 - Day-1
 - 👉 This folder will contain my website files.

 **✅ STEP 2: Create Required Files**
 
 - Inside the folder, create:
 - Profile.html
 - img/Srujana.jpeg

   🔎 Why?
- index.html → Main webpage file
- profile.jpg → Your profile photo

  **✅ STEP 3: Write Basic HTML Structure**
  - Opened Profile.html and type:
<!DOCTYPE html>
<html>
<head>
    <title>Srujana's Profile</title>
</head>
<body>

</body>
</html>

🔎 Explanation
<!DOCTYPE html> → Tells browser this is HTML5
<html> → Root of webpage
<head> → Contains page title
<body> → Visible content goes here

**✅ STEP 4: Add Heading**
Inside <body>, adding:
<h1 align="center">My Profile</h1>

🔎 Explanation
<h1> → Main heading
align="center" → Centers the text

**✅ STEP 5: Add Profile Image (Circle + Center)**
Added below heading:
<center>
    <img src="img/Srujana.jpeg"
         width="150"
         height="150"
         style="border-radius:50%;">
</center>

🔎 Explanation

<img> → Displays image
src → Image file name
width & height → Size
border-radius:50% → Makes it circle
<center> → Centers image

**✅ STEP 6: Add About Section**
<h2>About Me</h2>
<p>
Hello! My name is Srujana. <br>
I am learning HTML and Web Development.<br>
I am passionate about building websites.
</p>

🔎 Explanation
<h2> → Subheading
<p> → Paragraph text

**✅ STEP 7: Add Skills Section**
<h2>My Skills</h2>
<p>HTML</p>
<p>CSS</p>
<p>JavaScript</p>

**✅ STEP 8: Add Contact Section**
  <h2>Contact Me</h2>
  <p>Email: srujanach2005@gmail.com</p>
  <p>
  GitHub:
  <a href="https://github.com/srujanach2005-star" target="_blank">
   Visit My GitHub
  </a>
  </p>

  🔎 Explanation
<a> → Creates link
href → Website address

**✅ FINAL COMPLETE CODE**
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Srujana's Profile</title>
</head>
<body align="center">
    <h1>My Profile</h1>

    <!-- Profile Photo -->
     <img src="img/SRUJANA.jpeg" 
     alt="My Photo" 
     width="150" 
     height="150"
     style="border-radius:50%;">

   

    <!-- About Section -->
    <div>
        <h2>About Me</h2>
         <p >
            Hello! My name is Srujana. <br>
            I am learning HTML and Web Development.<br>
            I am passionate about building websites.
        </p>
    </div>

    <!-- Skills Section -->
    <div>
        <h2>My Skills</h2>
        <p>HTML</p>
        <p>CSS</p>
        <p>JavaScript</p>
    </div>

    <!-- Contact Section -->
    <div>
        <h2>Contact Me</h2>
        <p>Email: srujanach2005@gmail.com</p>
        <p>
            GitHub:
            <a href="https://github.com/srujanach2005-star" target="_blank">
                Visit My GitHub
            </a>
        </p>
    </div>
    
</body>
</html>

**OUT PUT**
![Profile Image](Srujana.jpeg)




    




   
   

   

 


