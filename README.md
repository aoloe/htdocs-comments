# htdocs-comments

A simple php comments engine.

# Features

- Comments are stored in text files (json?).
- Each application gets an authentication key.
- Comments are page specific and stored in one file per page.
- We can have the last n comments per application.
- Input is sanitized against known attacks.
- Spam detection (Akismet? Captcha?)
- Each comment must be manually accepted / deleted.
- Comments can be accepted per email (containg two links, for accepting and deleting which work without further authentication)
- Name and email fields are optional.
- A simple administrator interface for
  - Searching, accepting and deleting comments.
  - Activating and removing applications (and pages?).

Future features:

- Can be installed as an engine, used by web applications on the same or other servers.
- Banning IPs.


Features which (at least for now) won't be implemented:

- Threaded view.
- Voting.

# Possible inspirations

- https://github.com/duttski/comment-engine (no managing per email)
- http://ratherodd.com/commentator/ (way to complex)
- https://github.com/adtac/commento (just take the js part)
