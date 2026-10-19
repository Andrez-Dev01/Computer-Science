# EXAMPLE — For Loops (Python)

**Subject / language:** Python
**Learning goal:** Understand repetition and experiment with a loop.

---

## 1. What is it?
A `for` loop takes one item at a time from an iterable, such as a list or a `range`, and runs a block of code for each item.

## 2. Important words
- **Iterable:** An object you can iterate over.
- **Iteration:** One repetition of the loop's body.

## 3. How do I use it?
```python
for number in range(3):
    print(number)
```
The program prints `0`, `1`, and `2`, one per line. `range(3)` does not include 3.

## 4. Example I learned from
```python
scores = [90, 80, 100]
for score in scores:
    print(score)
```
**How the example works:** The loop variable receives each list element in order.

**Source:** Original demonstration example. When studying from documentation, link it beside the relevant fact.

## 5. My own test
**What I changed or built in my editor:** Create a script that totals the numbers in a list.

**Result:** (fill this in after running it)

**Code file / repository:** (fill this in)

## 6. Common errors and fixes
- **Error:** Missing a colon after the `for` statement.
  **Fix:** Write `for x in values:` and indent the body.
- **Error:** Expecting `range(3)` to include `3`.
  **Fix:** Remember the stop value is excluded.

## 7. Practice and takeaways
- [ ] Print even numbers from 0 to 10.
- [ ] Write the loop from memory.
- [ ] Explain what happens in every iteration.

**Remember:** Loops repeat work; they don't require you to copy the same statements many times.
