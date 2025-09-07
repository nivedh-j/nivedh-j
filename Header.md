<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Social Links</title>
  <style>
    .social-links {
      display: flex;
      gap: 8px;
      background: #111;
      padding: 10px;
    }

    .social-links a {
      display: inline-block;
      padding: 10px 16px;
      color: #fff;
      text-decoration: none;
      font-family: Arial, sans-serif;
      font-size: 14px;
      font-weight: bold;
      border-radius: 4px;
      transition: opacity 0.2s ease-in-out;
    }

    .social-links a:hover {
      opacity: 0.8;
    }

    /* Colors for each platform */
    .linkedin { background: #0077B5; }
    .stackoverflow { background: #f48024; }
    .website { background: #999; color: #111; font-weight: normal; }
    .devto { background: #0A0A0A; }
    .twitter { background: #1DA1F2; }
    .github { background: #181717; }
    .gitlab { background: #6e1e9c; }
  </style>
</head>
<body>
  <div class="social-links">
    <a href="https://linkedin.com" class="linkedin" target="_blank">LinkedIn</a>
    <a href="https://stackoverflow.com" class="stackoverflow" target="_blank">Stack Overflow</a>
    <a href="https://yourwebsite.com" class="website" target="_blank">Website</a>
    <a href="https://dev.to" class="devto" target="_blank">Dev.to</a>
    <a href="https://twitter.com" class="twitter" target="_blank">Twitter</a>
    <a href="https://github.com" class="github" target="_blank">GitHub</a>
    <a href="https://gitlab.com" class="gitlab" target="_blank">GitLab</a>
  </div>
</body>
</html>
