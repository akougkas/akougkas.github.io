# Welcome to my Portfolio! 👋

This repository hosts the code for my personal portfolio website, deployed at [https://akougkas.github.io/](https://akougkas.github.io/). 

It showcases my projects, skills, and experiences. Feel free to explore and learn more about my work.

## Contact

You can reach me at [a.kougkas@gmail.com](mailto:a.kougkas@gmail.com).

---

## Installation and Deployment

This project leverages Google Project IDX and a Nix environment for development and deployment. Here's a quick guide:

**1. Project IDX Setup**

* Refer to the official Project IDX guide for detailed instructions: [https://developers.google.com/idx/guides/introduction](https://developers.google.com/idx/guides/introduction)
* Ensure you have a Project IDX workspace set up for this repository.

**2. Nix Environment**

* **(If applicable)** If you're using a Nix environment, activate it within your Project IDX workspace.

**3. Installation**

* Open a terminal in your Project IDX workspace.
* Run the following command to install dependencies:

<div class="code-block">
<pre><code>bundle update && bundle install</code> <button class="copy-button" onclick="copyToClipboard('bundle update && bundle install')">Copy</button></pre>
</div><br>


**4. Deployment**

* Execute the deployment command:

<div class="code-block">
<pre><code>bundle exec jekyll build && bundle exec jekyll serve</code> <button class="copy-button" onclick="copyToClipboard('bundle exec jekyll build && bundle exec jekyll serve')">Copy</button></pre>
</div><br>

* **(If applicable)**  For automatic deployment to GitHub Pages, follow the steps outlined in the original repository's `INSTALL.md` file.

** Notes:**

* Remember to replace `[your-email@example.com]` with your actual email address.
---

Feel free to reach out if you have any questions or feedback!

<script>
function copyToClipboard(text) {
    navigator.clipboard.writeText(text).then(function() {
        alert('Copied to clipboard');
    }, function(err) {
        console.error('Async: Could not copy text: ', err);
    });
}
</script>

<style>
.code-block {
    position: relative;
    display: flex;
    align-items: center;
}

.code-block pre {
    margin: 0;
    padding-right: 50px; /* Adjust as needed to ensure space for the button */
}

.copy-button {
    margin-left: auto;
    padding: 5px 10px;
    font-size: 12px;
    cursor: pointer;
}
</style>