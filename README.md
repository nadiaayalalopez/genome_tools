# genome_tools
My genomics scripts NYAS workshop work

Example usage:

```
echo "name.count"
for fasta in data/*.fa; do
  count=$( bash count_seq.sh $fasta )
  echo "$fasta,$count"
done >> my_file.csv
```
