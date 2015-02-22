# redmine_favourite_projects_redmine_fixtures

Slightly altered versions of Redmine's default fixtures to load without error and adapted for the purpose of testing the Redmine Favourite Project plugin (https://github.com/syntacticvexation/redmine_favourite_projects).


## Usage:

`rake db:drop db:create db:migrate redmine:plugins:migrate db:fixtures:load`