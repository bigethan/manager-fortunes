# Manager Fortunes

A fortune file from the manager guidleines suggested in https://medium.com/@keavy/who-i-want-to-work-for-b04ce972c202

Open to any PRs that add other instructions as well. I enjoy that these aren't cliches and are clear actions.

## Install
Download the `manager` and `manager.dat` files and put them somewhere together. Then run `fortune manager` to randomly get a line from the article.  If you need to install fortune `brew install fortune` on a mac.

## Build
the `manager` file is deliniated by `%` symbols on their own lines. To build the dat file run `strfile -c % fortunes fortunes.dat`
