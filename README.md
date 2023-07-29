WE ARE SAFE 

![Alt text](https://github.com/samy-soliman/Devops-ITI-collab/blob/main/Git-Icon-1788C.png)

########################################## <br />

Lab Questions ?<br />
###############<br />

1) remove branches locally ?<br />
git branch -d <branch_name>  ->>> remote <br />
git branch -D <branch_name>  ->>> local <br />

########################################### <br />

Tell me how to checkout another branch without commit changes ? <br />
git switch -f <branch-name> <br />

############################################ <br />

Tell me how to list tags? <br />
git tag <br />

############################################

Tell me how to delete tag locally and remotely.<br />

In order to delete a local Git tag, use the “git tag” command with the “-d” option<br />
$ git tag -d <tag_name><br />

In order to delete a remote Git tag, use the “git push” command with the “–delete” option and specify the tag name.<br />
$ git push origin :refs/tags/<tag><br />

note that we are the refs syntax because  your tag may have the same name as your branch.<br />

############################################## <br />