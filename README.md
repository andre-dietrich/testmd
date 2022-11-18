# testmd

 <p>Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text (Windows).</p>

<p>Press <kbd>Cmd</kbd> + <kbd>C</kbd> to copy text (Mac OS).</p> 

<div itemscope itemtype="https://schema.org/Person">
<span itemprop="name">Jane Doe</span>
<img src="janedoe.jpg" itemprop="image" alt="Photo of Jane Doe"/>

<span itemprop="jobTitle">Professor</span>
<div itemprop="address" itemscope itemtype="https://schema.org/PostalAddress">
<span itemprop="streetAddress">
20341 Whitworth Institute
405 N. Whitworth
</span>
<span itemprop="addressLocality">Seattle</span>,
<span itemprop="addressRegion">WA</span>
<span itemprop="postalCode">98052</span>
</div>
<span itemprop="telephone">(425) 123-4567</span>
<a href="mailto:jane-doe@xyz.edu" itemprop="email">
jane-doe@xyz.edu</a>

Jane's home page:
<a href="http://www.janedoe.com" itemprop="url">janedoe.com</a>

Graduate students:
<a href="http://www.xyz.edu/students/alicejones.html" itemprop="colleague">
Alice Jones</a>
<a href="http://www.xyz.edu/students/bobsmith.html" itemprop="colleague">
Bob Smith</a>
</div>

## mermaid

```mermaid
sequenceDiagram
    participant dotcom
    participant iframe
    participant viewscreen
    dotcom->>iframe: loads html w/ iframe url
    iframe->>viewscreen: request template
    viewscreen->>iframe: html & javascript
    iframe->>dotcom: iframe ready
    dotcom->>iframe: set mermaid data on iframe
    iframe->>iframe: render mermaid
```
