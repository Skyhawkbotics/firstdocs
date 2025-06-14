# Contributing

Thank you for contributing to the FTC community docs! You are enhancing the knowledge base for current and future FTC teams, making FTC better for everyone.

## Update an Existing Page

1. Locate the page on the live website.
2. Click the edit icon. The button is located to the right of the page title.
3. Make your desired changes in the GitHub interface.
4. Once you are done, click the green "Commit changes" button.
5. Follow GitHub's instructions to create a pull request for your changes. For this type of change, set the target branch to `content`.

Once you have made your changes, we will review them, and if they pass, we will merge your pull request and it will soon become part of the documentation.

## Adding Your Team Page

1. Go to `source/docs/teams` folder in GitHub.
2. Create a file with this format: `[team-number].md`
   - If your team number is `12345`, name your file `12345.md`.
3. Populate your file with the information you wish to add.
4. Once you are done, click the green "Commit changes" button.
5. Optional: If you feel inclined to make your page visible, you may do so. Otherwise, skip this step and we can do this for you.
   1. Open `source/mkdocs.yml`.
   2. Locate the `nav` property (this is located at the top).
   3. In the `Teams` section, add an entry for your new page with the following format: `teams/[team-number].md`. Mind the numerical order.
   4. Once you are done, click the green "Commit changes" button.
6. Follow GitHub's instructions to create a pull request for your changes. For this type of change, set the target branch to `content`.

## Editing Something Else

1. Fork this repository.
2. Clone your fork onto your machine.
3. Create a virtual Python enviornment for this repository.
4. Install the dependencies from the list contained in `source/requirements.txt`.
5. Navigate to the root folder of this repository in your terminal
6. Run the appropriate activation script for your virtual enviornment and system
7. Change your directory to `source`
8. Run `mkdocs serve`, and open the link it outputs in your browser.