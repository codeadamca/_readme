# _readme

<style>@import url("//readme.codeadam.ca/readme.css");</style>

A set of standards for GitHub repos, README.md files, and README.md assets.

## GitHub Repos

When creating GitHub repos, follow these guidelines:

1. Repository names are all lowercase and use the kebab-case naming convention. For example `php-contact-form`, `html-forms`, or `personal-portfolio`.
2. Repository descriptions are one short sentence using sentence case.

    For repositories using GitHub Pages and Markdown, the description should be short and without a period as the description is placed into the home page title. For example `_readme | Formatting standards for GitHub repos and README.md files`.

3. Repository should be assigned all relevant topics in the repo settings.
4. Prefix forked repositories with `forked-`. For example `forked-brickmmo-core`. These repos do not need to follow _readme guidelines, this would cause future conflicts when pulling forked updates.
   
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

    Or:

    ```php
    DB_HOST=<DB_HOST>
    DB_DATABASE=<DB_DATABASE>
    DB_USERNAME=<DB_USERNAME>
    DB_PASSWORD=<DB_PASSWORD>
    ```
    
## README.md Assets

When adding images to a README.md file, place the files inside a folder names `_readme`. Images should follow these guidelines:

1. Images names are all lowercase and use the kebab-case naming convention. For example `terminal-nom-start.jpg`.
2. Images should have a maximum width of 624 pixels.
3. Most screenshots are 624 pixels wide. Terminal screenshots are 400 pixels wide. 
4. Screenshot files are prefixed with `screenshot`. For example `screenshot-codeadam-ca.png`.

## Citations

Citations placed in a README.md or Markdown file should use APA guidelines, a `>`, and wrapped in the `<small>` tag. For example:

```markdown
> <small>LEGO (n.d.). LEGO 12 Grimmauld Place. Retrieved August 7, 2023, from [https://www.lego.com/en-ca/product/12-grimmauld-place-7640](https://www.lego.com/en-ca/product/12-grimmauld-place-7640)</small>
```

Once rendered, it will appear as:

> <small>LEGO (n.d.). LEGO 12 Grimmauld Place. Retrieved August 7, 2023, from [https://www.lego.com/en-ca/product/12-grimmauld-place-7640](https://www.lego.com/en-ca/product/12-grimmauld-place-7640)</small>

## readme.css

The _readme guidelines also include some basic CSS rules to the GitHub default styles for Markdown conversion. To apply these CSS rules just import the `readme.css` file at the top of the markdown file (or directly after the `#` title if you have one):

```html
<style>@import url("//readme.codeadam.ca/readme.css");</style>
```

Currently this CSS file adds the following styles:

- Tables are 100% width
- All table content ls left aligned

> You can view the raw CSS file at  
> [https://readme.codeadam.ca/readme.css](https://readme.codeadam.ca/readme.css)

---

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="50">
</a>  
