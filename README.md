# ASReview Projects for testing
This repository has asreview project files created in different versions for testing compatibility in the latest version.

## Move code to `.asreview/` folder
MacOS code to download project files and move to `./asreview` folder.
```
curl -LOk https://github.com/asreview/asreview-project-files-testing/archive/master.zip -o ~/Downloads/projects.zip
unzip ~/Downloads/projects.zip -d ~/Downloads/asreview_projects/
rm -f ~/Downloads/projects.zip

mkdir -p ~/Downloads/.asreview
for dir in ~/Downloads/asreview_projects/asreview-project-files-testing-master/*/
do
    dir=${dir%*/}
    mv ${dir}/* ~/.asreview
done

```

## License 

All work in this repository is CC0 licensed.

##  Contributors

- [Yongchao Terry Ma](https://www.linkedin.com/in/yongchao-ma/) ([@terrymyc](https://github.com/terrymyc))
- [Jonathan de Bruin](https://www.uu.nl/staff/JdeBruin1) ([@J535D165](https://github.com/J535D165))

