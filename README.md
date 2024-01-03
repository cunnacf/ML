# ML
Repository dedicated to the notebook of the lab work in machine learning

I used git lfs because the file Sujet_DT was too big to be uploaded. You can find some informations about this module on the page https://git-lfs.com/ or https://github.com/git-lfs/git-lfs/blob/main/docs/man/git-lfs-migrate.adoc?utm_source=gitlfs_site&utm_medium=doc_man_migrate_link&utm_campaign=gitlfs. 

I guess that to export it you have to use a specific command or maybe not. So first try to pull it and then use it in a normal jupyter notebook page (Lab1, mlp, Sujet_DT) if its not working try this maybe
# Convert all zip Git LFS objects to files in your main branch
$ git lfs migrate export --include-ref=main --include="*.zip"

# Convert all zip Git LFS objects to files in every local branch,
# fetching any object data not cached locally from the my-remote Git remote
$ git lfs migrate export --everything --include="*.zip" --remote=my-remote

# Convert all Git LFS objects to files in every local branch
$ git lfs migrate export --everything --include="*"
