<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio Project Demo</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f2f6fa;
      margin: 2rem;
      line-height: 1.6;
      color: #333;
    }
    h1, h2 {
      color: #1a73e8;
    }
    a {
      color: #1a73e8;
      text-decoration: none;
    }
    section {
      margin-bottom: 2rem;
    }
    img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      border: 1px solid #ccc;
      margin-top: 0.5rem;
    }
    .code-block {
      background-color: #e8f0fe;
      padding: 1rem;
      border-left: 5px solid #1a73e8;
      font-family: monospace;
      overflow-x: auto;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <h1>Demo of My Portfolio Site (Template-Based)</h1>

  <section>
    <h2>1. Project Description</h2>
    <p>
      This portfolio site was developed using a responsive HTML and CSS template. I customized the template to reflect my personal style and include sections for projects, contact info, and resume highlights. The design adapts across devices, includes semantic HTML, and uses Flexbox and Grid for layout control. The site is also accessible and mobile-friendly.
    </p>
  </section>

  <section>
    <h2>2. Hosted Link</h2>
    <p>
      You can view the live project here:  
      <a href="https://your-hosted-link.com" target="_blank">https://your-hosted-link.com</a>
    </p>
  </section>

  <section>
    <h2>3. W3C Validator Compliance</h2>
    <p>
      My code was tested using the W3C HTML and CSS validator tools and passed successfully.
    </p>
    <img src="w3c-validation.png" alt="W3C Validator Screenshot - HTML and CSS Passed" />
  </section>

  <section>
    <h2>4. Responsive Design Proof</h2>
    <p>
      The site layout adjusts smoothly for multiple breakpoints: mobile, tablet, and large screens.
    </p>
    <img src="mobile-screenshot.png" alt="Mobile View" />
    <img src="tablet-screenshot.png" alt="Tablet View" />
    <img src="desktop-screenshot.png" alt="Desktop View" />
  </section>

  <section>
    <h2>5. CSS Styling Sample</h2>
    <p>Here’s a sample of the customized CSS used in the project:</p>
    <div class="code-block">
<pre>
body {
  font-family: 'Poppins', sans-serif;
  background-color: #ffffff;
  margin: 0;
  padding: 0;
  color: #444;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #1a73e8;
  padding: 1rem;
  color: white;
}

.grid-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 1rem;
  padding: 2rem;
}
</pre>
    </div>
  </section>

  <section>
    <h2>6. Final Notes</h2>
    <p>
      This project demonstrates my ability to work with professional templates and make meaningful design and layout changes. I ensured the code met accessibility, responsiveness, and validation standards. This site will serve as my live portfolio as I continue to grow in front-end development.
    </p>
  </section>
</body>
</html>
