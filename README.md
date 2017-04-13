# GetAllGit
Generates a CSV table that describes the current state of ALL git enlistments on a machine (or collection of machines). The primary use case for a script like this: a) determine the current state of a dev machine with a lot of repositories, b) useful for production deployments that involve cloning a lot of git repositories. Current information: machine name, ip address(es), local enlistment path, remote url, current branch, current tag(s), most recent sync time, current commit date, current commit description, current commit short hash.
