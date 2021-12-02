# Manager Fortunes

A fortune file from the manager guidleines suggested in https://medium.com/@keavy/who-i-want-to-work-for-b04ce972c202

Open to any PRs that add other instructions as well. I enjoy that these aren't cliches and are clear actions.

## Install
1. Download the `manager` and `manager.dat` files and put them somewhere together (I put them in `~/.fortunes`).
1. If you need to install fortune `brew install fortune` on a mac
1. Then run `fortune ~/.fortunes/manager` to randomly get a line from the article.
1. To see one every time you open a terminal, add that line to your *rc. .

## Add your own
the `manager` file is deliniated by `%` symbols on their own lines. To build the dat file after you edit the `manager` file run `strfile -c % manager manager.dat`
