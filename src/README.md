## Comparison sorts

| Algorithm              | File                 | Time               | Space    |
|------------------------|----------------------|--------------------|----------|
| [Bubble sort][01_a]    | [1][01_1]            | Θ(n^2)             | Θ(1)     |
|  Cocktail sort         | [1][02_1]            | O(n^2), Ω(n)       | Θ(1)     |
|  Gnome sort            | [1][03_1]            | O(n^2), Ω(n)       | Θ(1)     |
| [Heapsort][04_a]       | [1][04_1]            | Θ(n log n)         | Θ(1)     |
| [Insertion sort][05_a] | [1][05_1]            | O(n^2), Ω(n)       | Θ(1)     |
| [Merge sort][06_a]     | [1][06_1], [2][06_2] | Θ(n log n)         | Θ(n)     |
|  Odd-even sort         | [1][07_1]            | O(n^2), Ω(n)       | Θ(1)     |
| [Quicksort][08_a]      | [1][08_1]            | O(n^2), Ω(n log n) | O(log n) |
| [Selection sort][09_a] | [1][09_1]            | O(n^2), Ω(n)       | Θ(1)     |

  [01_a]: http://www.growingwiththeweb.com/2014/02/bubble-sort.html
  [01_1]: https://github.com/Tyriar/js-sorting/blob/master/src/bubble-sort.js
  [02_1]: https://github.com/Tyriar/js-sorting/blob/master/src/cocktail-sort.js
  [03_1]: https://github.com/Tyriar/js-sorting/blob/master/src/gnome-sort.js
  [04_a]: http://www.growingwiththeweb.com/2012/11/algorithm-heapsort.html
  [04_1]: https://github.com/Tyriar/js-sorting/blob/master/src/heapsort.js
  [05_a]: http://www.growingwiththeweb.com/2012/11/algorithm-insertion-sort.html
  [05_1]: https://github.com/Tyriar/js-sorting/blob/master/src/insertion-sort.js
  [06_a]: http://www.growingwiththeweb.com/2012/12/algorithm-quicksort.html
  [06_1]: https://github.com/Tyriar/js-sorting/blob/master/src/merge-sort.js
  [06_2]: https://github.com/Tyriar/js-sorting/blob/master/src/merge-sort-bottom-up.js
  [07_1]: https://github.com/Tyriar/js-sorting/blob/master/src/odd-even-sort.js
  [08_a]: http://www.growingwiththeweb.com/2012/12/algorithm-quicksort.html
  [08_1]: https://github.com/Tyriar/js-sorting/blob/master/src/quicksort.js
  [09_a]: http://www.growingwiththeweb.com/2013/12/selection-sort.html
  [09_1]: https://github.com/Tyriar/js-sorting/blob/master/src/selection-sort.js

## Distribution sorts

| Algorithm              | File                 | Time               | Space    |
|------------------------|----------------------|--------------------|----------|
| [Counting sort][d01_a] | [1][d01_1]           | Θ(n + k)           | Θ(n + k) |

  [d01_a]: http://www.growingwiththeweb.com/2014/05/counting-sort.html
  [d01_1]: https://github.com/Tyriar/js-sorting/blob/master/src/counting-sort.js