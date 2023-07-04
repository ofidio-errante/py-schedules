# Directory strategy

## Codebase

The codebase of the project is contained in the `src` parent folder.
Inside `src` there can be a number of subdirectories which should follow two guidelines:

* Each directory should be _atomic_, meaning that it should contain the minimum implementation possible.
* Short, descriptive `snake_case` names are preferable.

For example, a project that implements a base class `Person` inherited by classes `Student` and `Teacher` might look as:

```text
src
├── person
│   └── base.py
├── student
│   └── student.py
└── teacher
    └── teacher.py
```
