# screeps-server-dev
> development setup to get started with modifying the screeps server

## Installation
```bash
git submodule update --init --recursive
npx yarn
npm run init
```

## Build
```bash
npm run build
```

## Run server
```bash
npm start
```

## Known issues
- After installation some modules have unstaged changes, this should only be incorrect file permissions for some of the executables. This can be solved by disabling file mode changes in submodules:
```bash
git submodule foreach 'git config core.fileMode false'
``` 
