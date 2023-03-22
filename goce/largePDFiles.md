To upload large PDF file on Github/Gitlab <b>

download and install the git LFS extension (for Windows) <b>

by going on ![](git-lfs.com) <b>

Then, in the command line enter <b>

	git lfs install

In the git repository where the large .pdf file is located enter <b>

	git lfs track "*.pdf"

	git add .gitattributes

After, do the usual commands to push to Github/Gitlab

	git add *.pdf

	git commit -m ""

	git push
