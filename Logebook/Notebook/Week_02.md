
---

# **WEEK 2 – Variables and Data Types**

---

## **1. What is a Variable?**

A **variable** is used to **store data** in a program.

It acts like a **container** that holds information which can be used or changed later.

### **Example**

```python
age = 20
name = "Mithlesh"
```

### **Explanation**

* `age` stores a number
* `name` stores text
* The value on the right side is assigned to the variable on the left

---

## **2. Rules for Naming Variables**

* Variable names must start with a **letter or underscore (_)**
* They should not start with a number
* No spaces are allowed
* Names should be meaningful

### **Good Examples**

```python
total_price = 500
student_name = "Mithlesh"
```

---

## **3. What are Data Types?**

A **data type** defines the type of data a variable can store.

Different data types are used to store different kinds of values.

---

## **4. Common Data Types in Python**

| Data Type | Description                  | Example              |
| --------- | ---------------------------- | -------------------- |
| `int`     | Integer (whole number)       | 10, 25               |
| `float`   | Decimal number               | 2.5, 3.14            |
| `string`  | Text (written inside quotes) | `"Hello"`, `"Raman"` |

---

## **5. Examples of Data Types**

```python
price = 100        # int
rating = 4.5       # float
name = "Pizza"     # string
```

### **Explanation**

* `price` stores a whole number
* `rating` stores a decimal value
* `name` stores text

---

## **6. Checking the Data Type**

Python provides a built-in function called `type()` to check the data type of a variable.

```python
print(type(price))
print(type(rating))
print(type(name))
```

### **Output**

```
<class 'int'>
<class 'float'>
<class 'str'>
```

---

## **7. Conclusion**

In Week 2, we learned:

* What variables are
* How to create variables in Python
* Different data types such as `int`, `float`, and `string`
* How to check the data type using `type()`

These concepts are very important for writing **basic Python programs**.

---