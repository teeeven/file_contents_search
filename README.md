
# 🔍 Keyword Search Tool for Script Files

This Python script is a lightweight and helpful tool designed to search for specific **keywords or phrases** in script files within a specified folder. It helps you rediscover useful code snippets, notes, or documentation buried in `.sql`, `.py`, `.txt`, or `.ps1` files.

---

## 🧠 Why I Built This

As a Data Analyst, I find that this tool helps me foster a good practice of documenting my code while also emphasizing the importance of writing clean and maintainable code, whether that be in an ad hoc SQL Query or a Python data validation script. 

It's not always about reinventing the wheel, but rather about making a useful one that can be used in multiple projects. 

I think that this is a good practice to have in any field, and as someone who benefits from open source code, I think it is important to give back to the community even in such a small way.

---

## 🚀 Features

- ✅ Search for any keyword or phrase across multiple files
- ✅ Returns line numbers and content for every match
- ✅ Case-insensitive matching
- ✅ Supports multiple file extensions (`.sql`, `.ps1`, `.py`, `.ipynb`, `.txt`)
- ✅ Fun "DOH!" Homer Simpson ASCII if no matches are found 😉

---

## 🛠 How to Use

1. **Clone this repo** or copy the script into your environment.
2. Set the `folder_path` variable to the folder you want to search.
3. Set the `keyword` variable to your desired search term.
4. Run the script in any standard Python environment.

```python
# Example
folder_path = r'C:\Users\yourname\Documents\Scripts'
keyword = 'JOIN'
```

---

## 📂 File Types Supported

- `.sql` – SQL query files  
- `.ps1` – PowerShell scripts  
- `.py` – Python scripts  
- `.txt` – Notes, logs, or scratch files  
- `.ipynb` – Jupyter Notebooks (as plain text)

You can customize `extensions_to_search` to include more or fewer types.

---

## 🤖 Requirements

- Python 3.x
- No external packages needed — uses only the built-in `os` module

---

## 🧩 Example Output

```
Keyword found in report_script.sql:
  Line 15: LEFT JOIN vendor_master v on a.id = v.vendor_id
  Line 16: -- Revisit later to optimize vendor join from LEFT to INNER
--------------------------------------------------------------------------------
```

Or, if nothing is found:

```
                                 __ 
                      _ ,___,-'",-=-. 
            __,-- _ _,-'_)_  (""`'-._\ `. 
         _,'  __ |,' ,-' __)  ,-     /. | 
       ,'_,--'   |     -'  _)/         `\ 
     ,','      ,'       ,-'_,`           : 
     ,'     ,-'       ,(,-(              : 
          ,'       ,-' ,    _            ; 
         /        ,-._/`---'            / 
        /        (____)(----. )       ,' 
       /         (      `.__,     /\ /, 
      :           ;-.___         /__\/| 
      |         ,'      `--.      -,\ | 
      :        /            \    .__/ 
       \      (__            \    |_ 
        \       ,`-, *       /   _|,\ 
         \    ,'   `-.     ,'_,-'    \ 
        (_\,-'    ,'\")--,'-'       __\ 
         \       /  // ,'|      ,--'  `-. 
          `-.    `-/ \'  |   _,'         `. 
             `-._ /      `--'/             \ 
     -DOH-      ,'           |              \ 
               /             |               \ 
            ,-'              |               / 
           /                 |             -' 
```

---

## 🙌 Contributing

Ideas, improvements, or ASCII art upgrades are welcome! Feel free to fork and PR.

---

## 📄 License

MIT License

---
