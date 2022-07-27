# Word Count

* Word count finds out the frequency of each word
in a set of documents/files.

* Complete set of solutions are given for Word Count 
  problem using 
	* `groupByKey()` transformation/reducer
	* `reduceByKey()` transformation/reducer

* **BEFORE reduction filter**: 
  You may add `filter()` to remove undesired words

* **AFTER reduction filter**:
  To have a desired final word count as 
  `(word, frequency)`, you may add `filter()` 
  to remove elements where `frequency < N `, 
  where `N` (as an integer) is your threshold
  
--------

<table>
<tr>

<td>
<a href="https://www.oreilly.com/library/view/data-algorithms-with/9781492082378/">
<img src="https://learning.oreilly.com/library/cover/9781492082378/250w/"></a>
</td>

<td>
"... This  book  will be a  great resource for <br>
both readers looking  to  implement  existing <br>
algorithms in a scalable fashion and readers <br>
who are developing new, custom algorithms  <br>
using Spark. ..." <br>
<br>
<a href="https://cs.stanford.edu/people/matei/">Dr. Matei Zaharia</a><br>
Original Creator of Apache Spark <br>
<br>
<a href="https://github.com/mahmoudparsian/data-algorithms-with-spark/blob/master/docs/FOREWORD_by_Dr_Matei_Zaharia.md">FOREWORD by Dr. Matei Zaharia</a><br>
</td>

</tr>   
</table>


--------

# References

[1. Word count from Wiki](https://en.wikipedia.org/wiki/Word_count)

[2. Word Count Example, Spark](https://spark.apache.org/examples.html)