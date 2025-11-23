# QA Automation Engineer Portfolio

This is a modern, responsive portfolio website designed for a QA Automation Engineer. It features a premium dark mode design with glassmorphism effects.

## Project Structure

- `index.html`: The main HTML structure.
- `style.css`: The CSS styles for the premium design.
- `script.js`: JavaScript for smooth scrolling and animations.
- `profile_placeholder.png`: A generated placeholder image for the profile.

## How to Run

You can run this website using any static file server.

### Using Python (simplest)

Run the following command in this directory:

```bash
python3 -m http.server 8080
```

Then open your browser and navigate to `http://localhost:8080`.

### Using VS Code Live Server

If you have the Live Server extension installed in VS Code, simply right-click `index.html` and select "Open with Live Server".

## Customization

- **Profile Image**: Replace `profile_placeholder.png` with your own photo.
- **Content**: Edit `index.html` to update your name, experience, and skills.
- **Colors**: You can adjust the color variables in `style.css` (e.g., `--primary`, `--secondary`) to match your personal brand.

## Deployment

To host this portfolio on GitHub Pages:

1.  Create a new repository on GitHub.
2.  Push your code to the repository:
    ```bash
    git remote add origin <your-repo-url>
    git branch -M main
    git push -u origin main
    ```
3.  Go to your repository **Settings** > **Pages**.
4.  Under **Source**, select `Deploy from a branch`.
5.  Select `main` branch and `/ (root)` folder, then click **Save**.
6.  Your site will be live at `https://<your-username>.github.io/<repo-name>/`.
