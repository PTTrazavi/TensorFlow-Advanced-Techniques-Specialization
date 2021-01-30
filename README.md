This repository is for my learning record, please don't use it for your homework if you haven't passed the course.  
# How to download homework files from coursera
Refer to [2]  
zip folder into single tar file  
```
tar -czf workspace.tar.gz work
tar -xf workspace.tar.gz
```
zip folder into multiple tar files  
```
tar -czf - work | split --bytes=100MB - workspaces.tar.gz
cat workspaces.tar.* | tar -xf -
```

# References
[1] https://www.coursera.org/specializations/tensorflow-advanced-techniques  
[2] https://learner.coursera.help/hc/en-us/articles/360004990332-Download-Jupyter-Workspace-files  
