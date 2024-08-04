---
marp: true
theme: gaia
backgroundColor: #FFFFFF;
style: |
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap');
  section {
    font-family: 'Open Sans', sans-serif;
    font-size: 30px;
  }
  h1 {
    color: #008ECE;
    font-size: 50px;
  }
  h2 {
    color: #00A9E0;
    font-size: 35px;
  }
  h3 {
    color: #73787E;
    font-size: 35px; 
  }
paginate: true
math: mathjax
---
<!--- paginate: skip --->

# Project Presentation
## Social Media Data Science
Julia King
University of Konstanz
2024-07-03

---
<!--- paginate: true --->


# Research question and motivation

- track emergence of conspiracy around 15-minute cities on YouTube
- show effect on search results & engagement metrics

## Hypotheses

1. first spike in public interest -> % of conspirative videos increases

2. conspirative videos -> comments more negative

3. video is conspirative -> higher engagement rates per view

---


# Data and methods

1. google trends -> determine spikes in public interest

2. youtube api -> data & comments of most-viewed videos per week

3. by hand -> classify sample of videos as conspirative / non-conspirative

4. supervised text analysis -> classify complete dataset & evaluate

5. LEIA -> obtain sentiments of comments

6. Statistical analysis

---

# Results

![center w:1050](img/google-trends.png)

---


# Conclusion and critique

- google trends shows clear spike -> useful cutoff point
- heavy use of YouTube API -> data retrieval needs scheduling
- second spike unexpected -> potentially counters trend?

## Thank you for listening!



<!--- Style & Formatting --->
<!--- reformat page numbers to include total --->
<style> 
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
section::after {
  content: attr(data-marpit-pagination) ' / ' attr(data-marpit-pagination-total);
}
</style>