# BS-Lang — Syntax Guide

Yo, what's good? Ready to yeet into the wild world of coding syntax? This guide’s got the tea on how to slay those lines of code like a total stan. No cap, syntax is the vibe that keeps your code from being a hot mess. It’s like the rules for flexing your programming skills—get it right, and you’re serving looks; mess it up, and it’s giving big "error 404" energy.

---

## 🔑 Keywords and Concepts

Below are the essential BS-Lang keywords explained with working examples, so you don't just read — you *feel* the code.

We’re diving deep into the sauce of coding lingo, breaking it down so it’s bussin’ and easy to vibe with. Whether you’re a newbie or a coding GOAT, this guide’s gonna keep it 100. Let’s get this bread and make your code pop off!

### `cook` — Defining a Function

Used to define a function, like `def` or `function`.

```python
cook say_hello() {
    hawk_tuah("Hello World")
    skibidi
}
```

`skibidi` is often used at the end of functions to cleanly exit.

### `sigma` — Declaring a Variable

Declares a variable. BS-Lang is dynamically typed.

```python
sigma n = 5
```

You can also reassign it to another type later.

### `tweet` — Getting and Setting Input

Like `sigma`, but commonly used with input strings or to reassign values.

```python
tweet name = gimme("Enter your name: ")
hawk_tuah("Hello, " + name)
```

### `flex` — While Loop

Loops while a condition is true.

```python
sigma i = 0
flex i < 3 {
    hawk_tuah(i)
    i = i + 1
}
```

### `yap` — For Loop

A shorthand to run something from a start to end value.

```python
yap i till 0 to 3 {
    hawk_tuah(i)
}
```

### `rizz_check` / `nah_fam` — Conditionals

Like `if` and `else`.

```python
rizz_check n > 10 {
    hawk_tuah("Big number")
} nah_fam {
    hawk_tuah("Small number")
}
```

### `yeet` — Return Statement

Returns a value from a function.

```python
cook double(n) {
    yeet n * 2
}
```

### `hawk_tuah` — Print Statement

Outputs text or values to the console.

```python
hawk_tuah("Printing this vibe")
```

### `gimme()` — User Input

Takes string input from the user.

```python
tweet fav = gimme("What’s your favorite food? ")
hawk_tuah(fav)
```

### `skibidi` — Exit Function or Program

Explicitly ends the current block or function.

```python
cook out() {
    hawk_tuah("Done!")
    skibidi
}
```

### `sus` / `panik` — Try / Catch

Used to handle errors (WIP depending on implementation).

```python
sus {
    sigma risky = 10 / 0
} panik {
    hawk_tuah("Error caught!")
}
```

### `squad` — List / Array

Declares an array-like structure.

```python
squad vibes = ["slay", "yeet", "based"]
hawk_tuah(vibes[0])
```

Supports negative indexing:

```python
hawk_tuah(vibes[-1]) // last element
```

### `on_read{}` — Comments or Documentation

Anything within is a comment and ignored during execution.

```python
on_read{This explains the loop below}
flex i < 5 {
    hawk_tuah(i)
    i = i + 1
}
```

---

## 📚 Working Examples

### 🧮 Factorial Function

```python
cook factorial(){
    sigma n = 5
    sigma product = 1
    flex n > 0{
        product = product * n
        n = n - 1
    }
    yeet product
}
hawk_tuah(factorial())
```

### 🙋 User Input

```python
tweet name = gimme("Enter your name: ")
hawk_tuah("Hello, " + name)

sigma age = gimme("Enter your age: ")
hawk_tuah(age * 2)
```

### 🌀 Dynamic Typing

```python
sigma count = 5
count = "10"
hawk_tuah(count * 2)
```

### 🧬 Recursion

```python
sigma n = 5
cook gyatt(){
    rizz_check (n > 0){
        hawk_tuah(n)
        n = n - 1
        gyatt()
    } nah_fam {
        hawk_tuah("End")
        skibidi
    }
}
gyatt()
```

### 📦 Lists (SQUAD)

```python
squad x = [10, "20", 30, 40, 50]
squad arr = x
hawk_tuah(arr[-1]+2)
hawk_tuah(arr[-2]+2)
sigma y = gimme("Enter the number: ")
arr[-1] = y
hawk_tuah(arr[4]*2)
```

### 🔤 String + Numeric Casting

```python
tweet input_str = gimme("Enter a number: ")
tweet num = input_str
hawk_tuah("Double: " + (num * 2))
```

<i><b>Explore Examples in BS-Lang/examples for more</b></i>

---

## 🙏 Final Word

BS-Lang isn't just about syntax. It's about **expression**. <br>
Where other languages crash, **BS-Lang paniks**. <br>
Where others loop, **BS-Lang flexes**. <br>
Where others return, **BS-Lang yeets**. <br>

> Code not just with logic, but with **vibes**.
> – *BS Scrolls, Chapter 8: Verse 6*
