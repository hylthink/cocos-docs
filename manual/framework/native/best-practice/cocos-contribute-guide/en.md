#Cocos-docs Contribution Guide

##Preparation

Check out following tips before pull request:

[git](http://git-scm.com/) is a source version control system, it allows you using command line to interact with Github.

[SourceTree](http://www.sourcetreeapp.com/) is a GUI source code manage tool, which can simplify your operations with command line and easy to get used to. 

[Cocos-docs Contribution Guide](cocos-docs/manual/framework/native/best-practice/cocos-docs-style/en.md) is a set of official convention that can lead you to write a normal cocos-doc.

##Fork cocos-docs

Fork our [repo](https://github.com/cocos2d/cocos-docs) on Github first

![forkRepo](src/forkRepo.png)

Then, clone the repo to your local repo by inputting following code in command line:

```
cd ~/workingspace
git clone https://github.com/cocos2d/cocos-docs.git
```

##Add repo to SourceTree

Open SourceTree and add a repo

![addRepo1](src/addRepo1.png)

![addRepo2](src/addRepo2.png)

![addRepo3](src/addRepo3.png)

Then, you should create a remote repo in SourceTree to synchronize your repo from offical repo.

![remoteRepo1](src/remoteRepo1.png)

![remoteRepo2](src/remoteRepo2.png)

![remoteRepo3](src/remoteRepo3.png)

Now you can keep up with the official repo by `Pull from upstream`.

![remoteRepo4](src/remoteRepo4.png)

![remoteRepo5](src/remoteRepo5.png)

Push your local update to your Github repo.

![pushRepo](src/pushRepo.png)


##Add new doc and pull request

After you added new files in your local repo, add them to index and commit the change.

![addFile1](src/addFile1.png)

![addFile2](src/addFile2.png)

Now you can push the change in your remote repo on Github. 

![pushRepo](src/pushRepo.png)

One last thing, pull request for official repo on web page.

![pullRequest1](src/pullRequest1.png)

![pullRequest2](src/pullRequest2.png)

![pullRequest3](src/pullRequest3.png)
