# Oh, soggy oatmeal!

### Looking for a `README`? I have a [gist](https://gist.github.com/mitchejj/d71eb91be5107ae9380a889e10a8e68c) for that.

#### More
Since the gist things have changed.

Soggy-oatmeal is now a repo the 'content' as I keep looking forward. I have a few branches currently 

* `images` -- needs no explination
* `blog-archive` -- an archive of old blog post (from nullog & StaticDraft)
* `content-pages` -- a mix of all the other 'content'
* `about` -- needs no explination
* `io` -- kind of like a tech/projects space
* `suggest` -- when breadking out `content-pages` this was also in the branch and wanted to save it... its long forgotten concept I had to give suggestions/track pages.

##### Steps

`git remote rm origin`

`git filter-branch --subdirectory-filter <dir to archive> -- --all`

`git remote add origin git@github.com:mitchejj/soggy-oatmeal.git`

`git checkout -b <branch>`

`git push -u origin <branch>`

I 'should' now be able to 'import' them into other projects with

`git submodule add -b <branch name> https://github.com/mitchejj/soggy-oatmeal <dir name>`

I can then update the module with

`git submodule update --rebase --remote`
