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
  - May float in space forever, doomed to an uncertain future (this is a realistic bug tracker)

## Pro Tips

Should is an indicator that a validation may be necessary to enforce a business requirement. Can is an indicator that we need a column/attribute, but maybe we don't need to enforce it strictly. Look for language about associations between objects to decide how to design the schema. Start by designing a schema 