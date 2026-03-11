# Teacher Resources

This folder contains **global**, **reusable**, and **teacher-facing** curriculum materials that support all CS1 units. These resources are not tied to a single lesson or unit. Lesson-specific files (slides, code, activities, assessments) live inside the lesson folders (e.g., `CS1/Unit-01/U01L03/`).

This folder is meant to help teachers:
- prepare for instruction  
- reference onboarding materials  
- access editable versions of resources  
- download printable handouts  
- locate troubleshooting guides, rubrics, and shared tools  

---

## 📁 File Naming Conventions

To keep materials consistent and easy to navigate, all files in this folder follow a clear suffix-based system.

### 🎒 Teacher-Facing (TF)
**TF = Teacher-Facing**

Use this suffix for:
- editable files  
- detailed versions  
- teacher notes  
- annotated documents  
- reference guides  

Typical formats:
- `.docx` (editable)
- `.pdf` (stable display)

**Examples:**
- `Coding-Editor-Guide-TF.docx`  
- `Coding-Editor-Guide-TF.pdf`  

---

### 🎓 Student-Facing (SF)
**SF = Student-Facing**

Use this for simplified handouts designed for students.  
These are typically **PDF only** so formatting is preserved.

**Examples:**
- `Coding-Editor-Guide-SF.pdf`

---

## 🧭 No Unit Prefixes in This Folder

Files in `Teacher-Resources` must **NOT** use unit prefixes (U00, U01, etc.).  
They support *multiple* units and do not belong to a specific lesson.

Correct:
```
Coding-Editor-Guide-TF.docx
Naming-Conventions-TF.pdf
```

Incorrect:
```
U00-Coding-Editor-Guide.pdf
U01L03-Troubleshooting.docx
```

---

## 📚 Suffixes Used in Lesson Folders (for reference)

While this folder only uses **TF** and **SF**, lesson folders use additional suffixes to organize materials:

- **SD** = Slide Deck (PowerPoint, PDF, Google Slides link)  
- **CODE** = Code files (MKCD, TXT, PY)  
- **VOCAB** = Vocabulary activity  
- **FA** = Formative Assessment  
- **SA** = Summative Assessment  
- **KEY** = Answer Key / Solutions  
- **REF** = Reference Sheet (cheatsheet, shortcuts, syntax guide)

Lesson folder example:
```
U01L03-SD.pptx
U01L03-SD.pdf
U01L03-CODE.mkcd
U01L03-CODE.txt
U01L03-FA.pdf
U01L03-KEY.pdf
```

---

## 🔗 How Lesson Folders Reference Teacher-Resources

Lessons link to TF/SF materials rather than duplicating files.

Example inside a lesson README:

```
### Resources Needed
- Student Handout:  
  → ../../Teacher-Resources/Coding-Editor-Guide-SF.pdf

- Teacher Guide:  
  → ../../Teacher-Resources/Coding-Editor-Guide-TF.pdf
```

This keeps your repo clean and prevents multiple copies.

---

## 🧺 What Belongs in This Folder

Suggested items to store here:

- onboarding instructions  
- login directions  
- naming conventions  
- MakeCode troubleshooting guide  
- project rubrics  
- reusable checkoff templates  
- logic puzzles  
- planning documents  
- printable reference sheets  
- substitute plans  
- teacher training materials  

Anything that applies across multiple units belongs here.

---

## 🎉 Final Notes

This folder serves as the **shared backbone** of the CS1 curriculum.  
All teachers using this repo should check here first when preparing a lesson, troubleshooting an issue, or looking for reusable templates.

TF/SF suffixes, no unit prefixes, and consistent naming conventions ensure that the curriculum remains clean, scalable, and easy to navigate for many years.
