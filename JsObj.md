# 🧩 JavaScript Object Methods

## 🔹 1. Object.keys()
Returns an array of all **keys** in an object.

```javascript
let person = { name: "Shashidhar", age: 23, city: "Hyderabad" };
console.log(Object.keys(person));
```

✅ **Output:**
```javascript
["name", "age", "city"]
```

---

## 🔹 2. Object.values()
Returns an array of all **values** in an object.

```javascript
console.log(Object.values(person));
```

✅ **Output:**
```javascript
["Shashidhar", 23, "Hyderabad"]
```

---

## 🔹 3. Object.entries()
Returns an array of **[key, value] pairs**.

```javascript
console.log(Object.entries(person));
```

✅ **Output:**
```javascript
[["name", "Shashidhar"], ["age", 23], ["city", "Hyderabad"]]
```

💡 **Useful for looping:**
```javascript
for (let [key, value] of Object.entries(person)) {
  console.log(key + ": " + value);
}
```

---

## 🔹 4. Object.assign()
Copies values from one or more **source objects** to a **target object**.

```javascript
let target = { name: "Shashidhar" };
let source = { age: 23, city: "Hyderabad" };

Object.assign(target, source);
console.log(target);
```

✅ **Output:**
```javascript
{ name: "Shashidhar", age: 23, city: "Hyderabad" }
```

---

## 🔹 5. Object.freeze()
Prevents **modifications** to the object (cannot add, delete, or change properties).

```javascript
let user = { name: "Shashidhar" };
Object.freeze(user);
user.name = "Ravi"; // ignored
console.log(user.name); // "Shashidhar"
```

---

## 🔹 6. Object.seal()
Prevents **adding or deleting** properties but allows **modifying existing ones**.

```javascript
let user = { name: "Shashidhar" };
Object.seal(user);
user.name = "Ravi"; // ✅ allowed
user.age = 23;      // ❌ not added
console.log(user);
```

---

## 🔹 7. Object.create()
Creates a **new object** using another object as a **prototype**.

```javascript
let person = { greet() { console.log("Hello!"); } };
let user = Object.create(person);
user.greet();  // Hello!
```

---

## 🔹 8. Object.hasOwn() *(ES2022+)*
Checks whether an object has a specific property (without checking prototype chain).

```javascript
let user = { name: "Shashidhar" };
console.log(Object.hasOwn(user, "name")); // true
```

---

## 🔹 9. Object.getOwnPropertyNames()
Returns **all property names**, including non-enumerable ones.

```javascript
let obj = { name: "Shashidhar" };
console.log(Object.getOwnPropertyNames(obj));
```

✅ **Output:**
```javascript
["name"]
```

---

## 🔹 10. Object.fromEntries()
Converts **[key, value] pairs** back into an object (opposite of `Object.entries()`).

```javascript
let arr = [["name", "Shashidhar"], ["age", 23]];
let obj = Object.fromEntries(arr);
console.log(obj);
```

✅ **Output:**
```javascript
{ name: "Shashidhar", age: 23 }
```
