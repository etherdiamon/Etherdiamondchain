cpp-ethereum Contributing and Review Guidelines

All submitted Pull Requests are assumed to be ready for review unless they are labeled with [in progress] or have "[WIP]" in title.

Code formatting rules are described by the Clang-Format Style Options file .clang-format. Please use the clang-format (version 5.0 or higher recommended) tool to format your code changes accordingly. git-clang-format tool is useful to limit reformatting to your changes only:

git clang-format          # to reformat the changes in the staging area and put the result into working directory
git clang-format -f       # to reformat the changes in the working directory
git clang-format <commit> # to reformat commits between specified commit and HEAD
