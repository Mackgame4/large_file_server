# large_file_server
A repository to save and allow download/acess to larger files needed/used in other repositories

This repository uses [Git Large File Storage](https://git-lfs.github.com/) to store large files as suggested by [GitHub](https://docs.github.com/en/repositories/working-with-files/managing-large-files) doe to the [100MB limit on files on Github](https://help.github.com/en/github/managing-large-files/what-is-my-disk-quota)

## Files
$ [main](https://github.com/Mackgame4/large_file_server)<br/>
.<br/>
├── [.gitattributes](.gitattributes)<br/>
├── 📂 [booking-dataset-manager](https://github.com/dium-li3/grupo-23)<br/>
│   └── 📁 [dataset.zip](dataset.zip)<br/>
└── [README.md](README.md)<br/>

## How to use

1. [Install Git LFS](https://github.com/git-lfs/git-lfs)
2. Clone this repository
3. Run `git lfs pull` to download the files

## How to add files

1. [Install Git LFS](https://github.com/git-lfs/git-lfs)
2. Clone this repository
3. Run `git lfs track "path/to/file"` to track the file
4. Run `git add .gitattributes` to add the file to the repository
5. Run `git commit -m "Add large file"` to commit the file
6. Run `git push` to push the file to the repository

## How to remove files

1. [Install Git LFS](https://github.com/git-lfs/git-lfs)
2. Clone this repository
3. Run `git lfs rm "path/to/file"` to remove the file
4. Run `git rm "path/to/file"` to remove the file from the repository
5. Run `git commit -m "Remove large file"` to commit the file
6. Run `git push` to push the file to the repository