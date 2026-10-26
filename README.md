# otto-mail-bridge

One static page. It opens the visitor's own email app with a new email, filled in from the link.
Built for a family trip-planning page that sits inside claude.ai, which blocks email links but
allows ordinary web links to open in a new tab.

- The address, subject and message are carried after `#` in the link, which browsers never send to
  the server. No address is stored in this repository.
- Nothing is sent by the page and nothing is stored. It only opens the visitor's email app, where
  they see the email before pressing Send. There is no server code.

Link shape: `https://mickmcc100.github.io/otto-mail-bridge/#to=<address>&s=<subject>&b=<message>`
