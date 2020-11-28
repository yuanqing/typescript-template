# TypeScript Template

```sh
# Clone
$ git clone https://github.com/yuanqing/typescript-template
$ mv typescript-template my-project
$ cd my-project

# Interpolate project name
$ sed -i '' 's/typescript-template/my-project/' package.json

# Bump all dependencies to their latest versions
$ npx npm-check-updates --upgrade

# Install
$ yarn
```
