## Project setup

### Install locally with npm

```
npm install
```

### Add it to your path

```
export PATH="$PATH:./node_modules/.bin"
```

### To save the HTML result to the build folder

```
mjml -r {filename}.mjml -o build/{filename}.html
```

### To Run and watch a file to automatically update the output file (index.html)

```
mjml --watch components/{filename}.mjml -o build/{filename}.html
```
