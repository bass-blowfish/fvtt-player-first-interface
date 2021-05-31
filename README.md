# Implementation
If you don't want to use an image for the title, use the  "Original Text Title Code" branch. If you do want to use an image for the title use the second codeblock below under the title "Image Title Code" .

If you ARE using the image title code and want to use a different image, place the image in the foundryvtt/resources/app/public/ui folder and change "dnd-logo.svg" in the CSS to whatever your file is named.

I've written up the CSS so this should only target the elements in the login screen and not anywhere else. I've notated the code so it's easy to modify and see what's going on.

The way I'm implementing this is by just adding the code below to the end of foundryvtt/resources/app/public/css/style.css. I recommend always backing up the original CSS file just in case. Also as I understand it any updates to Foundry will possibly overwrite this file and you'd need to re-apply it at that point.
