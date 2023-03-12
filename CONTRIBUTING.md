# How to contribute?

- Step 1. Fork the repository to your GitHub account. This will create a copy of the repository that you can make changes to.
- Step 2. Next, navigate to the repository on your own account. This is where you'll make your changes and additions. But first you need to clone the repository to your local system using (replacing "YOUR_GITHUB_USERNAME" with your actual GitHub username)

```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/Py-Topics
```
- Step 3. Navigate to the directory.
```bash
   cd Py-Topics
```
- Step 4. Create a new branch and checkout to that branch.
```bash
   git checkout -b branch_name
```
- Step 5. Make your changes/addition and save your file.
- Step 6. Stage your changes, using
```bash
   git add .
```
- Step 6. Commit the changes with useful message.
```bash
   git commit -m "your message"
```
- Step 7. Finally, you'll need to push your changes to the branch you created in step 3. You can do this by running the command (using HEAD will prevent you from accidentally pushing to the wrong remote branch. )
```bash
   git push origin HEAD
```
- Step 8. Once your changes are pushed, you can go back to the Py-Topics repository on GitHub and make a pull request. This is where you'll describe your changes and ask for them to be reviewed and merged into the main repository.

## Contributing

We welcome pull requests. If there is an existing open issue that pertains to your work, that's fantastic! However, if you are introducing a new feature or template or if there's no relevant issue, please start by opening an issue to discuss your proposed changes.

Also, please ensure that you update the tests accordingly.

Lastly, checkout the sample template to make a structured changes that are consistent throughout the repository.
[Sample Template](https://github.com/PyTopics/Py-Topics/blob/main/Setups/sample_template.ipynb)

## License

[MIT](https://choosealicense.com/licenses/mit/)