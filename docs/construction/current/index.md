<!-- index.md  0.0.4                UTF-8                      dh:2020-10-29
     ----1----|----2----|----3----|----4----|----5----|----6----|----7----|--*
     construction structure, manifest, and job jar at
     <https://orcmid.github.io/docEng/construction/current/current.txt>
     -->
# DOCENG PROJECT DOCS: CURRENT MARKDOWN TREATMENT

This page demonstrates the layout and Markdown effects supported by the
current (default), template's rendering of <https://orcmid.github.io/docEng/>
pages.  This page is rendered at
<https://orcmid.github.io/docEng/construction/current/>.  It is authored
at
<https://github.com/orcmid/docEng/blob/main/docs/construction/current/index.md>.

For details of how the default, no-template presentation was experienced and
minimum expectations for other templates, see the
[plain rendering confirmation](../plain/).

## TEXT TREATMENT

### Paragraph Flow

The flow of paragraph text from line-to-line and spacing
from one paragraph to the next is presented in this and
the next paragraph.

There should be one blank line between these two paragraphs.
If the browser view is widened or narrowed, the text flow
should change to keep all of the text in view.

The above text and the titles were produced with the following Markdown text.
```text
## TEXT TREATMENT

### Paragraph Flow

The flow of paragraph text from line-to-line and spacing
from one paragraph to the next is presented in this and
the next paragraph.

There should be one blank line between these two paragraphs.
If the browser view is widened or narrowed, the text flow
should change to keep all of the text in view.
```

### Text Emphasis

Text can be **bold**, *italic*, and <strike>struckthrough</strike>.

There are ***comb**inations* and _altermatives_.

```text
### Text Emphasis

Text can be **bold**, *italic*, and <strike>struckthrough</strike>.

There are ***comb**inations* and _altermatives_.
```

### Special Text Features

A special text formatting is `code-style` or `typewriter`.

Characters used for special markdown purposes can be **escaped** with "\\"
to simply appear as text characters:

   \\ \` \* \_ \# \+ \- \. \! \( \[ \{ \} \] \)

For Markdown pages in the repository (but not GitHub pages) emoji are defined
at the [emoji cheat sheet](https://www.webfx.com/tools/emoji-cheat-sheet/),
including :smile: :boom: :heart: :kiss: :floppy_disk: :mouse:

```text
### Special Text Features

A special text formatting is `code-style` or `typewriter`.

Characters used for special markdown purposes can be **escaped** with "\\"
to simply appear as text characters:

   \\ \` \* \_ \# \+ \- \. \! \( \[ \{ \} \] \)

For Markdown pages in the repository (but not GitHub pages) emoji are defined
at the [emoji cheat sheet](https://www.webfx.com/tools/emoji-cheat-sheet/),
including :smile: :boom: :heart: :kiss: :floppy_disk: :mouse:
```

## HEADERS AND LINKS

There are six levels of headers supported in Markdown (and HTML)

---

# H1 Header

The largests header is generally used for the overall title.

## H2 Header

Decreasing size and strength reflect hierarchical nesting as desired.

### H3 Header

#### H4 Header

Generally, H4 is the same size as normal text, but still distinguished
as a header.

##### H5 Header

###### H6 Header

<small>The smallest header levels could use some smaller text.
</small>

---

```text
---

# H1 Header

The largests header is generally used for the overall title.

## H2 Header

Decreasing size and strength reflect hierarchical nesting as desired.

### H3 Header

#### H4 Header

Generally, H4 is the same size as normal text, but still distinguished
as a header.

##### H5 Header

###### H6 Header

<small>The smallest header levels could use some smaller text.
</small>

---
```

<!-- 0.0.4 2021-10-29T22:21Z Smoothing, change "master" to "main"
     0.0.3 2021-02-20T01:48 eliminate the stacking of <small>...</small> in
           the code block on H6.
     0.0.2 2021-02-16T01:09Z transposing to docEng for further development.
     0.0.1 2019-11-24-10:59 version 0.0.4 of this page in the Miser Project
           docs/ repository

           *** end of docs/construction/current/index.md ***
           -->
