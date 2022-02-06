---
title: Text Modifiers
permalink: /layout/modifiers/text

---
- Text Content

  The text to display. Does **not** support Markdown. 
  
See [List of Variables](#list-of-variables) for displaying dynamic content.
{: .notice--primary}

- Text Size

  Size of the text.

- Text Color

  Color of the text.

- Font Family

  Font of the text.

## List of Variables

- @title@

  Post title.

- @score@

  Post score.

- @author@

  Author username.

- @authorFlair@

  Author flair.

- @linkflair@

  Post flair.

- @subreddit@

  The subreddit the post belongs to. **No** _r/_ prefix.

- @comments@

  Number of comments.

- @domain@

  URL domain if the post is a link, or _self.subreddit_ if it is a text post.

- @age@

  How old is the post.

- @thumbnail@

  The smallest thumbnail image.

- @selftext@

  Text content if the post is a text post; empty string if the post is a link.

- @postId@

  Internal Reddit ID of the post. Used for navigating to the comments page.
