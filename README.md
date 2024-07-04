# RALRP_dataset
# Reconfigurable Assembly Line Reconfiguring Problem Dataset

## Fileformat

The reconfiguration optimization of reconfigurable assembly line problem dataset is composed of two files in ".txt" file format.

“PPGraph_Operation.txt” describes the relevant information of the operation.
The information in each line is as follows：
```yaml
<number of operation> <name of operation> <name of first resource>(process time in `s`) <name of second resource>(process time in `s`)……
```

“PPGraph_Precedence.txt” describes the relevant information of the operation precedence.That represents a process precedence, indicating that the first operation is better than the second operation.
The information in each line is as follows：
```yaml
<first operation> <second operation>.
```

## License

This work is licensed under a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) license.

```yaml
SPDX-License-Identifier: CC-BY-4.0
```
