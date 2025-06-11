<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GitHub Pages Course</title>
  <meta name="description" content="Create a site or blog from your GitHub repositories with GitHub Pages." />
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 40px;
      background-color: #f9f9f9;
      color: #333;
    }
    header, footer {
      background-color: #e9ecef;
      padding: 20px;
      border-radius: 10px;
    }
    main {
      margin: 40px 0;
    }
    h1, h2, h3 {
      color: #222;
    }
    code {
      background-color: #f4f4f4;
      padding: 2px 5px;
      border-radius: 4px;
    }
    pre {
      background-color: #f4f4f4;
      padding: 10px;
      border-radius: 5px;
      overflow-x: auto;
    }
    ol li {
      margin-bottom: 10px;
    }
    a {
      color: #0366d6;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>GitHub Pages</h1>
    <p><em>Create a site or blog from your GitHub repositories with GitHub Pages.</em></p>
  </header>

  <main>
    <h2>Step 2: Configure your site</h2>
    <p><em>You turned on GitHub Pages! 🎉</em></p>
    <p>We're working in a branch called <code>my-pages</code>, created for you to get this site looking great. ✨</p>

    <p>
      GitHub Pages uses <strong>Jekyll</strong>, which relies on a file called <code>_config.yml</code> to manage your site settings, theme, and reusable content like your site title and GitHub handle.
      You can find this file under the <strong>Code</strong> tab of your repository.
    </p>

    <p>For this course, we'll use the blog-ready theme named <strong>minima</strong>.</p>

    <h3>⌨️ Activity: Configure your site</h3>
    <ol>
      <li>Go to the <code>_config.yml</code> file in the <code>my-pages</code> branch.</li>
      <li>Click the pencil icon to edit the file.</li>
      <li>Add the following line:
        <pre><code>theme: minima</code></pre>
      </li>
      <li>(Optional) Modify the other configuration values like <code>title</code>, <code>author</code>, and <code>description</code> to customize your site.</li>
      <li>Commit your changes.</li>
      <li>(Optional) Create a pull request to merge your changes into <code>main</code>. Go to the <strong>Pull Requests</strong> tab, click <strong>New pull request</strong>, and select <code>base: main</code> and <code>compare: my-pages</code>.</li>
      <li>Wait about 20 seconds, then refresh the page. <a href="https://docs.github.com/en/actions">GitHub Actions</a> will automatically update to the next step.</li>
    </ol>
  </main>

  <footer>
    <p>
      Need help? 👉 <a href="https://github.com/orgs/skills/discussions/categories/github-pages">Post in our discussion board</a> •
      <a href="https://www.githubstatus.com/">Check GitHub Status</a> •
      <a href="https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md">Code of Conduct</a> •
      <a href="https://gh.io/mit">MIT License</a>
    </p>
    <p>&copy; 2023 GitHub</p>
  </footer>

</body>
</html>
