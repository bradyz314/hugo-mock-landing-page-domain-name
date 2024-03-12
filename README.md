# Hugo Mock Landing Page
This is for CIS3500 HW2. The goal of this homework was to use GitHub Actions to automatically deploy the Hugo website that was developed in CIS3500 HW1. The yaml file that deploys the Hugo website was provided by Jérémie Lumbroso. The deploy job checks out the repository code and fetches the entire commit history to ensure accurate Git metadata, sets up the Hugo environment, runs the hugo command to build the static files for the website, and then publishes the files to the branch that sources the website.
This time, the website is deployed to a custom domain.
