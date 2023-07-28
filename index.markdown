# _readme

A set of standard for GitHub repos, README.md files, and README.md assets.

## GitHub Repos

When creating GitHub repos, follow these guidelines:

1. Repository names are all lowercase and use the kebab case naming convention. For example `php-contact-form`, `html-forms`, or `personal-portfolio`.
2. Repository descriptions are one short sentence using sentence case.
3. Repository should be assigned all relevant topics.
4. Prefix forked repositores with `forked-`. For example `forked-brickmmo-core`.
5. Always include a `.gitignore` file. The file should at least ignore `.DS_Store` files.

## README.md Files

When creating README.md files for your GitHub repositories, follow these guidelines:

1. Use one tic (\`) for inline code and three tics (\`\`\`) for coding blocks. Provide the language when using coding blocks (\`\`\`php).
2. Each README.md should use a main title using # and sub-titles when appropriate using ##.
3. Do no include usernames or passwords in README.md files (or coding samples). Using the following format to block out confiential information:

    ```php
    define('SENDGRID_API_KEY', '<SENDGRID_API_KEY>');
    define('SENDGRID_API_SECRET', '<SENDGRID_API_SECRET>');
    ```

4. 
