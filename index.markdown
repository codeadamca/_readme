# _readme

A set of standard for GitHub repos, README.md files, and README.md assets.

## GitHub Repos

When creating GitHub repos, follow these guidelines:

1. Repository names are all lowercase and use the kebab-case naming convention. For example `php-contact-form`, `html-forms`, or `personal-portfolio`.
2. Repository descriptions are one short sentence using sentence case.
3. Repository should be assigned all relevant topics.
4. Prefix forked repositores with `forked-`. For example `forked-brickmmo-core`.
5. Always include a `.gitignore` file. The file should at least ignore `.DS_Store` files.

## README.md Files

When creating README.md files for your GitHub repositories, follow these guidelines:

1. Use one tic (\`) for inline code and three tics (\`\`\`) for coding blocks. Provide the language when using coding blocks (\`\`\`php).
2. Each README.md should use a main title using # and sub-titles when appropriate using ##.
3. Do not include usernames or passwords in README.md files (or coding samples). Using the following format to block out sensitive information:

    ```php
    define('API_KEY', '<API_KEY>');
    define('API_SECRET', '<API_SECRET>');
    ```
    
## README.md Assets

When adding images to a README.md file, place the files inside a folder names `_readme`. Images should follow these guidelines:

1. Images names are all lowercase and use the kebab-case naming convention. For example `terminla-nom-start.jpg`.
2. Images should have a maximum width of 624 pixels.
3. Most screenshots are 624 pixels wide. Terminal screenshots are 400 pixels wide. 
4. Screenshot files are prefixed with `screenshot`. For example `screenshot-codeadam-ca.png`.

---

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="50">
</a>
