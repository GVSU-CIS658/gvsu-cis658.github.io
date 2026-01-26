# CSS Zen Garden

— CSS Layout & Design

In this assignment, you will create a complete visual redesign of the classic **CSS Zen Garden** page using CSS only. The HTML structure and content are provided and must remain unchanged. Your task is to demonstrate how modern CSS can transform the same HTML into a visually compelling, well-structured, and responsive layout.

This assignment focuses on layout, styling, and design, not JavaScript or dynamic behavior. You are expected to apply modern CSS techniques for organizing smaller components.

## Objectives

By completing this assignment, you will practice:

- Structuring page layout using CSS Grid
- Organizing components using CSS Flexbox
- Writing clean, maintainable CSS
- Creating a responsive design without modifying HTML
- Managing source code with GitHub
- Deploying a static site using GitHub Pages

## Preparation

- **IDE Setup:** Use [VS Code](https://code.visualstudio.com/) for editing and managing your code.
- **Development Environment:**
  1. **NodeJS Environment Setup**: Choose one of the following options to set up your NodeJS environment,
     - Docker Container: Create a Node.js development environment with Docker. For detailed instructions, please refer to the [class slides](../assets/pdf/Docker.pdf).
     - Direct Install: Alternatively, you can install NodeJS directly from the [NodeJS official website](https://nodejs.org).

     In the context of this document, the term `terminal` refers to:
     - Command Prompt: On Windows systems.
     - Terminal: On macOS systems.
     - Shell or Bash: Inside a Docker container, depending on the base image of the container.

     Verify the installation by execute the command in `terminal`:

     ```bash
     node -v    # v14 or newer
     npm -v     # v8 or newer
     ```

  2. **GitHub Setup:**
     1. Create a [GitHub account](https://github.com) if you don't have one.
     2. Ensure you can access your GitHub account using an SSH Key. If you haven't set this up, follow the steps below or check this [tutorial](https://youtu.be/a-zX_qc2S-M).
        - Open a `terminal`. If you haven't yet configured an SSH key for GitHub on your machine, generate a new one with the following command:

          ```bash
          ssh-keygen
          ```

        - Navigate to your GitHub account settings(web). Click on `SSH and GPG keys` and then `New SSH key`. Paste the public key that was generated in the first step and click `Add SSH key`. ![github-sshkey](../assets/img/github-sshkey.png)

        - Set up your GitHub username and email in a `terminal``. You can do this with the following commands:

          ```bash
           git config --global user.name "Your Name"
           git config --global user.email "your-email@example.com"

          ```

  3. Accept your instructor's [GitHub classroom invitation](https://classroom.github.com/a/4PBR5Nlz) to set up your project repository.
     1. **Select Your Name:** ![select-name](../assets/img/github-classroom-selectname.png)
     2. **Initialize Your Assignment Repository:** ![init-repo](../assets/img/github-classroom-initrepo.png)
     3. **Clone the Repository:** ![clone](../assets/img/github-classroom-sshclone.png) You're now ready to clone the repository. In your `terminal`, use the following command with your SSH repository link to download the repository to your local machine:

        ```bash
        git clone [YOUR_SSH_REPO_LINK]
        ```

     4. **Install Required Packages:** Execute the following command to install the necessary packages for your project:

        ```bash
        cd [YOUR_REPO]
        npm install
        ```

  4. Run a local development server (default port 5173):

     ```bash
     npm run dev
     ```

     Then you can access your project at `localhost:5173` in browser.

## Project Files

You will work with the following files:

- `index.html` (provided)
- `main.css` (you write all CSS here)

### Important Rules

- Do not modify the HTML structure or content
- Do not add JavaScript
- Do not use inline styles
- Do not use CSS frameworks (Bootstrap, Tailwind, etc.)
- The only allowed HTML change is linking your CSS file:

```html
<link rel="stylesheet" media="screen" href="main.css" />
```

All visual changes must be done in `main.css`.

---

## Requirements

### 1. Page Layout (CSS Grid — Required)

- Use **CSS Grid** for the overall page structure
- Create a clear layout (e.g., header / main / sidebar / footer)
- Layout must fill the browser width
- **No horizontal scrolling**

---

### 2. Component Layout (Flexbox — Required)

- Use **Flexbox** for at least one of the following:
  - Navigation links
  - Sidebar lists
  - Grouped content sections

- Flexbox should be used intentionally, not just once to satisfy the requirement

---

### 3. Typography & Readability

- Clear heading hierarchy (`h1`, `h2`, `h3`)
- Appropriate line height and spacing
- Text must be readable on all screen sizes
- Choose fonts thoughtfully (system fonts are fine)

---

### 4. Visual Design

- Consistent color palette
- Intentional spacing and alignment
- Sections visually separated
- Avoid default browser styling

---

### 5. Responsiveness

- Page must work on both desktop and narrow screens
- No overlapping content
- No clipped text
- Images (if any) must not overflow containers

---

## Grading Rubric

| Category                                               |  Points |
| ------------------------------------------------------ | ------: |
| GitHub setup, commits, push, & GitHub Pages deployment |      15 |
| CSS Grid layout (structure, responsiveness, no scroll) |      20 |
| Flexbox usage (navigation/components)                  |      10 |
| Typography & readability                               |      15 |
| Section styling & layout consistency                   |      15 |
| Visual design & aesthetics                             |      15 |
| Code quality & organization                            |      10 |
| **Total**                                              | **100** |

## Deliverables

- Deploy your web application using the following commands in your `terminal`:

  ```bash
   npm run build
   npm run deploy
  ```

- Github Page Setup
  - Set up your GitHub repository for GitHub Pages deployment. Follow the steps shown in the image below: ![Layout](../assets/img/github-page.png).
  - Your web application will be accessible at the URL: gvsu-cis658.github.io/YOUR-REPO

- Submit the URL of your GitHub Page in Blackboard.
