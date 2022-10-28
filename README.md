# (Broken) Blog app

This web application is broken. You have three objectives:

 * Find the bugs and fix them. **You can assume that the tests describe the correct behaviour** (so you shouldn't modify anything in the `spec/` directory)
 * You need to get **all the tests passing**.
 * You need to **run the app manually with your browser** and make sure it works. You can have a look at the user stories below to understand how the program is expected to behave (without bugs). 

## THE BUGS

There were 4 tests not passing to start with.

1. In the '/' method, the posts variable was missing an @ to make it an instance variable.
There were still 4 tests failing after correcting this.

2. In the index file the input tag labelled title had the name "content" instead of "title".
There were 3 tests failing after correcting this.

3. There was a random _ in from of the variable response.

4. In abb.rb, one of the parmeters was written at the_title, istead of title.
There are now 2 tests failing.

5. Again there was a POST instead of a GET method. Must remember to check for these.

6. In the post_manager.rb, in the all_posts_by_tag method, it was searching the titles for a given tag instead of the tags.
___
## User stories

Note that these user stories are **already implemented** by the app — they're here as guidance for you to understand what the program is about and how it should behave when correct.

```
As a developer who likes to blog,
So I can write about my learnings,
I'd like to add a new post on the blog.
```

```
As a developer who likes to read,
So I can read about cool tech things,
I'd like to browse the list of blog posts.
```

```
As a developer who likes to read,
So I can read about the things I'm interested with,
I'd like to browse the list of blog posts having a specific tag.
```



<!-- BEGIN GENERATED SECTION DO NOT EDIT -->

---

**How was this resource?**  
[😫](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fweb-applications&prefill_File=projects_to_debug%2Fblog_app%2FREADME.md&prefill_Sentiment=😫) [😕](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fweb-applications&prefill_File=projects_to_debug%2Fblog_app%2FREADME.md&prefill_Sentiment=😕) [😐](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fweb-applications&prefill_File=projects_to_debug%2Fblog_app%2FREADME.md&prefill_Sentiment=😐) [🙂](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fweb-applications&prefill_File=projects_to_debug%2Fblog_app%2FREADME.md&prefill_Sentiment=🙂) [😀](https://airtable.com/shrUJ3t7KLMqVRFKR?prefill_Repository=makersacademy%2Fweb-applications&prefill_File=projects_to_debug%2Fblog_app%2FREADME.md&prefill_Sentiment=😀)  
Click an emoji to tell us.

<!-- END GENERATED SECTION DO NOT EDIT -->
