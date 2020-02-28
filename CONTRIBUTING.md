Adding your Talks
=================

We're really grateful for your presentation at ConFoo 2020. Please use this guide to share your slides and code samples with attendees.


## TL;DR

1. Slides: `presentation_name-author_name.pdf`.

2. Demos: `presentation_name-author_name.zip` or a GitHub/GitLab/BitBucket/etc link.

3. Place in folder matching date of presentation.

4. Update README.md to include links.

5. PR the changes into this repository.


## Steps to add your content

1. Fork the repo: After logging into GitHub, click `Fork` on the top-right of this repository.

2. Clone the repo: In your forked repository, click `Clone or Download` and copy the git url. Use your favorite Git tool to clone the repository onto your machine.

3. Open the folder for the date you delivered the presentation.

4. Create files for your content.  We use a careful naming convention to ensure there will be as few merge conflicts as possible.

   Slides: `presentation_name-author-name.pdf`  Please create a pdf version of your slides. In the rare case your slides can't be made into a PDF, you can include a link to the slides instead.

   Demos: `presentation_name-author_name.zip`  Please link to GitHub, GitLab, BitBucket, or a location for your source code. If your source code doesn't live online, please create a zip file of your code samples.

   For example, Yann Larrivee is giving a presentation titled "Our Amazing Presenters" to be delivered on Feb 31.  He has slides but no demos.  So his presentation file will be `our_amazing_presenters-yann_larrivee.pdf` and be placed in the `2020-02-31` folder.

5. Update the README.md to link to your presentation on the ConFoo website, and to the slides and code files you added.  https://www.markdownguide.org/cheat-sheet/ is a helpful Markdown reference.

6. Commit the changes.

7. `git push origin master` to send the changes to your forked repository.

8. Return to the master repository, and create a pull request.

9. In short order, we'll merge your changes into place, and your presentation content will be available to all.


## Changing Content

Need to update your slides or demos?  That's totally easy.  Just repeat the steps above, altering the files that need changing, and submit a new pull request.
