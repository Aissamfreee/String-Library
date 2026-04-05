# 🔤 clsString Library

## 📌 Overview

`clsString` is a custom C++ utility class designed to simplify and extend string manipulation beyond the standard library.

It provides a wide range of functions for:

* Text formatting
* Case conversion
* Word processing
* Splitting and joining
* Counting and analysis

---

## 🚀 Features

* 🔠 Convert string case:

  * Uppercase / Lowercase
  * Invert letter case
  * Capitalize first letter of each word

* 📊 String analysis:

  * Count words
  * Count letters (capital / small)
  * Count specific characters
  * Count vowels

* ✂️ String processing:

  * Split strings
  * Join strings
  * Trim (left, right, full)

* 🔄 Advanced operations:

  * Reverse words
  * Replace words
  * Remove punctuation

---

## 🛠️ Usage

```cpp
#include "clsString.h"

int main() {
    clsString s("hello world");

    s.UpperFirstLetterOfEachWord();
    cout << s.Value << endl; // Hello World

    cout << clsString::CountWords("C++ is powerful") << endl;

    return 0;
}
```

---

## 🧠 Design Notes

* Supports both:

  * Static methods (utility style)
  * Object methods (OOP style)

* Built using:

  * `std::string`
  * `std::vector`

---

## ⚠️ Limitations

* Not optimized for very large strings
* Uses basic parsing (no regex)
* Depends on ASCII (limited Unicode support)

---

## 📌 Future Improvements

* Add Unicode support
* Improve performance (avoid copies)
* Add regex-based functions
