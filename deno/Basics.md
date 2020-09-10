## What is Deno?

#### Deno is a  secure Javascript/Typescript runtime based on the v8 Javascript engine and the Rust programming Language(Ryan Dahl)

# Why?

#### Cool-Features of Deno
- Uses Typescript
- Secure by Default
   - Runs in a sandbox  
- De-Centralised Packages
   - No more NPM packages/package.json
   - Packages are imported from a URL - https://deno.land/x/oak/mod.ts 
   - Then it is cached to hard-drive on load
- Standard Library
   - Extensive standard library for things like fs,datetime,https etc
   - 
- Modern JS
   - Deno takes advantage of latest JS,like import in ES6
   - we can use await with wrapping in global with async!
- ES Modules
- Top Level/First Class Await
- Built in Testing
- Browser Compatible API

## Installation
### Package managers:
curl
scoop
choco
brew
cargo(best for linux)
```js
> I installed it with curl: (UBUNTU)
> curl -fsSL https://deno.land/x/install/install.sh | sh
```


```js
- Deno was installed successfully to /home/supertramp_piyush/.deno/bin/deno
- Manually add the directory to your $HOME/.bash_profile (or similar)
  export DENO_INSTALL="/home/supertramp_piyush/.deno"
  export PATH="$DENO_INSTALL/bin:$PATH"

```

