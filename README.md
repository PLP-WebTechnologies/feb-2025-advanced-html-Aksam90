# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PLP Learning Academy</title>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>PLP Learning Academy</h1>
    <p>This page demonstrates various PLP Learning Academy.</p>
  </header>

  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>Types of programming language</h2>
    <ol type="I">
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Python</li>
      <li>SQL</li>
    </ol>
  </section>

  <!-- External Image -->
  <section>
    <h2>External Image</h2>
    <img 
      src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" 
      alt="Nature Landscape" 
      width="550"
    />
  </section>

  <!-- Registration Form -->
  <section>
    <h2>Registration Form</h2>
    <form>
      <!-- Name Field -->
      <label for="name">Full Name:</label><br>
      <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

      <!-- Email Field -->
      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email" placeholder="example@domain.com" required><br><br>

      <!-- Password Field -->
      <label for="password">Password:</label><br>
      <input type="password" id="password" name="password" placeholder="Minimum 6 characters" required minlength="6"><br><br>

      <!-- Date Field -->
      <label for="dob">Date of Birth:</label><br>
      <input type="date" id="dob" name="dob" required><br><br>

      <!-- Dropdown -->
      <label for="country">Country:</label><br>
      <select id="country" name="country" required>
        <option value="">Select a country</option>
        <option value="ghana">Ghana</option>
        <option value="nigeria">Nigeria</option>
        <option value="kenya">Kenya</option>
        <option value="south_africa">South Africa</option>
      </select><br><br>

      <!-- Radio Buttons -->
      <p>Gender:</p>
      <input type="radio" id="male" name="gender" value="male" required>
      <label for="male">Male</label><br>
      <input type="radio" id="female" name="gender" value="female">
      <label for="female">Female</label><br>
      <input type="radio" id="other" name="gender" value="other">
      <label for="other">Other</label><br><br>

      <!-- Checkboxes -->
      <p>Select your interests:</p>
      <input type="checkbox" id="music" name="interests" value="music">
      <label for="music">Music</label><br>
      <input type="checkbox" id="sports" name="interests" value="sports">
      <label for="sports">Sports</label><br>
      <input type="checkbox" id="reading" name="interests" value="reading">
      <label for="reading">Reading</label><br><br>

      <!-- Submit Button -->
      <button type="submit">Register</button>
    </form>
  </section>

  <!-- Multimedia Section -->
  <section>
    <h2>Multimedia</h2>

    <!-- Audio -->
    <h3>Sample Audio</h3>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>

    <!-- Video -->
    <h3>Sample Video</h3>
    <video width="500" controls>
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
      Your browser does not support the video element.
    </video>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 PLP Learning Academy. All rights reserved.</p>
  </footer>

</body>
</html>
