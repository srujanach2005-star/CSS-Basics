# Day-3 Tables & Accessibility
# 📘 1️⃣ TABLES – THEORY

# 🔹 What is a Table?

-A table is used to display structured data in rows and columns.

# Example:

-Student list

-Course details

-Marks sheet

-Employee records

# 🔹 Important Table Tags
| Tag       | Meaning       |
| --------- | ------------- |
| `<table>` | Creates table |
| `<tr>`    | Table row     |
| `<th>`    | Table header  |
| `<td>`    | Table data    |

# 🔹 Basic Structure
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>

    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>

# ♿ 2️⃣ Accessibility – THEORY
-Accessibility means:

# 👉 Making websites usable for:

-Screen readers

-Visually impaired users

-Keyboard users

# 🔹 Important Accessibility Features
# ✅ 1. alt Attribute (For Images)

Used to describe image.
<img src="logo.png" alt="SSB Training Logo">

# Why important?

-Screen readers read this text

-Shows if image fails to load

# ✅ 2. <label> Tag (For Forms)

Connects label with input.
<label for="name">Full Name:</label>
<input type="text" id="name">

# Why important?

-Improves usability

-Better accessibility

-Clicking label selects input

# 🚀 3️⃣ Create Sample Table Layout (With Accessibility)

<!DOCTYPE html>
<html>
<head>
    <title>Day 3 - Tables</title>
</head>
<body>

<header align="center">
    <h1>Student Course Table</h1>
</header>

<main>

    <section>

        <h2 align="center">Course Details</h2>

        <center>   <!-- Center Starts -->

        <table border="1" cellpadding="10">

            <tr>
                <th>Student Name</th>
                <th>Course</th>
                <th>Duration</th>
                <th>Status</th>
            </tr>

            <tr>
                <td>Srujana</td>
                <td>Java Full Stack</td>
                <td>6 Months</td>
                <td>Active</td>
            </tr>

            <tr>
                <td>Sreedhar</td>
                <td>Python with AI & ML</td>
                <td>5 Months</td>
                <td>Completed</td>
            </tr>

            <tr>
                <td>Sindhu</td>
                <td>React JS</td>
                <td>3 Months</td>
                <td>Active</td>
            </tr>

        </table>

        </center>  <!-- Center Ends -->

    </section>

</main>

<footer align="center">
    <p>© 2026 SSB Training</p>
</footer>



</body>
</html>

# OUT PUT

![Day-3](img/day-3-output.png)
