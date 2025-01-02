# Contributing

## Creating a Pull Request

New to GitHub? If you're not familiar with terminal commands, using GitHub Desktop
to raise Pull Requests is recommended.

## With GitHub Desktop

1. Download GitHub Desktop: https://desktop.github.com/download/
2. Fork and clone the repository: https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop
3. Create a branch for your changes: https://docs.github.com/en/desktop/making-changes-in-a-branch/managing-branches-in-github-desktop
4. Create a new folder inside `emojis` with the name of your emoji(s).
5. Drag your emoji into the new folder, name it the same as the folder name.
	1. Ensure it is a **PNG** image.
	2. Ensure the dimensions are 512x512 pixels or larger.
6. Optionally, add `author.txt` containing your username for attribution.
7. Your folder structure inside `emojis` should look like the following:
	```
    +- MyEmojiName
       +- MyEmojiName.png
       +- author.txt
  	```
8. Commit your changes https://docs.github.com/en/desktop/making-changes-in-a-branch/committing-and-reviewing-changes-to-your-project-in-github-desktop
9. Create a Pull Request: https://docs.github.com/en/desktop/working-with-your-remote-repository-on-github-or-github-enterprise/creating-an-issue-or-pull-request-from-github-desktop#creating-a-pull-request


## With Git

1. Fork this repository.
2. Clone your fork.
	```
	git clone https://github.com/zeepkist/emojis.git
	cd emojis
	```
3. Create a branch for your emojis.
	```
	git checkout -b my-new-emojis
	```
4. Create a new folder inside `emojis` with the name of your emoji(s).
5. Drag your emoji into the new folder, name it the same as the folder name.
	1. Ensure it is a **PNG** image.
	2. Ensure the dimensions are 512x512 pixels or larger.
6. Optionally, add `author.txt` containing your username for attribution.
7. Your folder structure inside `emojis` should look like the following:
	```
    +- MyEmojiName
       +- MyEmojiName.png
       +- author.txt
  	```
8. Commit your changes.
	```
	git commit -am 'feat: add MyEmojiName'
	```
9. Push your changes.
	```
	git push
	```
10. [Open a Pull Request][0] from your fork.
11. Accept the conditions in the Pull Request body.
12. Your Pull Request will be reviewed and merged if the conditions are met.

[0]:https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork
