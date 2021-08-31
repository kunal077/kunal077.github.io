## Blog Post Title From First Header

Due to a plugin called `jekyll-titles-from-headings` which is supported by GitHub Pages by default. The above header (in the markdown file) will be automatically used as the pages title.

If the file does not start with a header, then the post title will be derived from the filename.

This is a sample blog post. You can talk about all sorts of fun things here.

---

### This is a header

#### Some T-SQL Code

```tsql
SELECT This, [Is], A, Code, Block -- Using SSMS style syntax highlighting
    , REVERSE('abc')
FROM dbo.SomeTable s
    CROSS JOIN dbo.OtherTable o;
```

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

<!--<script src="https://gist.github.com/kunal077/66d01de9c017489ab93335f54cce560d.js"></script>
-->

<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fkunal077%2FScalable-Data-Science%2Fblob%2Fmain%2FMisra%2520Greetch%2520and%2520Bloom%2520Filters%2FBloom_Filter.py&style=github&showBorder=on&showLineNumbers=on&showFileMeta=on&showCopy=on"></script>


{% gist 66d01de9c017489ab93335f54cce560d %}


```python
def __init__(self, namedTuple):
    seld.namedTuple = namedTuple
```
