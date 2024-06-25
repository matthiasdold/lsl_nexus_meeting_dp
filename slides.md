---
theme: seriph
background: "dark"
highlighter: shiki
class: text-center
lineNumbers: false
info: |
  ## Slidev presentation
drawings:
  persist: false
transition: slide-left
title: Dareplane update 
---


<div id='title_text'>LSL case on:</div>

# Dareplane

<!-- <div id="spacer"></div> -->

**Da**ta-driven **re**search **pla**tform for **ne**uro-technology

<!-- #### Matthias Dold - PIs: Michael Tangermann, Mark Janssen -->

  <!-- NOTE: './public' is availabe as './'-->

<div id='title_brain'></div>
<div id='title_pc'></div>
<div class='eeg_background_wrapper'>
  <div id='eeg_bg'>
  </div> 
</div>

<div class='control_background_wrapper'>
  <div id='control_bg'>
  </div> 
</div>
<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->
<div id="full_footer">
  <img src="/all_logos.svg">
</div>

---
src: ./pages/dp_concept.md
---

---
src: ./pages/dp_web.md
---

---
src: ./pages/dp_performance.md
---

---
src: ./pages/use_case.md
---


# Summary

![dareplane_logo](/single_dareplane_logo_dark_bg.svg)

<table>
  <tr>
    <td><uiw-github /></td>
    <td>Dareplane is released at <a href="https://github.com/bsdlab/Dareplane">https://github.com/bsdlab/Dareplane</a></td>
  </tr>
  <tr>
    <td><emojione-stopwatch /></td>
    <td>Performance seems sufficient for testing a broad range of control approaches</td>
  </tr> 
  <tr>
    <td><ri-loop-right-line /></td>
    <td>Full closed-loop proof of concept done</td>
  </tr>
</table>


<style>
svg {
  width: 120%;
  height: auto;
}
p {
height: 10%;
img {
  position: absolute;
  right: 5%;
  top: 5%;
  width: 30%;
  height: auto;
}
}
</style>

