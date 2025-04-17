# test1

## tooltip

This is text that needs a tooltip [<img src="https://www.wppluginsforyou.com/wp-content/uploads/2020/05/tooltips.png" width="15px" />
](## "Tooltip help")

## Note blocks

Notes inside lists don't work
1. blazhble
   edve b
   wewe

   fnrdf

   > blocxk in list
   >

   reg in list

   > [!NOTE]
   > test note

working note:
> [!NOTE]
> The above query inserted the text data into the wiki table without having to do anything to create the embeddings. The vectorizer will automatically create the embeddings for the new row without any intervention from you.  The vectorizer will also automatically update the embeddings for the new row when the data changes.

## script tags (dont work)
<script src="https://gist.github.com/cevian/a118453d929a8ee423d8a7d0ee003ee2.js">
  
</script>


## Highlight lines in code blocks
```python
def hello:
   v = 1
```

```python
def hello:
👀   v = 1
```


```diff
+def hello:
   v = 1
```


<pre><code class="language-python">
def hello:
    v = 1
</code></pre>

use marks:
<pre><code class="language-python">
def hello:
   <mark>v = 1</mark>
</code></pre>


<div class="highlight-source-python"><pre><code>
def hello:
   <mark>v = 1</mark>
</code></pre></div>

https://github.com/cevian/test1/blob/c75db4ab994d976c6298ac2fd212da2fcce63b28/test.py#L2

https://github.com/cevian/test1/blob/6a93c5907b1b47d6675420822be5282c8556e737/test.py#L1-L3

https://github.com/cevian/test1/test.py#L2
