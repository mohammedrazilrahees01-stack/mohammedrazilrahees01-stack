# Install this replacement

This is a **salesp07-style GitHub profile README replacement**. It intentionally replaces the dashboard-style profile from the previous ZIP.

1. Extract this ZIP into the same local folder/repository used for the previous package.
2. Allow it to overwrite `README.md` and `.github/workflows/contribution-snake.yml`.
3. In the repository folder, run:

   ```bash
   git add README.md .github/workflows/contribution-snake.yml
   git commit -m "Replace dashboard profile with clean developer README"
   git push origin main
   ```

4. On GitHub, open **Settings → Actions → General → Workflow permissions**, choose **Read and write permissions**, and save.
5. Open **Actions → Generate contribution snake → Run workflow** once. It creates the `output` branch used by the animated contribution section.

The profile photo remains GitHub's normal sidebar photo. This README does not use a duplicate image or ASCII portrait.
