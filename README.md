# fail-on-main
Github Action to ensure Caller workflow is not executing on main branch


This is a github action that by default fail and exit the workflow when running on `main` branch. The rationale is that when working with workflow dispatch manually you can't set the workflow to not run steps on `main` branch. (or maybe just not to my awareness)


