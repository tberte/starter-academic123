---
title: An example title
summary: Here we describe how to add a page to your site.
date: "2018-06-28T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `assets/media/` folder).
header:
  caption: ""
  image: ""
---
<h1> T1 - Heavy 6 min ca 20 reps per </h1>
<p id="firstId"></p>

<h1> T2 - medium 12 min ca 30 reps per </h1>
<p id="secId"></p>

<h1> T3 - light 15 min ca. 60 reps  per</h1>
<p id="thirdId"></p>

<script language="JavaScript">

function firstRandom() {
    var firstRandom = [
"snatch",
"Clean and Jerk",
"HSPU",
"Heavy squat"
];
return firstRandom[Math.floor((Math.random() * 3.99))];
}

function secRandom() {
    var secRandom = [
"squat",
"deadlift",
"pushpress",
"row",
"push-up",
"pull-up"
];
return secRandom[Math.floor((Math.random() * 5.99))];
}

function thirdRandom() {
    var thirdRandom = [
"DU",
"burpee",
"hollowhold",
"superman",
"kbswing",
"sprint",
"airsqaut",
"bandpull",
"cuban press"
];
return thirdRandom[Math.floor((Math.random() * 8.99))];
}

document.getElementById("firstId").innerHTML = firstRandom();
document.getElementById("secId").innerHTML = secRandom();
document.getElementById("thirdId").innerHTML = thirdRandom();
</script>