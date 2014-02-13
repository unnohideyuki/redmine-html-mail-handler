redmine-html-mail-handler
=========================

Redmine mail_handler to accept HTML email including inline images.

## Overview

When you use [Redmine CKEditor plugin](https://github.com/a-ono/redmine_ckeditor), you may also allow your redmine to accept HTML email to create an issue or comment.

This mail_handler.rb accept HTML email including inline images.

## Requirements

* [Redmine CKEditor plugin](https://github.com/a-ono/redmine_ckeditor)
* Redmine 2.3.4 (maybe or higher. I only tested with 2.3.4)

## How to use

Setup the redmine for [Receiving Emails](http://www.redmine.org/projects/redmine/wiki/RedmineReceivingEmails).

Replace app/models/mail_handler.rb with mail_handler.rb of this project.
