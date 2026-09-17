# GitHub profile installation

This package is designed for the profile repository:

`Oussama-Lmekkedddem/Oussama-Lmekkedddem`

## Install the profile

1. Upload `README.md`, the `assets` folder, and the `.github` folder to the root of the profile repository.
2. Keep the folder structure unchanged so the local SVG paths continue to work.
3. Open the repository's **Actions** tab.
4. Select **Update Profile Stats** and choose **Run workflow**.
5. Refresh the profile after the workflow finishes.

The workflow replaces the two placeholder metric cards with current statistics and updates them daily. Because the generated SVG files are committed to your repository, profile visitors do not depend on a shared public statistics server.

## If the workflow cannot push

Open:

**Settings → Actions → General → Workflow permissions**

Select **Read and write permissions**, save, and run the workflow again.

## Optional private-repository statistics

The default workflow uses GitHub's built-in token and shows public statistics. Private-repository statistics require a separate personal access token. Do not place that token in the README or workflow file; store it as a repository secret instead.
