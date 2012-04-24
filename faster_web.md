# Let's Make the Web Faster
## Ilya Grigorik
http://bit.ly/faster_rails

Most web pages load between context switch and starting a new task. Too slow.

Pages are getting bigger, more requests per page. Ave ~ 1 meg, ~84 requests!

New navigation timing spec: present timing of previously-opaque timing stats to
the browser so you can instrument them (like DNS-lookup time, etc.).

This new data is in Google Analytics now.
