

git config --global alias.all '!f() { ls -R -d */.git | xargs -I{} bash -c "echo {} && git -C {}/../ $1"; }; f' [details](https://stackoverflow.com/questions/3497123/run-git-pull-over-all-subdirectories)
