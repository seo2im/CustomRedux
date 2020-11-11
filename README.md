# Custom Redux

> OBJECT

1. Knownledge what is **Redux**
</br></br>

## What is Redux

**Redux** is 'state management framework' for javascript. It make possible to separte 'state management code' from 'component code'</br></br>Redux work like `ContextAPI`, but redux offers more than state management. For example, can use middleware.</br></br>Redux has advantages with react.
1. Can separate 'state management code' from 'component code'
2. Easy to send data in server rendering
3. Make co-work environment by sending 'action structure' in network
4. Can make 'TDD' in state management
5. Easy to write code for loading local storage.
6. Can change UI with re-using business logic.

from [Dan Abramov Medium](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367)

## Redux Structure

![Redux image]()

Redux has **Store**, **Action**, **Reducer** </br></br>**Store** has states.</br>**Action** is flag for changing state.</br>**Reducer** is function to make new state in store.

## Redux Rule

1. **Save all state in a structure**


2. **State is immutable**

State must be changed 'action structure'

3. **State must be changed by pure function**