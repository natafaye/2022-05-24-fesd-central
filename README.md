# FESD Central 2022-05-24 Class Playground

## Connecting to the Class Repository

1. Find a good spot on your computer, open Git Bash there, and clone the repository to your computer (you may need to log in)
```
git clone https://github.com/natafaye/2022-05-24-fesd-central.git
```

2. Open the repository folder in VS Code

3. Create a folder with your name and inside that folder, create a .html and a .js file

4. Go into the .html file, type `!` and hit Enter.

5. Add this line to your HTML file and replace `your-js-file.js` with the name of your .js file:
```html
<script src="your-js-file.js"></script>
```

6. Commit your changes
```
git add .
git commit -m "Added html and js"
```

7. Pull down any commits pushed up by others
```
git pull --rebase origin main
```

8. Push your commit to the online repository
```
git push -u origin main
```

9. Check that your folder and files are showing up in the online repository

10. Add some Javascript to your .js file. Maybe something like this:
```javascript
console.log("Hello developers!");
```

11. Commit your new changes
```
git add .
git commit -m "Added console logging"
```

12. Pull down any commits pushed up by others
```
git pull --rebase
```

13. Push your commit to the online repository
```
git push
```

