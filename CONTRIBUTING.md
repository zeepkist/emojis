# Contributing

## Creating a Pull Request

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
7. [Open a Pull Request][0] from your fork.
8. Accept the conditions in the Pull Request body.
9. Your Pull Request will be reviewed and merged if the conditions are met.

[0]:https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork
