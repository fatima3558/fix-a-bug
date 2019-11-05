# 🛠 fix-a-bug

## Setup

Clone this repo.

```bash
git clone https://github.com/datamade/fix-a-bug.git && cd fix-a-bug
```

Install the requirements. (Feel free to use a virtual environment!)

```bash
pip install -r requirements.txt
```

Run the tests.

```bash
pytest -sv
```

## Challenge

The code in `fix_me.py` contains four errors that are preventing the test from
passing. Debug and correct each error. As you identify the errors, fill out
a description of the problem and an explanation of the root cause and your fix
in the section below.

### Error 1

**Description:**
The `get_previous()` method does not return zero when there is no previous value.

**Explanation:**
The only situation in which there wouldn't be a previous value is when the method is trying to find the previous value of the first value in the list -- by definition, it doesn't have a previous value. To fix it, I set up a conditional where, if the index of the value is 0, the method should just return 0.

### Error 2

**Description:**

**Explanation:**

### Error 3

**Description:**

**Explanation:**

### Error 4

**Description:**

**Explanation:**
