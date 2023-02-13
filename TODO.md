## Cleaning
### Jouyou Kanji
- The last column and first columns have no names 
    - The first column is an index so I used `index_col` in `pd.read_csv` to use the first column as an index
- The last column has no data
    - Solution is to drop the last column
- Grade should be categorical in the order S,5,4,3,2,1
- Year is float
    - It should be integer
- Radicals: Transform the radicals into their more common shapes

### Exploratory
- For kanjis added, which grades were they for
    - Also did they have a kyuujitai (old form)
- Most common radicals

