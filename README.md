# yoink
Yoink is a quick tool for use with [Obsidian](https://obsidian.md) that will allow you to take a markdown file and package it up into a folder that will allow you to share an entire markdown document with someone else without having to manually copy all the attachments to a folder.

# What problem does yoink solve?
In Obsidian, when you have a large vault, keeping images organized can become unwieldy. If I wanted to share a single note with someone, I would have to be sure to include in a folder the markdown file as well as any attachments referenced by that markdown file. This can become painful if you wish to share a document with many attachments. Yoink allows you to search your vault for a single markdown file and copies it to an "extracted" folder along with all of it's attachments. This allows you to share a single folder without having to manually track down the attachments referenced by the markdown file.

![yoink](https://github.com/grahamhelton/yoink/assets/19278569/8a4e7508-7d89-400f-b13d-cb085163d0a7)


# Usage
- If you're searching for files that may contain spaces, ensure that your `note_to_find.md` is enclosed in double quotes.

`yoink -f "note_to_find.md" -l "/path/to/vault/"`



- Feel free to submit PRs to clean up the code, it is *very* messy but it gets the job done.
