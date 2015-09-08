# Bug Tracker

Review of ActiveRecord migrations, associations, querying, and validations.

I want to create a bug tracker for my development team. We have a few different web applications. Here's the basic idea:

## Developers
  - Should have email and password
  - Can have first and last name
  - Developers can be members of a project, even if there are no bugs in that project
  - Developers can work on multiple projects
  - Developers can also be assigned to a bug, but only in a project they belong to

## Applications
  - Should have a name
  - Can optionally have a description, but not too long!
  - Can have more than one developer assigned to work on this application

## Bugs
  - Should have a title or name
  - Can also optionally have a description, as long as they want
  - Should have a deadline (for completion)
  - Can belong to a single project, optionally
  - Can belong to a single developer, optionally

