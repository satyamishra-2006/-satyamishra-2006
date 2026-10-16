# Host your portfolio free with GitHub Pages

You do not need to pay, install Node.js, or add JavaScript. The portfolio works as a static site.

## 1. Extract and check your ZIP

1. Download `SATYAM_KUMAR_MISHRA_HTML_CSS_Portfolio.zip`.
2. Extract it. Open the extracted project folder and double-click `index.html`.
3. Check spelling, photos, project statuses, and contact details. Edit with VS Code or a text editor if needed.

## 2. Create a public GitHub repository

1. Sign in to the GitHub account `satyamishra-2006` at https://github.com.
2. Use **+ → New repository**.
3. For a simple project URL, name the repository `portfolio` (if already taken, choose a different name).
4. Choose **Public**. Use public visibility for free GitHub Pages on a personal GitHub Free account. Your photos, email, and code will be visible publicly.
5. Create the repository. Do not upload credentials or other sensitive files.

## 3. Upload the extracted files (not the ZIP)

1. In the new repository, select **uploading an existing file**. If it already has files, use **Add file → Upload files**.
2. Drag the **contents** of the extracted project folder into the upload area, including `index.html`, `style.css`, and the `images` folder. Upload the folders intact so the relative image paths work. The screenshot and documentation files may be included as well.
3. `index.html` must be at the repository root, not inside another portfolio folder.
4. Enter a commit message such as `Add personal HTML and CSS portfolio` and commit the changes to the default branch (normally `main`). If uploading folders is difficult on mobile, use a desktop browser.

The repository root should look like this:

```text
index.html
style.css
images/
screenshots/
README.md
...documentation files
```

## 4. Enable Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch** as the source.
3. Select the branch containing the files (normally `main`) and the folder **/ (root)**.
4. Click **Save**. No build command or custom domain is needed.
5. Allow a few minutes for deployment. Check **Actions** for completion and return to **Settings → Pages** for the published URL.
6. If you used the account and repository name above, the expected URL is:
   `https://satyamishra-2006.github.io/portfolio/`
   This is an expected URL, not a claim that the site has already been published. Use the exact URL GitHub displays after successful deployment.

Alternative: a repository named exactly `satyamishra-2006.github.io` normally publishes at `https://satyamishra-2006.github.io/` instead. Use this only if you want an account-level website and understand any existing site may be affected.

## 5. Verify the published site

- Open the published URL in a signed-out/private window and on your phone.
- Check photos and styling. File names are case-sensitive.
- Click Home, About, Skills, Projects, and Contact; each should scroll to its section.
- Try all profile links. The supplied profiles have not been independently ownership-verified.
- Try the email link; it should open a configured mail client.
- If you see 404, confirm the deployment completed, the selected branch is correct, and `index.html` is at the root. Verify the repository name in your URL.
- For missing images/CSS, preserve the `images/` folder and file names, and retain relative paths rather than computer-specific paths.
- To update, upload an edited file to the same path and commit. Wait for redeployment; a hard refresh may clear old cached content.

## 6. Submit the internship project

The PDF gives this official form:
https://docs.google.com/forms/d/e/1FAIpQLSfLJkwxKh8nHF1u6hj803j_x3hg5DavCNK41N0Vto9ZEmLdoA/viewform?usp=header

1. Open the form and confirm it is still accepting submissions. It has not been opened or submitted on your behalf.
2. Fill in the student information it actually requests.
3. If uploads are accepted, attach the project ZIP, or the files requested by the form. It already contains source files and both screenshots.
4. Paste the text from `PROJECT_DESCRIPTION.txt` if a description is requested.
5. If requested, provide your real repository URL and the working published Pages URL. A repository URL and a hosted URL are different.
6. Review everything, then submit yourself and retain the confirmation.

**Deadline in the brief: 16 October 2026; closing time unspecified.** Hosting is optional, so do not delay an otherwise complete required submission while waiting for Pages. Certificate issuance is scheduled to begin after the deadline, not immediately upon submission.
