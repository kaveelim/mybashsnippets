# Awk code snippets

## To change column(s) name in tab separated file.
```
# To add prefix/suffix to column 3
awk 'FNR==1{$3="prefix"$3"suffix";OFS="\t"}1' in_file.tsv

```
