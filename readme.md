# //p1 started
# => git config --global user.name "peter-mahrous-aziz"
# => git config --global user.email petermahrousaziz@gmail.com
# => git init
# => git add .
# => git commit -m "first commit"
# => git remote add origin git@github.com:peter-mahrous-aziz/lab2.git
# => git push origin master
# //p1 done 
# 
================================================================
# //p2 started
# => git checkout -b dev 
# //dev.html file created
# => git add .
# => git commit -m "commit from dev"
# => git push origin dev

# =>git checkout -b test
# //test.html file created
# => git add .
# => git commit -m "commit from test"
# => git push origin test
# //p2 done

================================================================
# //p3 started
# => git checkout master
# => git rebase dev
# => git rebase test
# => git push origin master
# //p3 done

================================================================
# //p4 started
# Tell me how to remove them locally and remotely.

# to delete branch locally => git branch -d BranchName
# to delete branch remotly => git push origin : BranchName
# //p4 done

================================================================
# //p5 started
# Tell me how to checkout another branch without commit
# changes

# => git stash
# => git checkout BranchName
# //p5 done

================================================================
# Create an annotated tag with tagname (v1.7)
# => git tag -a v1.7 -m "version1.7"

# Push it to the remote repository
# => git push origin v1.7

# Tell me how to list tags.
# => git tag

# Tell me how to delete tag locally and remotely.

# locally => git tag -d TagName

# remotely => git push origin : TagName

![image description]("img.jpg")