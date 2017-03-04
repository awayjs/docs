# AwayJS Static Docs Generator

This project produces a static documentation site for the AwayJS software API.
AwayJS is written in Typescript and the documentation is generated using Typedoc,
so the docs, as the code, are fully typed.

## Self Deployment

Any push to any of the AwayJS modules will trigger a Travis CI rebuild of the documentation,
so the static docs site should remain up to date with the source code from the **dev** branches at
all times.

## Local Copy

This repository does not track any documentation files or output, only the generator files, so
in order to obtain a local copy of the documentation, you will have to clone this repository and 
run the generation yourself:

```typescript
npm install
```

and then,

```typescript
npm run docs
```

This will generate a bin folder with the documentation. Note that you will have to repeat the above
commands each time you want to get the latest docs.

## Custom Typedoc Implementation/Theme

This uses a modified version of [https://github.com/TypeStrong/typedoc](Typedoc). However,
all modifications are done at runtime in a single file, externaly to typedoc, [https://github.com/awayjs/docs/blob/master/awaydoc.js](awaydoc.js).
This means that no typedoc code is ever altered.
Most changes are generally minor tweaks of features that typedoc doesn't support out of the box.
Other than that, this can be considered to be a custom typedoc theme.

## Feedback

Please provide any feedback in this repository. We are here to help. 
Hopefully this will be a valuable resource and reference to AwayJS users.