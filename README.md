# read_excel_crystal
Benchmark xlsx reader with crystal

# how does it works?
```bash
$ clone repo
$ cd read_excel_cr
$ shard install
$ crystal run main.cr for standar execution
$ crystal build main.cr --release for compile and create executable
$ ./main
```

# Bench
crystal 1.10.1

**Standard version**
```
               user     system      total        real
parser:    1.033945   0.011712   1.045657 (  1.046572)
```

**Compiled version**
```
               user     system      total        real
parser:    0.573927   0.000000   0.573927 (  0.573958)
```