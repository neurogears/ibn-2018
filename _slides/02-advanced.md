---
layout: slides
title: Advanced Concepts
permalink: /slides/advanced/
---

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

## Bonsai
![Bonsai](../../assets/images/bonsai-circle.svg)

[bonsai-rx.org](http://bonsai-rx.org)

### Advanced Concepts

---

###### Merge

![Merge](../../assets/images/merge.svg)

---

###### Amb

![Amb](../../assets/images/amb.svg)

---

###### Concat

![Concat](../../assets/images/concat.svg)

---

### Higher-Order Operators

![Concatenate video files using first order operators](../../assets/images/concatfile-firstorder.svg)

--

###### Enumerate Files

![Enumerate all file names in a folder](../../assets/images/concatfile-enumeratefiles.svg)

--

###### Create Observable

![Create sequences of frames from file names](../../assets/images/concatfile-observable.svg)

--

###### Concat

![Combine all sequences of frames into a single sequence](../../assets/images/concatfile-combine.svg)

---

<!-- .element: data-transition="default none" -->
###### Transform

![Transform](../../assets/images/transform.svg)

--

<!-- .element: data-transition="none default" -->
###### Select

![Select](../../assets/images/select.svg)

---

###### SelectMany

![SelectMany](../../assets/images/selectmany.svg)

---

### Representing discrete states

**State**
<!-- .element: class="fragment" data-fragment-index="1" style="display: inline-block; vertical-align: middle;" -->

<small>"the particular condition that someone or something is in at a specific time"</small>
<!-- .element: class="fragment" data-fragment-index="1" style="display: inline-block; vertical-align: middle;" -->
<small>"a physical condition as regards internal or molecular form or structure"</small>
<!-- .element: class="fragment" data-fragment-index="2" style="display: inline-block; vertical-align: middle;" -->

**Event**
<!-- .element: class="fragment" data-fragment-index="3" style="display: inline-block; vertical-align: middle;" -->

<small>"a thing that happens or takes place, especially one of importance"</small>
<!-- .element: class="fragment" data-fragment-index="3" style="display: inline-block; vertical-align: middle;" -->
<small>"a single occurrence of a process, e.g. the ionization of one atom"</small>
<!-- .element: class="fragment" data-fragment-index="4" style="display: inline-block; vertical-align: middle;" -->

<small>source: <a href="https://en.oxforddictionaries.com/">Oxford English Living Dictionaries</a></small>
<!-- .element: class="fragment" data-fragment-index="1" style="display: inline-block; position: absolute; right: 0px;" -->

--

#### Working Definition

**State** → Extended

**Event** → Punctate

---

<!-- .element: data-transition="default none" -->
![TriggeredWindow](../../assets/images/triggeredwindow-states-hidden.svg)

--

<!-- .element: data-transition="none default" -->
![TriggeredWindow](../../assets/images/triggeredwindow-states.svg)

---

<!-- .element: data-transition="default none" -->
![SelectMany](../../assets/images/selectmany-events-hidden.svg)

--

<!-- .element: data-transition="none none" -->
![SelectMany](../../assets/images/selectmany-events-in.svg)

--

<!-- .element: data-transition="none none" -->
![SelectMany](../../assets/images/selectmany-states.svg)

--

<!-- .element: data-transition="none default" -->
![SelectMany](../../assets/images/selectmany-events-out.svg)

---

###### Buffer

![Buffer](../../assets/images/buffer.svg)

---

###### TriggeredBuffer

![TriggeredBuffer](../../assets/images/triggeredbuffer.svg)

---

###### Window

![Window](../../assets/images/window.svg)

---

###### TriggeredWindow

![TriggeredWindow](../../assets/images/triggeredwindow.svg)

---

### Sharing observable sequences

![Branching](../../assets/images/branching-simple.svg)
<!-- .element: style="display: inline-block; vertical-align: top;" -->
![Subjects (Publish)](../../assets/images/subjects-publish-simple.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: top; padding-left: 120px;" -->

--

### Sharing observable sequences

![Publish](../../assets/images/publish.svg)
<!-- .element: style="display: inline-block; vertical-align: top;" -->
![Replay](../../assets/images/replay.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: top; padding-left: 40px;" -->

--

### Sharing observable sequences

![Subjects (Publish)](../../assets/images/subjects-publish.svg)
<!-- .element: style="display: inline-block; vertical-align: top; padding-left: 120px;" -->
![Subjects (Replay)](../../assets/images/subjects-replay.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: top; padding-left: 120px;" -->

</script>
</section>