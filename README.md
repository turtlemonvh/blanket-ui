# Blanket UI

A prototype UI plugin for blanket.

## Running

See README in `html` directory.

## TODO

- use card bordered areas to give everything a cleaner more organized look

- like Ionic, use divs with a slight shadow that separates them from other content

- make it flannel colors (dark, grays) instead of so bright
    - like a blanket
    - solarized dark would be good

- other UI
    - user should be able to upload files to include in a task run
    - add ability to shut down / restart main server from web ui
    - allow user to view and edit server configuration on UI
        - may need to allow them to trigger a restart
    - allow user to back up database from UI
    - add primitive main dashboard with recent activity
    - add ability to add new task types
    - allow editing task types on HTTP interface
    - add confirmations for delete / stop commands
    - bulk delete
    - a way to show messages for things we have done (toast messages)
        - https://github.com/CodeSeven/toastr4
    - re-run a task that has run, or is stalled
    - fix memory leak (was >500 mb when running for a while)
    - "_cat" api that gives information similar to the command line, but over http

- better browsing interface for files
    - instead of just a list, include modified time, size, etc.

