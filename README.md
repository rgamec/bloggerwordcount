# Blogger Word Count
Since this feature isn't yet integrated into Google Blogger, use the quick bookmarklet below to spawn a pop-up box (à la early editions of MS Word) showing a rough count of the number of words in your post.

This is to be used from the Post Editor screen.

## Usage
1. Create a new bookmark (e.g. on a bookmarks toolbar), name it something reasonable like "Blogger Wordcount" and set the location attribute to the following:

`javascript:alert("Words: " + document.getElementById("debugPostingComposeBox").value.match(/ /g).length)`

2. Then just click the link whenever you're on the Post Editor screen to get a word count. 

## Todo
Do a 'correct' word count instead of just counting spaces. 
