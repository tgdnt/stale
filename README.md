 stale

This is an add-on for [todo.sh](https://github.com/todotxt/todo.txt-cli/)
that moves todos into a separate file called stale.txt, where you would
keep todos that you haven't actually got around to doing in a while
and want to get them out of your sight so as not to clutter your todo.txt
file. Evidently these are not urgent todos, maybe you shouldn't even have
added them in, and also they don't really fit into a specific outline, so for
now you will just set them aside and take another look when you have a chance.

Usage:

```
todo.sh stale prune ITEM# - moves an item into your stale.txt file
todo.sh stale ls - lists your stale todos
todo.sh stale restore ITEM# - moves an item out of your stale.txt file back into todo.txt
```
