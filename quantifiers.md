- `?` **The preceding characters are optional (0 or 1 times)**

    `use?`

    use a used variabels name is illegal.

- `*` **0 or more times**

    `ab*c`

    ac
    abc
    abbbbc
    adc

- `+` **1 or more times**

    `ab+c`

- `{}` **Specify exact number**

    `ab{4}c` `ab{2,4}c` `ab{2,}c`

- `()` **Multiple patterns**

    `(ab)+`

    abc
    abababc