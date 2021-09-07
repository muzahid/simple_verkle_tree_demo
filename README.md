CSV Data from https://raw.githubusercontent.com/tonmcg/County_Level_Election_Results_12-16/master/2016_US_County_Level_Presidential_Results.csv (via wget into the checkout directory).

After that, I ran:

```
python2 create_verkle_tree.py
```

That created JSON documents for each voting district.

After that, I ran:

```
python2 update_verkle_tree_hashes.py
```

That one just runs in a loop. This is only a proof of concept.