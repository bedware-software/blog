---
bookHidden: true
---

```java {linenos=inline,hl_lines=[2,"8-10"],linenostart=199}
public int toInt() {
    return levelInt;
}

/**
* Returns the string representation of this Level.
*/
public String toString() {
    return levelStr;
}
```

{{< mermaid class="optional" >}}
stateDiagram-v2
    State1: The state with a note
    note right of State1
        Important information! You can write
        notes.
    end note
    State1 --> State2
    note left of State2 : This is the note to the left.
{{< /mermaid >}}

