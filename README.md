#### Submitting Presentation Slide

1. Take permission from your presentation partner.
2. Fork the repo.
3. Remove **matriculation number** from the slide.
4. Rename the pdf file as `GroupNumber TopicName.pdf`. (eg: 04 Presentation on Structure and Architecture of a Scientific Paper.pdf)
5. Copy the slide in its respective topic group directory.
6. Commit. (Ref: [Creating a commit with multiple authors](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors))
```
git add .
```
```
git config --local user.email author@mailbox.tu-dresden.de
```
```
$ git commit -m "group 4 slide
>
>
Co-authored-by: co-author-name <co-author@mailbox.tu-dresden.de>"
```
6. Submit PR.
