# **Limited XE Assembler - CS530 Project #2**

## **Project Overview**
This project is a **two-pass assembler** for the XE variant of the SIC/XE machine architecture. It processes **SIC/XE assembler source files (.sic)** and generates **listing files (.l) and symbol table files (.st)**.

🚀 **Key Features:**
- Implements **all XE features and assembler directives** (up to section 2.3.4).
- **Two-pass assembler logic**:
  - **Pass 1:** Builds the **SYMTAB** and calculates addresses.
  - **Pass 2:** Generates **listing files** and writes the **symbol table** to disk.
- Runs from the **command line** with multiple source files as arguments.
- **Does not generate object code**.

---

## **Project Requirements**
### ✅ **General Requirements**
- Written in **C/C++** (using `gcc/g++`).
- Must use **Makefile** to compile.
- Must include a **README.md** file with usage instructions.
- **Code should be well-commented** for readability.
- Works on **Edoras server** (`Linux` environment).

### 📂 **File Requirements**
| **File Type** | **Description** |
|--------------|----------------|
| `.sic`  | SIC/XE assembler source file |
| `.l`    | SIC/XE listing file (output) |
| `.st`   | SIC/XE symbol table file (output) |
| `Makefile` | Build automation |
| `README.md` | Project documentation |
| `test/` | Test files for validation |

---

## **Installation & Setup**
📌 **Steps to Set Up the Project:**
1. **Clone the repository** (if using Git):
   ```sh
   git clone <repository-url>
   cd <project-folder>
