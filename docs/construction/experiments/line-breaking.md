<!-- line-breaking.md  0.0.1        UTF-8                          2023-07-25
     ----1----|----2----|----3----|----4----|----5----|----6----|----7----|--*

                    SIMPLE EXPERIMENT ABOUT LINE-BREAKING
     -->

# Line-Breaking Experiment

This page simply tests how line-endings
work from one line to the next
and how text flow is provided automatically
among the lines that are typed with spacing
between.

```text
This page simply tests how line-endings
work from one line to the next
and how text flow is provided automatically
among the lines that are typed with spacing
between.
```

You can see the difference between the Markdown layout, above, and the way
that the text has been flowed just above.

Here's another.

This paragraph simply tests how line-continuations\
signalled by \\ line-ends\
provoke hard line breaks that inhibit\
text-flowing wit the next line.

The above was achieved (or not) by

```text
This paragraph simply tests how line-continuations\
signalled by \\ line-ends\
provoke hard line breaks that inhibit\
text-flowing wit the next line.
```

Note that this use of \\ is exactly the opposite of how that line-ending is
used in C Language texts.

The other way to do the hard line-breaks is with
two spaces at the end of a line.  That
is difficult to handle
in text editors
and the intention can be
thwarted when the text is
saved with the extra spaces
dropped.

```text
The other way to do the hard line-breaks is with
two spaces at the end of a line.  That
is difficult to handle
in text editors
and the intention can be
thwarted when the text is
saved with the extra spaces
dropped.
```

That all of the lines above apart from the last one have two spaces at the
end is not very legible.

So endeth this experiment.

<!-- ----1----|----2----|----3----|----4----|----5----|----6----|----7----|--*

     0.0.1 2023-07-25T00:44Z Corrected hard line-break \ case
     0.0.0 2023-07-25T00:24Z Initial Test Draft

                   *** end of line-breaking.md ***
     -->
