# hugo-mock-landing-page
CIS3500

## How the yaml file works
This GitHub Actions workflow is designed to automatically build and deploy a static website to GitHub Pages whenever new code is pushed to the main branch of the repository. It first checks out the full repository code, including any submodules like Hugo themes. Then, it sets up the Hugo environment by installing the specified version of Hugowith the extended feature set enabled. After that, it runs the Hugo command to compile all the static website files, including drafts, while performing garbage collection to remove unused cached resources and minifying the HTML, CSS, and JS files. Finally, it publishes these compiled files to the gh-pages branch of the repository, which is where GitHub Pages looks for content to serve. 

