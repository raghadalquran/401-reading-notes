
## Custom Hooks!
Custom Hooks are JavaScript functions whose names are prefixed with the word use. A custom Hook is a normal function but we hold them to a different standard. By adding the word use to the beginning, it lets us know that this function follows the rules of Hooks.


- **Hooks are exported as a function, named as useXXX()**
- **Hooks return data or behaviors (functions) that are required to reuse their internal functionality.**
- **Hooks are imported into components.**
- **Components can re-use the hook functionality or data/state as needed.**
- **Hooks do not render.**

## React Hooks with Async-Await  
- We cannot use 'async' keyword with 'useEffect' callback method. It will result in race conditions.  
- so we should fetch our data from an API then updating our 'setResult' state  
    so React.useEffect method will only run when our 'state' got change.  
    
