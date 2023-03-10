# Git-for-Professionals
  GIT:
			1) Git is an open-source distributed version control system. 
	    2) It is designed to handle minor to major projects with high speed and efficiency. 
			3) It is developed to co-ordinate the work among the developers.
	
	Features of Git:
			*Fully distributed VCS
  		*Data Integrity And Security
  		*Supports Non-linear Development
  		*Branching
  		*Lightweight and Fast
																																				
	The Perfect Commit:
			1) A more precise commit that’s focused on a single topic.
			2) A commit that makes sense one that only includes includes changes from a single top. 
	
																																					
	Adding changes to Commit:
			1) To create a perfect commit we should not cram every file into one commit.
			2) Selective and carefully deciding what should ngo into one commit is really important.
			3) Bigger a commit gets ,the more topics  are mixed into the commit which will be harder to understand for users.
			4) Staging areas can select individual files for one commit and leave others for future commit.
	
	
	Perfect Commit Message:
			1)It should be understandable even by seeing only the header of the message.
      2)It should be just enough, and not too detailed.
			3)It should be unambiguous.

 	Branching Strategies:
			1)written convention.
			2)Git allows you to create branches but not tell how to use them.
			3)It helps to on board new team mates.
			4)It depends on your team and projects.
	
	Integrating Changes and Structuring Releases:
			1)Mainline Development("Always integrating").
			2)State,Release and Feature Branches(Enhances Structures and work Flow).
			
	These two types of branches are long running and Short lived Branches.
	The distention between a long running and a short lived branches is one of the broadest and very helpful one.
	
	Long running and Short Running branches:
	
	a)long running branch:
			1)Exists through the complete life time of the project.
			2)Often they mirror stages in your dev life cycle.
			3)They also called Integration Branches.
	      
  b)Short lived branch :
	 		1)for new feature, bug fixes, refractories , experiments
      2)Will be deleted after integration ( merge/rebase).
			 
	Examples for branching strategies:
			1)Github flow.
			2)Git flow.
		
	1)Git hub flow:
			very simple, lean
      Has only 1 long- run branch( main )+ feature branches
  2)GitFlow:
			more structures, more rules
      Long-running:"main"+ develop
      Short-lived: features, releases,hotfixes
	main branch is a reflection of the current production state.
	the other long running branch is typically called develop.in branches
	
	Pull Requests:
	    1)helps in comminucating about code and rewiewing it with pull requests 
			2)can invite other users to review your work and give feedback
	Fork:																																		
			1)Apersonal copy of a git repository.
			2)Creating a fork of the original repository ,where  user can make changes and suggest changes to be included via pull request.
	Merge conflicts:
			1)Occurs when integrating commits from different Sources.
			2)Occurs when you integrate when you merge changes from a different Sources
						like cherry-pick ,or a pull ,or even when re-applying a stash.
			3)Merging branches works effortlessly most of the time ,becuse Git is usually able to figure out on its own.
	How to solve a conflict:
			1)We can solve a conflict by clean up the file.
	                      
												
	Merge Vs Rebase:
			1)It is important to use branches in git because seperate containers for user work is helpful.
			2)Integrating branches about getting new code back into existing branch.
			The different ways to do this are merge and rebase.
			                       
														 MERGE.                              Vs.                    REBASE

   1. Merge lets you merge different branches.                    Rebase allows to integrate the changes from one branch to another.
   2. Shows complete history of commit merging .                  Rebase logs are Linear
   3. All commits are combined into a single master branch.       Same number of commits are added to master branch.
   4. Best used when target branch is to be shared.               Best used when target branch is private.
   5. Preserve history.                                           Rewrites history.

	 History of two branches in a project they always have one commit in common.
	 The goal of an integration is to combine the current states of two branches.

	NOTES:
  a) Do not use Rebase on commits that have already pushed/shared on remote repository.
  b) Instead use it for cleaning up local commit history before merging it into shared team branch.


			
																																					
																																					
																																					
																																					
																																					
																																					
																																					
