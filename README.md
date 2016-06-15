# Today in America

## 1. Setup
```bash
npm install
```
- install all npm and bower dependencies

**Note:** If `npm install` fails during dependency installation it will be likely caused by `gulp-imagemin`. In that case remove `gulp-imagemin` dependency from `package.json`, run `npm install` again and then install `gulp-imagemin` separately with following command: `npm install gulp-imagemin --save-dev`

## 2. Watch files
```bash
gulp
```
- all SCSS/HTML will be watched for changes and injected into browser thanks to BrowserSync

## 3. Build production version
```bash
gulp build

## 4. Start webserver without watch task
```bash
gulp server
```

## 5. Start webserver from build folder
```bash
gulp server-build
```

## Contact

Email: thaisrodrigues25rj@gmail.com
linkedin: https://www.linkedin.com/in/thaisrodriguesdesouza
