# copy-directory-tool

A file/directory copy utility with a simple console progress bar, built while
learning Java I/O.

> Built within my first ~4–5 months of learning Java (a coding course). Kept as a record of progress, not as polished production code.

## Run
```bash
find src -name '*.java' | xargs javac -d out
java -cp out copydir.CopyFilesImpl
```
`CopyFilesImpl` is the entry point. Run it against paths you own.

## Note
`Testing.java` is a leftover demo harness — it compiles but is not the intended
entry point.
