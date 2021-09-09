# assignment2-Chaparala
# shashanka ravi chaparala
## vijayawada
Vijayawada is a city in the **southeast** Indian state of **Andhra Pradesh**. It's known for the ornate **Kanaka Durga Temple**, which sits atop a hill overlooking the **city**.

****
## Vijayawada to maryville

1. Directions for maryville.
   1. start in vijayawada drive for about 25 hours.
   2. Vijayawada to delhi.
   3. Delhi to chicago.
   4. Chicago to kansas.
   5. kansas to maryville.
        
2. Finally maryville.

****

### Products to be packed for enjoyment

- Casual sneakers.
- Heavy jacket.
- Camera and lens.
- Backpack.
- cash.
- extra specs.

Take me to [AboutMe](AboutMe.md)

---
## Indian Resturant
This is the Menu, location and price table

| Menu		    | Location	  | Price    |
| ------------- | --------    | -------- |
| biryani	    | Indian pot  | $1.50    |
| Butter naan	| Indian pot  | $1.70    |
| Dal           | Indian pot  | $1.20    |
| Mandi	        | Indian pot  | $1.60    |

---

---
## Pithy Quotes

As Albert Einstein said:

> Two things are infinite: the universe and human stupidity; and I'm not sure about the universe.

> So many books, so little time

---

## Code fencing

Aho–Corasick algorithm from **String Processing**

>The Aho-Corasick algorithm can be used to efficiently search for multiple patterns in a large blob of text, making it a really useful algorithm in data science and many other areas.
>Efficient string algorithms play an important role in many data science processes. Often they are what make such processes feasible enough for practical use.

Aho–Corasick algorithm [Reference_link](https://en.wikipedia.org/wiki/Aho%E2%80%93Corasick_algorithm)

code for Aho–Corasick Algorithms

```

void add_string(string const& s) {
    int v = 0;
    for (char ch : s) {
        int c = ch - 'a';
        if (trie[v].next[c] == -1) {
            trie[v].next[c] = trie.size();
            trie.emplace_back();
        }
        v = trie[v].next[c];
    }
    trie[v].leaf = true;
}
```


Aho–Corasick algorithm [Code_link](https://cp-algorithms.com/string/aho_corasick.html)