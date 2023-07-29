WE ARE SAFE 

![Alt text](https://github.com/samy-soliman/Devops-ITI-collab/blob/main/Git-Icon-1788C.png)

##########################################

Lab Questions ?
###############

1) remove branches locally ?
git branch -d <branch_name>  ->>> remote
git branch -D <branch_name>  ->>> local

###########################################

Tell me how to checkout another branch without commit changes ?
git switch -f <branch-name>

############################################

Tell me how to list tags?
git tag

############################################

Tell me how to delete tag locally and remotely.

In order to delete a local Git tag, use the “git tag” command with the “-d” option
$ git tag -d <tag_name>

In order to delete a remote Git tag, use the “git push” command with the “–delete” option and specify the tag name.
$ git push origin :refs/tags/<tag>

note that we are the refs syntax because  your tag may have the same name as your branch.

##############################################