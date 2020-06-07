# Testcases

There are 5 different test cases present, going from as small as 100 queries to as large as 100k. In final evaluation, we'll go for a million queries (at least), but since that would just increase the repo size unnecessarily, we have skipped that in sample testcases. It's your job to make sure your code work for (very) large testcases too.

- Bulkload
	+ Always the first (and only first) line of query file.
	+ Starts with `BULKLOAD`.
	+ The second string is the path of data file you need to bulk load from, and you'll need to change that according to your system.  

- INSERT/QUERY
	+ Process all queries (insert/search) one after the other.
	+ For `QUERY`, you of course need to answer as per the current state of the tree.