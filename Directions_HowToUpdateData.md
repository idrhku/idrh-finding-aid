# Instructions for updating the CSV

1. Pull to your local repository

```
git pull origin master
```

2. Update and save the CSV located in csv-to-html-table/data

Make sure to save the CSV as UTF-8 to preserve the encoded non-English characters.

3. Add and commit any files that were changed to your local repository with a descriptive message

```
git add *
git commit -m "updated idrh-talks-index" .
```

4. Push the changes to the gh pages branch on the remote repository 

```
git push origin master:gh-pages
```
