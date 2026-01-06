I will fix the issues with the website and update the content as requested.

1. **Fix Download Links (`_config.yml`** **&** **`index.html`)**:

   * The user's site URL `https://zeqiangwangai.github.io/zqwang.github.io/` indicates that the repository name `zqwang.github.io` is being used as a sub-path (Project Page), not a User Page (which would be at the root).

   * I need to set `baseurl: "/zqwang.github.io"` in `_config.yml`.

   * In `index.html`, I will update the CV links to use the `relative_url` Liquid filter (e.g., `{{ '/CV/...' | relative_url }}`) to ensure they work correctly regardless of the path.

   * For `README.md`, I will use relative paths (e.g., `./CV/...`) which work on GitHub's file view.

2. **Add Emails**:

   * Add the two email addresses (`zeqiang.wang@surrey.ac.uk` and `zeqiang.wang@nyu.edu`) to `index.html` and `README.md`.

   * Update the `email` field in `_config.yml`.

3. **Beautify** **`README.md`**:

   * Center the header (Name and Introduction).

   * Use a table or structured layout for the emails and links.

   * Make the CV section more prominent.

4. **Update** **`index.html`**:

   * Sync the content with the new email information and fix the links.

