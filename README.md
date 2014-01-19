# WunderlistConverter

Tools to convert Wunderlist backups to other formats.  It's currently [just a standalone webpage](http://benjaminoakes.github.io/WunderlistConverter/) where you paste in your Wunderlist JSON.

[
![Flattr this git repo](https://api.flattr.com/button/flattr-badge-large.png)
](https://flattr.com/submit/auto?user_id=benjaminoakes&url=https://github.com/benjaminoakes/WunderlistConverter&title=maid&language=en_GB&tags=github&category=software)

The following formats are supported:

  * GitHub-Flavored Markdown
  * Taskpaper

Pull requests with additional formats are welcome!

## Formats

### GitHub-Flavored Markdown

Example:

     ## Inbox

       - [ ] Incomplete task

     ## List 1
     
       - [ ] 2013-01-08 Task with due date

     ## List 2

       - [ ] Starred task #star
       - [x] Completed task

### Taskpaper

Example:

    Inbox:
    	- Incomplete task
    
    List 1:
    	- Task with due date @due(2013-01-08)
    
    List 2:
    	- Starred task @star
    	- Completed task @done
