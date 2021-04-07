---
title: Training
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

<head>
<style>
p {display:inline}
</style>
</head>

<h3> Day1 </h3>
<p>T1 leg</p>
<p>AMRAP 20/4 RFQ/T/Chipper with 40(10/R) reps each</p>

<p id ="pullT31"></p>
<p id ="pullT32"></p>
<p id ="core"></p>

<h3> Day 2  </h3>
<p>T2 push find 10RM</p>
<p>AMRAP 20/4 RFQ/T/Chipper with 40 reps each (20 for T2)</p>

<p> 5 /round T2 Push</p>
<p id ="pushT31"></p>
<p id ="pushT32"></p>
<p id ="core"></p>

<h3> Day 3 </h3>
<p>T1 pull</p>
<p>AMRAP 20/4 RFQ/T/Chipper with 40(10/R) reps each</p>

<p id ="pullT31"></p>
<p id ="pullT32"></p>
<p id ="core"></p>
<p id="mono"></p>

<h3> Day 4  </h3>
<p>T2 leg find 10RM</p>
<p>T2 pull find 10RM </p>
<p>AMRAP 20/4 RFQ/T/Chipper with 40 reps each (20 for T2)</p>

<p> 5 /round T2 leg</p>
<p> 5 /round T2 pull</p>
<p id ="core"></p>

<h3> Day 5 </h3>
<p>T1 push</p>
<p>AMRAP 20/4 RFQ/T/Chipper with 40(10/R) reps each</p>

<p id ="pushT31"></p>
<p id ="pushT32"></p>
<p id ="core"></p>

<h3> Day 6 </h3>
<p>AMRAP 40</p>

<p id ="pushT31"></p>
<p id ="pushT32"></p>
<p id ="pullT31"></p>
<p id ="pullT32"></p>
<p id ="core"></p>

<script language="JavaScript">




function pullT31() {
    var pullT31 = [
"Squat clean",
"hang SQ clean",
"Alt. single leg deadlift",
"deadlift",
"pendlay row",
"upright row",
"gorilla row",
"bicep curl",
"pull-up",
"deadlift high pull"
];
return pullT31[Math.floor((Math.random() * 9.99))];
}

function pullT32() {
    var pullT32 = [
"Squat clean",
"hang SQ clean",
"Alt. single leg deadlift",
"deadlift",
"pendlay row",
"upright row",
"gorilla row",
"bicep curl",
"pull-up",
"deadlift high pull"
];
return pullT32[Math.floor((Math.random() * 9.99))];
}


function core() {
    var core = [
"burpee",
"farmer carry",
"houtie bear crawl",
"sit-up",
"plank",
"plank flow",
"hollow rock",
"superman",
"good morning",
"T2B",
"candlestick",
"v-ups",
"quadruped houtie crosslift",
];
return core[Math.floor((Math.random() * 12.99))];
}

function pushT31() {
    var pushT31 = [
"snatch",
"jerk",
"thruster",
"push up",
"front lean rest",
"ohp",
"dips"
];
return pushT31[Math.floor((Math.random() * 6.99))];
}

function pushT32() {
    var pushT32 = [
"snatch",
"jerk",
"thruster",
"push up",
"front lean rest",
"ohp",
"dips"
];
return pushT32[Math.floor((Math.random() * 6.99))];
}

function mono() {
    var mono = [
"DU",
"run"
];
return mono[Math.floor((Math.random() * 1.99))];
}

document.getElementById("pullT31").innerHTML = pullT31();
document.getElementById("pullT32").innerHTML = pullT32();
document.getElementById("pushT31").innerHTML = pushT31();
document.getElementById("pushT32").innerHTML = pushT32();
document.getElementById("core").innerHTML = core();
document.getElementById("mono").innerHTML = mono();

</script>