---
title: Our Research
layout: ourresearch
permalink: /ourresearch
---

<style>
    .custom-list {
        font-size: 18px; 
    }
    .img {
        width: 100%; /* Make the image take up 100% of the container's width */
    }
    .div{
        max-width: 400px; /* Set a maximum width for the container on larger screens */
        margin-right: 10px;
        margin-top: 15px;
        float: left;
    }
</style>


<ol class="custom-list">
    <li><a href="#manifold-learning">Manifold Learning</a></li>
    <li><a href="#representation-learning">Representation Learning</a></li>
    <li><a href="#computational-neuroscience-neuroai">Computational Neuroscience/NeuroAI</a></li>
</ol>

### Manifold Learning

---

**If you have a passion for the subjects mentioned and are eager to contribute to cutting-edge research, consider joining our dynamic team through opportunities such as Master's thesis projects, summer internships, or PhD studies. Explore our current open positions:**

<div style="">
 <p style="text-align: center;" ><a href="/contactus" class="btn btn-outline-primary" style="border-radius: 50px; font-size:20px;">Open Positions</a></p>
</div>

<script>
const allPTags = document.querySelectorAll("p");

allPTags.forEach((elem) => {
    if (elem.innerText === "" && elem.childNodes.length === 1 && elem.childNodes[0].tagName === "IMG") {
        elem.parentNode.insertBefore(elem.childNodes[0], elem);
        elem.remove();
    }
});
</script>
