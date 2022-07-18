---
layout: page
title: Projects
permalink: /evol/projects/
---

# EVOL Research Projects
Below are some of our current and past projects
<a href="/evol/projects/" target="_blank"><img src="/images/logo.jpeg" alt="Evol Logo" style="width:300px;height:117px;" align="right"></a> <br>



# Current Projects

### PaReco: Patched Clones and Missed Patches among the Divergent Variants of a Software Family

<table>
<tr>
<td>  
	
<p align="justify" style="max-width:800px">

Re-using whole repositories as a starting point for new projects is often done by maintaining a variant fork parallel to the original.
      However, the common artifacts between both are not always kept up to date.
      As a result, patches are not optimally integrated across the two repositories, which may lead to sub-optimal maintenance between the variant and the original project.
      A bug existing in both repositories can be patched in one but not the other (we see this as a missed opportunity) or it can be manually patched in both probably by different developers (we see this as effort duplication).
      In this paper we present a tool (named  PaReco) which relies on clone detection to mine cases of missed opportunity and effort duplication from a pool of patches.
      We analyzed 364 (source->target) variant pairs with 8,323 patches resulting in a curated dataset containing 1,116 cases of effort duplication and 1,008 cases of missed opportunities.
      We achieve a precision of 91%, recall of 80%, accuracy of 88%, and F1-score of 85%.
      Furthermore, we investigated the time interval between patches and found out that, on average, missed patches in the target variants have been introduced in the source variants 52 weeks earlier.
      Consequently, PaReco can be used to manage variability in ``time'' by automatically identifying interesting patches in later project releases to be backported to supported earlier releases.</p>
</td>
	<td > <a href="/images/fse_image.jpeg" target="_blank"><img src="/images/fse_image.jpeg" alt="FSE 2022" style="width:300px;height:165px;" align="right"></a></td>

</tr>

</table>