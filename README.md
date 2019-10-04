
## Usage

Assumes component project is in parallel folder.

See: https://github.com/mitchallen/react-component-example

After building the project above, clone this project to a parallel folder and do the following:

```
npm run link:sibling

npm start
```

## Linking to component project

The **link:sibling** script does the following:

```
sudo npm link ../react-component-example/
```

Remove `sudo` from the command if not needed.

Assumes react-component-example is in a parallel project folder.


## View sudo link (Mac)

Search for the link:

```
 npm list -g | grep 'react-component-example' 
```

You should see something like this:

```
├─┬ react-component-example@1.0.0 -> /Users/mitch/projects/react-apps/react-component-example
```

* * * 

## How this project was created

This is a React / TypeScript project.

```
npx create-react-app react-component-example-test --typescript

cd react-component-example-test/
```
