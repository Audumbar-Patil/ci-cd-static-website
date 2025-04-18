🚀 Building and Deploying a Static Website with GitHub Pages and GitHub Actions
I'm excited to share how I built and deployed a simple static website using HTML, CSS, and GitHub Pages, with full CI/CD automation using GitHub Actions.

Here’s how I went from building the website to automating its deployment:

1. Building the Static Website 🖥️
First, I created the core of the website, which consists of:

HTML: The structure of the website (e.g., header, footer, content sections).

CSS: Styling to make the website look clean and modern. I used flexbox for the layout and added hover animations for interactive elements.

Assets: Images and logos to add visual appeal.
2. Setting Up GitHub Repository 📂
I created a GitHub repository to store the project and enable easy deployment. Here’s how I set it up:

Created a new repository on GitHub (e.g., my-static-website).

Cloned the repository to my local machine.

Added the necessary HTML, CSS, and assets to the repository.

3. Pushing Code to GitHub 🚀
After creating the local files, I pushed the website code to GitHub using the following Git commands:
# Initialize local git repo
git init

# Add all files
git add .

# Commit the changes
git commit -m "Initial commit with website files"

# Add remote origin
git remote add origin https://github.com/username/my-static-website.git

# Push to GitHub
git push -u origin master
4. Automating Deployment with GitHub Actions ⚙️
To automate the deployment process to GitHub Pages whenever I push new changes, I set up a GitHub Actions workflow. Here’s how I did it:

Created a .github/workflows directory in the repo.

Added a deploy.yml file to the directory, containing the CI/CD pipeline configuration.
5. Deploying the Website to GitHub Pages 🌐
Once the CI/CD pipeline was set up, every time I pushed changes to the repository’s master branch, the GitHub Actions workflow would trigger, build the project, and automatically deploy it to GitHub Pages.

6. Accessing the Website 🌍
Now, my static website is live! I can easily access it via https://username.github.io/my-static-website/.

