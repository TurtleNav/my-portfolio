## My Portfolio
by Luc Tourangeau

-----

In this assignment, I created a portfolio site containing exclusively html
and css to host and display my programming skills. While not a complete
project, I can add to the project as I develop future projects.

My `index.html` file was structured as follows:
```html
<body>
<!-- Main header and nav bar -->
  <header>
    <h1>...</h1>
    <nav>
      <ul>
        <!-- List of internal links to my showcased projects -->
        <li><a href="#project-1">Project 1</a></li>
        ...
      </ul>
    </nav>
  </header>
  <!-- Main content -->
  <main>
  <!-- About me section will contain a profile pic, some text, links
       to previous jobs, etc. -->
    <article id="about-me">
      <!-- Profile Pic -->
      <img ... >
      <div id="about-me-content">
        <h2>...</h2>
        <!-- Text and other stuff here -->
      </div>
    </article>

    <article id="project-1" class="project-class">
      <h2>...</h2>
      <!-- Text and image here -->
    </article>

    <!-- Duplicate the above for other showcased projects -->
    ...
  </main>
  <footer>
    <h3>Contact Me:</h3>
    <!-- Contact info below -->
    <ul>
      <li>Email ...</li>
      <li>Github ...</li>
      ...
    </ul>
  </footer>
</body>
```




