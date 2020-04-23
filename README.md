Replace default stylesheets from rails new with custom components etc.
```
curl -L https://github.com/scrumpygeo/stylesheets/archive/master.zip > stylesheets.zip
```
or in rails 6:

```
rm -rf app/assets/stylesheets
curl -L https://github.com/scrumpygeo/stylesheets/archive/master.zip > stylesheets.zip
unzip stylesheets.zip -d app/assets && rm stylesheets.zip && mv app/assets/rails-stylesheets-master app/assets/stylesheets
```
