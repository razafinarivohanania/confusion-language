## Method both static and asynchronous in class

* Wrong :

```js
class Class {

    async static method() {
        //TODO
    }
}
```

* Correct :

```js
class Class {

    static async method() {
        //TODO
    }
}
```

## Export variable

* Wrong :

```js
default export variable;
```

* Correct :

```js
export default variable;
```

### Read object data from illegal key characters

* Wrong :

```js
const value = objet.key-0;
```

* Correct :

```js
const value = object['key-0'];
```