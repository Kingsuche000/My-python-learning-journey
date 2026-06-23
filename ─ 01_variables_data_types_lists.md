# Python Variables, Data Types and Lists

## Python Variables Beginner Guide

**Source:** Reed Barger - FreeCodeCamp

### What are Variables?

Variables are containers used to store values.

These values can be of different **data types**.

Variables help us store, manipulate, and reference data throughout a program.

### Simple Analogy

Think of a variable as a bottle and the value as the content inside the bottle.

* Bottle = Variable
* Water, Juice, Pepsi = Value

Example:

```python
drink = "Pepsi"
```

Here:

* `drink` is the variable
* `"Pepsi"` is the value

---

## Biology Examples

### Cancer Gene

```python
cancer_gene = "BRCA1"
```

### Tumor Suppressor Gene

```python
gene = "P53"
```

---

## Rules and Conventions for Variables

### Creating Variables

Use the equals sign (`=`) to assign a value to a variable.

```python
gene = "P53"
```

### Snake Case Naming Convention

When a variable name contains multiple words, use underscores (`_`) to separate the words.

```python
cancer_gene_name = "BRCA1"
```

### Python Naming Convention

It is recommended to write variable names in lowercase.

```python
gene_name = "P53"
```

### Valid Variable Names

Variable names can contain:

* Letters
* Numbers
* Underscores (`_`)

Variable names cannot contain:

* Spaces
* Special characters such as `@`, `#`, `%`, `&`

Valid:

```python
gene_name = "P53"
```

Invalid:

```python
gene name = "P53"
```

---

# Common Python Data Types

## Integer (int)

Whole numbers.

```python
number_of_dna_bases = 4
```

Examples:

* 1
* 10
* -5
* 1000

---

## Float (float)

Numbers with decimal points.

```python
fossil_weight = 40.28
```

Examples:

* 3.14
* 0.5
* 40.28

---

## String (str)

A sequence of characters enclosed in quotation marks.

```python
dna = "A molecule composed of nucleotide bases and a sugar-phosphate backbone"
```

Examples:

```python
gene = "P53"
```

```python
protein = "Hemoglobin"
```

---

## Boolean (bool)

Represents either True or False.

```python
dna_is_helix_shaped = True
```

Examples:

```python
cell_is_alive = True
```

```python
virus_detected = False
```

---

## List (list)

An ordered and mutable (changeable) collection of values.

Lists use square brackets `[]`.

```python
cell_types = ["T Cells", "B Cells", "Red Blood Cells", "NK Cells"]
```

### Characteristics

* Ordered
* Mutable (can be changed)
* Can contain multiple values

---

## Tuple (tuple)

An ordered and immutable (unchangeable) collection of values.

Tuples use parentheses `()`.

```python
nucleotide_bases = ("Adenine", "Thymine", "Cytosine", "Guanine")
```

### Characteristics

* Ordered
* Immutable (cannot be changed after creation)

---

# Working with Lists

## Adding Items to a List

Use `.append()` to add an item to the end of a list.

```python
cell_types.append("Macrophages")
```

Result:

```python
["T Cells", "B Cells", "Red Blood Cells", "NK Cells", "Macrophages"]
```

---

## Indexing

Python starts counting from **0**, not 1.

Example:

```python
cell_types = ["T Cells", "B Cells", "NK Cells"]
```

| Index | Value    |
| ----- | -------- |
| 0     | T Cells  |
| 1     | B Cells  |
| 2     | NK Cells |

---

## Replacing Values in a List

Because lists are mutable, values can be changed using their index.

```python
cell_types[2] = "Stem Cells"
```

Result:

```python
["T Cells", "B Cells", "Stem Cells"]
```

---

## Printing Values

### Print an Entire List

```python
print(cell_types)
```

Output:

```python
['T Cells', 'B Cells', 'NK Cells']
```

---

### Print a Specific Value

```python
print(cell_types[2])
```

Output:

```python
NK Cells
```

---

# Key Takeaways

* Variables store values.
* Data is stored using different data types.
* Strings must be enclosed in quotation marks.
* Lists use square brackets `[]` and can be changed.
* Tuples use parentheses `()` and cannot be changed.
* `.append()` adds an item to the end of a list.
* Python indexing starts at `0`.
* `print(variable)` displays the entire variable.
* `print(variable[index])` displays a specific item.
