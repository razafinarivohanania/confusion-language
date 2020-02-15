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