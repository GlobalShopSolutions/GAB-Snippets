# GAB Snippets
GAB snippet files for use in GAB Code Editor (3.0+).

## Usage
To use, place these files in a folder inside \Global\Plugins named "GAB-Snippets" or "GAB-Snippets-[username]" where "[username]" is a Global shop username *(i.e.: "GAB-Snippets-supervsr")*.

## Snippet Format
To add your own snippets, create a text file with the extension **.gabsnippet** and place in snippets folder.

### Title
The first line of your snippet should have the title between double brackets (`[[` and `]]`).

#### Example
    [[If Statement]]

### Wildcards
Wildcard elements of your snippet should be surrounded by percent symbol `%` on each side.

#### Example
    F.Intrinsic.Control.If(%Condition%)

### Cursor
To indicate where the cursor should appear once the snippet has been inserted and modified, place two pipe characters in the location it should appear `||`.

## Contribute
If you have any GAB snippets you would like to contribute to this repository, fork this repository, make your changes, and submit a pull request.

You can find more info on this here:
* https://help.github.com/articles/fork-a-repo/
* https://help.github.com/articles/creating-a-pull-request-from-a-fork/