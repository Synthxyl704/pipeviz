```bash
cat test.txt \
| ./target/release/pipeviz --stage 1 \
| grep INFO \
| ./target/release/pipeviz --stage 2 \
| wc -l
```
