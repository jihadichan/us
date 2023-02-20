# Restore

- `.apkg` file was split via:

  ```
  split --verbose -b20m UberVocab_1.apkg ubervocab_split.
  ```

- Restore via

  ```
  cat ubervocab_split.a? > ubervocab_1.apkg
  ```

  
