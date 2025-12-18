## 🏗 Architecture Diagram

```text
+----------------------+
|      Linux User      |
|  (Terminal / Shell)  |
+----------+-----------+
           |
           v
+----------------------+
|  Linux File System   |
|----------------------|
|  README.md           |
|  notes.md            |
|  commands.md         |
+----------+-----------+
           |
           v
+----------------------+
|     Git Version      |
|     Control System   |
|----------------------|
| git init             |
| git add              |
| git commit           |
| git push             |
+----------+-----------+
           |
           v
+----------------------+
|     GitHub Remote    |
|   Repository Backup  |
+----------------------+
```
