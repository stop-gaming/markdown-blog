# Markdown Blog Posts Template

- This is where you write your blog, using your favorite **Markdown** and **Git**.
- The *Markdown files* **only** in the [drafts](./drafts) and [published](./published) directories will be **synchronized** to your blog as **posts**.

	When you `git push` after `git commit`, it will trigger the synchronization.

- [drafts](./drafts) are visible only to you on the blog.

## Categories

Here, `categories` are directories, and `posts` are placed in directories in the form of markdown files.

You never have to worry about losing SEO weight by renaming or moving a directory,
because we add `-directory_id` to the end of the link when adding a link to each directory.

Because the directory id will never change, when a directory is renamed, for example, from `abc` to `def`,
and the directory id value is 5, then when visiting `/category/abc-5`, the URL will be redirected with `status 301` to `/category/def-5`.

So, feel free to name your directories whatever you like.
Whether you name your directory `ruby_on_rails`, `Ruby_on_Rails`, `ruby-on-rails`, `Ruby-on-Rails`, `Ruby on Rails`, or `Ruby On rails`,
the name that will appear on your blog will be `Ruby on Rails`, and the URL path will be `/category/ruby-on-rails-7` (if the category id is 7).

## Markdown Files

You can name the Markdown file anything you want; the file name will not be used by your blog.
