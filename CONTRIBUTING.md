If you have a bugfix or new feature that you would like to contribute to Sapphire, please email us about it first. Talk about what you would like to do. It may be that somebody is already working on it, or that there are particular issues that you should know about before implementing the change.

Collaboration space (issues, wiki, etc.) for Sapphire will be setup soon.

##Guidelines for Contribution

NOTE: All development on Sapphire proceeds on the develop branch. Periodically, we push releases to the release branch.

1.	If you are contributing code, please fork the develop branch.
2.	Make your changes (new panels, bug fixes, style changes, etc.). Provide the datasets you use for testing the new functionality (along with Solr config/schemas, data import script/command, and dashboards) so that others can review your work. You can provide the commit id on your branch to your fellow contributors so that they can review your changes.
3.	Try and ensure backward compatibility of dashboards. This means existing dashboards should work. If not, please discuss with the community on why your change requires a revision of the dashboard structure. This also means that we expect no changes to the existing dashboards within the app/dashboards directory, though it is possible you may put in additional dashboards that showcase the new capabilities that you have added.
4.	When you have completed your development and testing, make an upstream pull; I.e.: pull the latest changes from the develop branch of the main sapphire repository to your fork. Merge conflicts as necessary on your fork. This will ensure that you are up to date, and that a merge onto the develop branch of the main repository will not create unnecessary conflicts, conflicts that would confuse your contribution. 
5.	Coordinate Step 4 with the Sapphire team lead (Louis Roehrs <lroehrs@us.ibm.com>) so that when you issue a pull request, he is ready to merge it immediately. If there is a time-gap between your pull request and the merge, the develop branch on the main sapphire repository may have moved, in which case you will need to repeat Step 4.


All the Best!

