<!-- ---
layout: page
title: project 1
description: a project with a background image
img: assets/img/12.jpg
importance: 1
category: work
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="\_projects\quarto_files\folktales\figure-html\0c2c92b6-1-hrustall-eQVUSm2peDc-unsplash.jpg" class="img-fluid figure-img" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>
 -->

<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en"><head>

<meta charset="utf-8">
<meta name="generator" content="quarto-1.2.253">

<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">


<title>Cultural Stories and Values</title>
<style>
code{white-space: pre-wrap;}
span.smallcaps{font-variant: small-caps;}
div.columns{display: flex; gap: min(4vw, 1.5em);}
div.column{flex: auto; overflow-x: auto;}
div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
ul.task-list{list-style: none;}
ul.task-list li input[type="checkbox"] {
  width: 0.8em;
  margin: 0 0.8em 0.2em -1.6em;
  vertical-align: middle;
}
</style>


<script src="_project/quarto_files/folktales/libs/clipboard/clipboard.min.js"></script>
<script src="_project/quarto_files/folktales/libs/quarto-html/quarto.js"></script>
<script src="_project/quarto_files/folktales/libs/quarto-html/popper.min.js"></script>
<script src="_project/quarto_files/folktales/libs/quarto-html/tippy.umd.min.js"></script>
<script src="_project/quarto_files/folktales/libs/quarto-html/anchor.min.js"></script>
<link href="_project/quarto_files/folktales/libs/quarto-html/tippy.css" rel="stylesheet">
<link href="_project/quarto_files/folktales/libs/quarto-html/quarto-syntax-highlighting.css" rel="stylesheet" id="quarto-text-highlighting-styles">
<script src="_project/quarto_files/folktales/libs/bootstrap/bootstrap.min.js"></script>
<link href="_project/quarto_files/folktales/libs/bootstrap/bootstrap-icons.css" rel="stylesheet">
<link href="_project/quarto_files/folktales/libs/bootstrap/bootstrap.min.css" rel="stylesheet" id="quarto-bootstrap" data-mode="light">
<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.3.6/require.min.js" integrity="sha512-c3Nl8+7g4LMSTdrm621y7kf9v3SDPnhxLNhcjFJbKECVnmZHTdo+IRO05sNLTH/D3vA6u1X32ehoLC7WFVdheg==" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js" integrity="sha512-bLT0Qm9VnAYZDflyKcBaQ2gg0hSYNQrJ8RilYldYQ1FxQYoCLtUjuuRuZo+fjqhx/qtq/1itJ0C2ejDxltZVFg==" crossorigin="anonymous"></script>
<script type="application/javascript">define('jquery', [],function() {return window.jQuery;})</script>


</head>

<body class="fullcontent">

<div id="quarto-content" class="page-columns page-rows-contents page-layout-article">

<main class="content" id="quarto-document-content">

<header id="title-block-header" class="quarto-title-block default">
<div class="quarto-title">
<h1 class="title">Cultural Stories and Values</h1>
</div>



<div class="quarto-title-meta">

    
  
    
  </div>
  

</header>

<div class="quarto-figure quarto-figure-center">
<figure class="figure">
<p>{% include figure.html path="_project/quarto_files/folktales/figure-html/0c2c92b6-1-hrustall-eQVUSm2peDc-unsplash.jpg" class="img-fluid figure-img" %}</p>
<!-- <p><img src="_project/quarto_files/folktales/figure-html/0c2c92b6-1-hrustall-eQVUSm2peDc-unsplash.jpg" class="img-fluid figure-img"></p> -->
<p></p><figcaption class="figure-caption">image from unsplash.com</figcaption><p></p>
</figure>
</div>
<section id="introduction" class="level2">
<h2 class="anchored" data-anchor-id="introduction">Introduction</h2>
<p>Although most knowledge is communicated and stored in writing today, the oral tradition takes precedent with it’s longer history and wider reach. Storytelling is a fundamental mode of communication: they’re easy to remember and understand. Parents teach values to kids through storytelling. The classic tale of the knight saving a princess from the dragon exemplifies bravery as a desireable trait. The stories we tell our kids can reflect what we value. <br> <br> On a larger scale, stories passed down generationally reflect the values of a society. Here, I explore the relationship between a culture’s stories and its values. <br> For data on stories, I use folktale data scraped by Andrzej Panczenko (avaliable <a href="https://www.kaggle.com/datasets/andrzejpanczenko/folk-tales-dataset">here</a>, accessed October 2022), which contains 2,838 folktales from 57 nations. The drawbacks of using a dataset for folktales should be noted: English translations are used for other languages; stories are told and retold, but are only recorded once here; the popularity/importance of each story is not considered; and the stories that are included might be of different types (are English folktales about Jack and Jill comparable to Chinese epics retold for children, like the Monkey King?)<br> For data on cultural values, I use Hofstede’s six cultural dimensions: power distance index, individualism, masculinity, uncertainty avoidance index, and long-term orientation. I downloaded the data <a href="https://www.kaggle.com/code/tarukofusuki/hofstede-s-cultural-dimensions-notebook/data">here</a>. A future study might consider using laws to analyze cultural values. However, because of colonization and Western influence, current laws might not be an accurate representation of cultural values.</p>
<div class="cell" data-execution_count="3">
<div class="cell-output cell-output-display" data-execution_count="3">

<div>

<table class="dataframe table table-sm table-striped">
  <thead>
    <tr>
      <th></th>
      <th>nation</th>
      <th>title</th>
      <th>text</th>
      <th>wordlist</th>
      <th>cleaned</th>
      <th>lemmas</th>
      <th>phrased</th>
      <th>language_family</th>
      <th>sid</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>japanese</td>
      <td>Momotaro</td>
      <td>If you’ll believe me there was a time when the...</td>
      <td>['believe', 'time', 'fairies', 'none', 'shy', ...</td>
      <td>believe time fairies none shy time beasts talk...</td>
      <td>['believe', 'time', 'fairy', 'none', 'time', '...</td>
      <td>['believe', 'time', 'fairy', 'none', 'time', '...</td>
      <td>east_asia</td>
      <td>sid0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>serbian</td>
      <td>The Birdcatcher</td>
      <td>Near Constantinople there lived a man who knew...</td>
      <td>['near', 'constantinople', 'lived', 'man', 'kn...</td>
      <td>near constantinople lived man knew occupation ...</td>
      <td>['near', 'constantinople', 'live', 'knew', 'oc...</td>
      <td>['near', 'constantinople', 'live', 'knew', 'oc...</td>
      <td>slavic</td>
      <td>sid1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>german</td>
      <td>Sharing Joy and Sorrow</td>
      <td>There was once a tailor, who was a quarrelsome...</td>
      <td>['tailor', 'quarrelsome', 'fellow', 'wife', 'g...</td>
      <td>tailor quarrelsome fellow wife good industriou...</td>
      <td>['tailor', 'quarrelsome', 'fellow', 'wife', 'g...</td>
      <td>['tailor', 'quarrelsome', 'fellow', 'wife', 'g...</td>
      <td>germanic</td>
      <td>sid2</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell" data-execution_count="4">
<div class="cell-output cell-output-display" data-execution_count="4">

<div>

<table class="dataframe table table-sm table-striped">
  <thead>
    <tr>
      <th></th>
      <th>ctr</th>
      <th>country</th>
      <th>pdi</th>
      <th>idv</th>
      <th>mas</th>
      <th>uai</th>
      <th>ltowvs</th>
      <th>ivr</th>
      <th>estim</th>
      <th>Unnamed: 9</th>
      <th>Unnamed: 10</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>ALB</td>
      <td>Albania</td>
      <td>90</td>
      <td>20</td>
      <td>80</td>
      <td>70</td>
      <td>61.460957</td>
      <td>14.508929</td>
      <td>1</td>
      <td>NaN</td>
      <td>https://www.hofstede-insights.com/product/comp...</td>
    </tr>
    <tr>
      <th>1</th>
      <td>ALG</td>
      <td>Algeria</td>
      <td>80</td>
      <td>35</td>
      <td>35</td>
      <td>70</td>
      <td>25.944584</td>
      <td>32.366071</td>
      <td>1</td>
      <td>NaN</td>
      <td>Use estimates</td>
    </tr>
    <tr>
      <th>2</th>
      <td>ANG</td>
      <td>Angola</td>
      <td>83</td>
      <td>18</td>
      <td>20</td>
      <td>60</td>
      <td>15.000000</td>
      <td>83.000000</td>
      <td>1</td>
      <td>NaN</td>
      <td>0 = Not estimated</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<section id="existence-of-a-pattern" class="level3">
<h3 class="anchored" data-anchor-id="existence-of-a-pattern">Existence of a Pattern</h3>
<p>Using the Peircean understanding of a sign, the sign-vehicle here are the stories and the object and interpretant are the cultural values. <br> <br> With the example of the knight in shining armor, the story of the knight is the sign-vehicle. If a parent asks a child to remember the story when the child is facing a difficulty, the object is bravery, because that is what the parent is trying to communicate. The object and sign-vehicle relate iconically, since the knight resembles bravery. <br> The child might most immediately see the knight as “cool”, so that is the immediate interpretant. The knight and coolness relate dicentically; the statement “The knight is cool” is a proposition. Another proposition is “The knight is brave”. Thus, the child makes the argument that he should be like the knight, and be brave, since the knight is cool. <br> <br> At a larger level, these stories are legisigns: most knights are brave. In this way, the knight becomes a convention of bravery. Other cultures might have other conventions of bravery, such as dragons. Where Western culture tells stories about scary dragon, East Asian cultures might tell stories about royal dragons. At the international level, we can see how cultures that tell stories about bravery more often likely value bravery.</p>
<p>To see if this pattern truly exists, let’s look at a general map of the stories. Each story is turned into a datapoint using t-SNE and doc2vec. Because the dataset I’m using tags folktales with their “nation”, this is what I use to differentiate between cultures. I define culture here as the stories and values of these nations.</p>
<div class="cell" data-execution_count="22">
<div class="cell-output cell-output-display" data-execution_count="22">

<div id="altair-viz-419c89aac0ff4e89b50e33f5f53addd1"></div>
<script type="text/javascript">
  var VEGA_DEBUG = (typeof VEGA_DEBUG == "undefined") ? {} : VEGA_DEBUG;
  (function(spec, embedOpt){
    let outputDiv = document.currentScript.previousElementSibling;
    if (outputDiv.id !== "altair-viz-419c89aac0ff4e89b50e33f5f53addd1") {
      outputDiv = document.getElementById("altair-viz-419c89aac0ff4e89b50e33f5f53addd1");
    }
    const paths = {
      "vega": "https://cdn.jsdelivr.net/npm//vega@5?noext",
      "vega-lib": "https://cdn.jsdelivr.net/npm//vega-lib?noext",
      "vega-lite": "https://cdn.jsdelivr.net/npm//vega-lite@4.17.0?noext",
      "vega-embed": "https://cdn.jsdelivr.net/npm//vega-embed@6?noext",
    };

    function maybeLoadScript(lib, version) {
      var key = `${lib.replace("-", "")}_version`;
      return (VEGA_DEBUG[key] == version) ?
        Promise.resolve(paths[lib]) :
        new Promise(function(resolve, reject) {
          var s = document.createElement('script');
          document.getElementsByTagName("head")[0].appendChild(s);
          s.async = true;
          s.onload = () => {
            VEGA_DEBUG[key] = version;
            return resolve(paths[lib]);
          };
          s.onerror = () => reject(`Error loading script: ${paths[lib]}`);
          s.src = paths[lib];
        });
    }

    function showError(err) {
      outputDiv.innerHTML = `<div class="error" style="color:red;">${err}</div>`;
      throw err;
    }

    function displayChart(vegaEmbed) {
      vegaEmbed(outputDiv, spec, embedOpt)
        .catch(err => showError(`Javascript Error: ${err.message}<br>This usually means there's a typo in your chart specification. See the javascript console for the full traceback.`));
    }

    if(typeof define === "function" && define.amd) {
      requirejs.config({paths});
      require(["vega-embed"], displayChart, err => showError(`Error loading script: ${err.message}`));
    } else {
      maybeLoadScript("vega", "5")
        .then(() => maybeLoadScript("vega-lite", "4.17.0"))
        .then(() => maybeLoadScript("vega-embed", "6"))
        .catch(showError)
        .then(() => displayChart(vegaEmbed));
    }
  })({"config": {"view": {"continuousWidth": 400, "continuousHeight": 300}}, "data": {"name": "data-46b784f4844fa62b60c789a0a4f055bf"}, "mark": {"type": "point", "filled": true, "opacity": 0.5}, "encoding": {"color": {"field": "Nation", "legend": null, "type": "nominal"}, "facet": {"columns": 2, "field": "language_family", "header": {"labelFontSize": 20}, "type": "nominal"}, "tooltip": [{"field": "Nation", "type": "nominal"}], "x": {"field": "X1", "scale": {"zero": false}, "type": "quantitative"}, "y": {"field": "X2", "scale": {"zero": false}, "type": "quantitative"}}, "height": 300, "width": 300, "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json", "datasets": {"data-46b784f4844fa62b60c789a0a4f055bf": [{"X1": -7.5506144, "X2": -11.772786, "Nation": "German", "language_family": "Germanic"}, {"X1": -3.6273453, "X2": -28.77757, "Nation": "English", "language_family": "Germanic"}, {"X1": -15.61611, "X2": -9.73962, "Nation": "English", "language_family": "Germanic"}, {"X1": 8.863904, "X2": -22.674429, "Nation": "German", "language_family": "Germanic"}, {"X1": -32.830315, "X2": 3.1435993, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 26.572205, "X2": -3.9748535, "Nation": "German", "language_family": "Germanic"}, {"X1": -13.264935, "X2": -1.3266561, "Nation": "English", "language_family": "Germanic"}, {"X1": -22.45433, "X2": 7.243844, "Nation": "German", "language_family": "Germanic"}, {"X1": 20.518202, "X2": -25.295599, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 8.664921, "X2": -21.805838, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 14.977307, "X2": -35.024483, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": -7.5509324, "X2": -26.523844, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 12.046329, "X2": -26.749832, "Nation": "German", "language_family": "Germanic"}, {"X1": 26.655886, "X2": 17.895771, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 25.291409, "X2": 11.584854, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 25.530222, "X2": 17.038359, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 0.6871591, "X2": 36.870335, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": -6.261014, "X2": -13.274788, "Nation": "English", "language_family": "Germanic"}, {"X1": 22.747175, "X2": 18.976162, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 13.150396, "X2": -31.627768, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 28.964628, "X2": 21.636662, "Nation": "German", "language_family": "Germanic"}, {"X1": 0.056290526, "X2": 29.38388, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": -3.516889, "X2": 29.745668, "Nation": "English", "language_family": "Germanic"}, {"X1": 31.64594, "X2": 12.314723, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 1.1804538, "X2": -23.282763, "Nation": "German", "language_family": "Germanic"}, {"X1": 20.275629, "X2": 17.423649, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 21.58536, "X2": 16.24928, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 2.0450885, "X2": 38.201492, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 16.64033, "X2": -5.745389, "Nation": "German", "language_family": "Germanic"}, {"X1": 20.343248, "X2": 21.696917, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 5.2366567, "X2": -33.354992, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -12.438611, "X2": -33.87553, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": -9.34533, "X2": -23.30081, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 29.495157, "X2": 14.263099, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 6.3633666, "X2": -38.149418, "Nation": "English", "language_family": "Germanic"}, {"X1": 24.77508, "X2": -10.233263, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 23.026617, "X2": 13.384576, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 29.915606, "X2": 14.610617, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 9.622739, "X2": 34.777756, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 22.025055, "X2": 14.540603, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -3.288615, "X2": -28.92914, "Nation": "English", "language_family": "Germanic"}, {"X1": 18.718746, "X2": 31.75148, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 6.5865083, "X2": 18.959274, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 28.739683, "X2": -22.629591, "Nation": "German", "language_family": "Germanic"}, {"X1": 4.464074, "X2": 40.414394, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -12.484399, "X2": 19.428408, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 3.5854104, "X2": 35.017437, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -0.03360217, "X2": -32.902805, "Nation": "English", "language_family": "Germanic"}, {"X1": 22.791512, "X2": 15.271173, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 26.812435, "X2": 17.703152, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -18.152258, "X2": -13.661538, "Nation": "German", "language_family": "Germanic"}, {"X1": 2.2720964, "X2": 0.6884005, "Nation": "German", "language_family": "Germanic"}, {"X1": 13.63383, "X2": 30.257172, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 22.891054, "X2": 12.142348, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -11.540382, "X2": -6.7732315, "Nation": "German", "language_family": "Germanic"}, {"X1": 8.668605, "X2": 34.97298, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 15.881231, "X2": -9.009655, "Nation": "German", "language_family": "Germanic"}, {"X1": 6.179011, "X2": 37.294197, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 10.588927, "X2": 13.55447, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -15.8972025, "X2": 2.5163348, "Nation": "German", "language_family": "Germanic"}, {"X1": 11.860339, "X2": 28.925753, "Nation": "English", "language_family": "Germanic"}, {"X1": 13.497674, "X2": 2.4593067, "Nation": "English", "language_family": "Germanic"}, {"X1": 3.8492696, "X2": 40.542732, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 25.335716, "X2": -5.5314817, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 28.033667, "X2": 11.61036, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 24.864298, "X2": -22.769735, "Nation": "German", "language_family": "Germanic"}, {"X1": 20.097683, "X2": -24.28555, "Nation": "English", "language_family": "Germanic"}, {"X1": 13.145331, "X2": -34.72754, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 26.98524, "X2": 26.046041, "Nation": "German", "language_family": "Germanic"}, {"X1": -19.490358, "X2": -15.017289, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 27.79017, "X2": 15.6409445, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 0.33019438, "X2": -31.033373, "Nation": "English", "language_family": "Germanic"}, {"X1": 27.349463, "X2": -27.04199, "Nation": "German", "language_family": "Germanic"}, {"X1": -4.263311, "X2": -22.63477, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -5.5141735, "X2": 0.06411824, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.234842, "X2": 38.62223, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -17.291193, "X2": 2.3876936, "Nation": "English", "language_family": "Germanic"}, {"X1": 36.246765, "X2": -1.0249611, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -13.856672, "X2": -0.033728085, "Nation": "German", "language_family": "Germanic"}, {"X1": 18.24886, "X2": -16.179232, "Nation": "English", "language_family": "Germanic"}, {"X1": 27.34726, "X2": -27.091991, "Nation": "German", "language_family": "Germanic"}, {"X1": 28.924908, "X2": 12.156568, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 27.511164, "X2": -13.92951, "Nation": "German", "language_family": "Germanic"}, {"X1": 1.8088118, "X2": -44.062637, "Nation": "German", "language_family": "Germanic"}, {"X1": 22.352175, "X2": 14.014742, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 29.603672, "X2": -22.317604, "Nation": "German", "language_family": "Germanic"}, {"X1": -27.6119, "X2": -26.95452, "Nation": "English", "language_family": "Germanic"}, {"X1": 3.4936132, "X2": 35.34722, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 2.5475469, "X2": -31.72165, "Nation": "English", "language_family": "Germanic"}, {"X1": 14.926696, "X2": -23.218761, "Nation": "German", "language_family": "Germanic"}, {"X1": 26.762148, "X2": 13.976553, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 4.363103, "X2": 37.32672, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 14.2651205, "X2": -22.877102, "Nation": "German", "language_family": "Germanic"}, {"X1": 27.442661, "X2": 17.557917, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 29.475918, "X2": 12.004274, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 23.644682, "X2": -23.573715, "Nation": "German", "language_family": "Germanic"}, {"X1": -7.9068246, "X2": 11.511052, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 18.637764, "X2": -31.239819, "Nation": "German", "language_family": "Germanic"}, {"X1": 15.7158575, "X2": 3.9167402, "Nation": "Belgian", "language_family": "Germanic"}, {"X1": 20.67327, "X2": -13.339983, "Nation": "English", "language_family": "Germanic"}, {"X1": 23.45897, "X2": -16.561018, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 15.160777, "X2": 17.232935, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -15.295344, "X2": -28.635292, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 12.849796, "X2": -13.819389, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 15.009536, "X2": -8.051662, "Nation": "German", "language_family": "Germanic"}, {"X1": -4.120359, "X2": -14.92251, "Nation": "German", "language_family": "Germanic"}, {"X1": 14.061997, "X2": 28.919573, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.298597, "X2": 9.240076, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 5.2639804, "X2": 6.0589466, "Nation": "English", "language_family": "Germanic"}, {"X1": 6.6767387, "X2": -31.894114, "Nation": "German", "language_family": "Germanic"}, {"X1": 15.74182, "X2": 18.932417, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 8.328387, "X2": -22.887173, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 18.66373, "X2": 16.869501, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 8.421871, "X2": 35.523876, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 11.406425, "X2": 29.189253, "Nation": "German", "language_family": "Germanic"}, {"X1": -18.93305, "X2": -14.030628, "Nation": "German", "language_family": "Germanic"}, {"X1": 22.583313, "X2": -18.957039, "Nation": "German", "language_family": "Germanic"}, {"X1": 20.25804, "X2": -25.227222, "Nation": "English", "language_family": "Germanic"}, {"X1": 18.08297, "X2": -18.624062, "Nation": "English", "language_family": "Germanic"}, {"X1": 3.5998235, "X2": 33.781322, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 20.32023, "X2": 10.148439, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -15.273328, "X2": -28.468863, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 23.081165, "X2": -18.657536, "Nation": "German", "language_family": "Germanic"}, {"X1": -28.781347, "X2": -13.677815, "Nation": "English", "language_family": "Germanic"}, {"X1": -27.276756, "X2": -11.786609, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -0.16904272, "X2": -16.138472, "Nation": "German", "language_family": "Germanic"}, {"X1": 27.69752, "X2": 15.576525, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 22.396294, "X2": 14.033051, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -10.511515, "X2": -7.186389, "Nation": "German", "language_family": "Germanic"}, {"X1": 27.165277, "X2": -19.170568, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.737542, "X2": -32.339153, "Nation": "German", "language_family": "Germanic"}, {"X1": -10.377978, "X2": -22.837961, "Nation": "English", "language_family": "Germanic"}, {"X1": 1.7558604, "X2": 40.141956, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 28.00898, "X2": 13.543214, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 0.123192936, "X2": -18.698723, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 28.335056, "X2": 14.607553, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 18.80935, "X2": -16.253098, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": -25.372795, "X2": -3.385657, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 16.230076, "X2": -25.659464, "Nation": "German", "language_family": "Germanic"}, {"X1": -13.693397, "X2": -14.766723, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 12.5672035, "X2": -3.2334237, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -2.5846875, "X2": 27.235611, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": -12.955641, "X2": 16.838274, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 22.100096, "X2": -2.3374126, "Nation": "German", "language_family": "Germanic"}, {"X1": 13.983179, "X2": -33.371357, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 14.042218, "X2": -2.3814552, "Nation": "German", "language_family": "Germanic"}, {"X1": -12.622164, "X2": -1.0668788, "Nation": "German", "language_family": "Germanic"}, {"X1": 29.38047, "X2": -18.972345, "Nation": "German", "language_family": "Germanic"}, {"X1": -6.0823164, "X2": -23.95882, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 28.147093, "X2": 12.19907, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -10.130683, "X2": -16.830116, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 1.657953, "X2": -10.808292, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 26.897871, "X2": 14.316787, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -9.067109, "X2": -6.113497, "Nation": "German", "language_family": "Germanic"}, {"X1": -3.176603, "X2": 10.278713, "Nation": "German", "language_family": "Germanic"}, {"X1": 8.151883, "X2": 35.21101, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 2.849144, "X2": 3.8124347, "Nation": "German", "language_family": "Germanic"}, {"X1": 26.584661, "X2": 15.718839, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 3.8747647, "X2": 39.54673, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -4.4881096, "X2": -27.948586, "Nation": "English", "language_family": "Germanic"}, {"X1": 14.998204, "X2": -35.278507, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 0.34529606, "X2": -21.569057, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 23.606012, "X2": -25.341745, "Nation": "German", "language_family": "Germanic"}, {"X1": 20.603094, "X2": 12.537969, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 21.012402, "X2": -17.494072, "Nation": "German", "language_family": "Germanic"}, {"X1": -1.1050313, "X2": 3.6144018, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 27.41228, "X2": 9.58589, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -7.863531, "X2": -12.997914, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 15.144483, "X2": -32.47197, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 23.490042, "X2": -4.354846, "Nation": "German", "language_family": "Germanic"}, {"X1": 14.739065, "X2": -8.004543, "Nation": "German", "language_family": "Germanic"}, {"X1": -25.71409, "X2": -10.810797, "Nation": "German", "language_family": "Germanic"}, {"X1": 14.257198, "X2": -22.907385, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.601297, "X2": 13.508095, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 25.382296, "X2": -5.627839, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 14.296072, "X2": -17.925983, "Nation": "German", "language_family": "Germanic"}, {"X1": 17.905188, "X2": 18.48268, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 4.423824, "X2": -32.138874, "Nation": "English", "language_family": "Germanic"}, {"X1": -10.891411, "X2": -34.019203, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 15.885498, "X2": 19.571156, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 24.75817, "X2": -15.161322, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.207176, "X2": -12.815649, "Nation": "German", "language_family": "Germanic"}, {"X1": -3.0819879, "X2": 5.874337, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -3.8250358, "X2": -22.426495, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -26.272509, "X2": -15.052601, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 17.207506, "X2": -25.507235, "Nation": "German", "language_family": "Germanic"}, {"X1": 12.731663, "X2": -10.251041, "Nation": "German", "language_family": "Germanic"}, {"X1": 9.048441, "X2": -15.520223, "Nation": "German", "language_family": "Germanic"}, {"X1": 8.292376, "X2": 16.254684, "Nation": "English", "language_family": "Germanic"}, {"X1": 21.22879, "X2": 12.528717, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 37.093975, "X2": 18.70449, "Nation": "English", "language_family": "Germanic"}, {"X1": 16.921951, "X2": 16.016314, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -7.882977, "X2": 2.3640015, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": -14.640969, "X2": -26.652674, "Nation": "English", "language_family": "Germanic"}, {"X1": 19.309347, "X2": -17.700912, "Nation": "German", "language_family": "Germanic"}, {"X1": -21.991718, "X2": -10.149112, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 6.179681, "X2": 16.799576, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 2.9732647, "X2": 38.083652, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 8.019576, "X2": 12.757287, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 5.4247313, "X2": 36.90442, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -2.8014, "X2": -7.952053, "Nation": "English", "language_family": "Germanic"}, {"X1": 26.329039, "X2": 16.62334, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -3.1265197, "X2": 8.654675, "Nation": "English", "language_family": "Germanic"}, {"X1": 3.6962638, "X2": -34.170414, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -25.818314, "X2": -19.635841, "Nation": "German", "language_family": "Germanic"}, {"X1": 12.585866, "X2": -21.544138, "Nation": "German", "language_family": "Germanic"}, {"X1": 18.61646, "X2": -31.228947, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.764248, "X2": 16.844786, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 20.043072, "X2": 15.013046, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -22.006268, "X2": -25.313187, "Nation": "German", "language_family": "Germanic"}, {"X1": 26.32951, "X2": 6.4270988, "Nation": "English", "language_family": "Germanic"}, {"X1": 10.36893, "X2": -13.8969555, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -9.06141, "X2": -9.684852, "Nation": "Belgian", "language_family": "Germanic"}, {"X1": 2.8873951, "X2": -33.223648, "Nation": "German", "language_family": "Germanic"}, {"X1": -18.490261, "X2": -13.687921, "Nation": "English", "language_family": "Germanic"}, {"X1": 13.695438, "X2": -33.879276, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 24.59632, "X2": -20.837751, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.04319, "X2": 15.15246, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -9.504474, "X2": -19.139492, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -21.712582, "X2": -21.65299, "Nation": "English", "language_family": "Germanic"}, {"X1": 2.0566268, "X2": 37.203007, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -4.1277413, "X2": -28.90762, "Nation": "German", "language_family": "Germanic"}, {"X1": -9.754515, "X2": -8.218293, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 0.9200992, "X2": 37.92869, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -3.4280467, "X2": -29.521904, "Nation": "English", "language_family": "Germanic"}, {"X1": -10.272009, "X2": -17.32018, "Nation": "German", "language_family": "Germanic"}, {"X1": -35.864048, "X2": 4.7844305, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 4.42991, "X2": 36.0322, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 8.813244, "X2": -7.7051177, "Nation": "German", "language_family": "Germanic"}, {"X1": 22.721983, "X2": 19.648558, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 24.268011, "X2": -20.261389, "Nation": "German", "language_family": "Germanic"}, {"X1": -0.77220446, "X2": -6.6826735, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 22.901806, "X2": -22.303755, "Nation": "German", "language_family": "Germanic"}, {"X1": -3.665482, "X2": -28.284815, "Nation": "English", "language_family": "Germanic"}, {"X1": 3.4780579, "X2": 10.8556595, "Nation": "English", "language_family": "Germanic"}, {"X1": -2.5713108, "X2": 9.302946, "Nation": "English", "language_family": "Germanic"}, {"X1": 28.734976, "X2": 10.132055, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -16.741518, "X2": -7.053534, "Nation": "German", "language_family": "Germanic"}, {"X1": 23.646927, "X2": 7.4532127, "Nation": "German", "language_family": "Germanic"}, {"X1": 18.21361, "X2": 14.958265, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 12.817966, "X2": -18.86156, "Nation": "Belgian", "language_family": "Germanic"}, {"X1": -6.2922597, "X2": 0.008006075, "Nation": "German", "language_family": "Germanic"}, {"X1": 6.368559, "X2": -38.15398, "Nation": "English", "language_family": "Germanic"}, {"X1": 21.25071, "X2": -20.73959, "Nation": "German", "language_family": "Germanic"}, {"X1": -4.925424, "X2": -27.626032, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 0.8924481, "X2": -25.931486, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 18.18592, "X2": 12.859108, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -35.87778, "X2": 4.799955, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 2.9605618, "X2": 10.838832, "Nation": "English", "language_family": "Germanic"}, {"X1": 2.623801, "X2": -39.754498, "Nation": "English", "language_family": "Germanic"}, {"X1": -2.7549298, "X2": -24.632164, "Nation": "German", "language_family": "Germanic"}, {"X1": 8.673288, "X2": 34.678688, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 10.43139, "X2": -28.428202, "Nation": "German", "language_family": "Germanic"}, {"X1": 16.61021, "X2": -24.455969, "Nation": "German", "language_family": "Germanic"}, {"X1": 11.512887, "X2": -2.5341582, "Nation": "German", "language_family": "Germanic"}, {"X1": 26.195099, "X2": -22.745512, "Nation": "German", "language_family": "Germanic"}, {"X1": -17.095089, "X2": -9.72969, "Nation": "German", "language_family": "Germanic"}, {"X1": 0.5425982, "X2": -30.339636, "Nation": "English", "language_family": "Germanic"}, {"X1": 3.6695204, "X2": 33.617413, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 26.3365, "X2": -19.039896, "Nation": "German", "language_family": "Germanic"}, {"X1": -15.278423, "X2": -6.635056, "Nation": "English", "language_family": "Germanic"}, {"X1": 25.587921, "X2": 10.770947, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -12.900454, "X2": -4.752994, "Nation": "German", "language_family": "Germanic"}, {"X1": -12.958803, "X2": 16.176085, "Nation": "German", "language_family": "Germanic"}, {"X1": 16.22844, "X2": 35.621532, "Nation": "English", "language_family": "Germanic"}, {"X1": 4.891292, "X2": 34.477333, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -28.509672, "X2": 13.369796, "Nation": "German", "language_family": "Germanic"}, {"X1": -20.955877, "X2": -21.75659, "Nation": "English", "language_family": "Germanic"}, {"X1": 3.2953744, "X2": 19.917664, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 23.921326, "X2": 7.454169, "Nation": "German", "language_family": "Germanic"}, {"X1": 9.845818, "X2": -25.999264, "Nation": "German", "language_family": "Germanic"}, {"X1": 18.478447, "X2": -21.71023, "Nation": "German", "language_family": "Germanic"}, {"X1": 18.713812, "X2": 31.751509, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 17.526474, "X2": -24.267885, "Nation": "German", "language_family": "Germanic"}, {"X1": -14.995107, "X2": -24.692696, "Nation": "German", "language_family": "Germanic"}, {"X1": 14.03275, "X2": -21.734438, "Nation": "German", "language_family": "Germanic"}, {"X1": 6.783751, "X2": -24.325998, "Nation": "German", "language_family": "Germanic"}, {"X1": 3.1705923, "X2": 38.135513, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 7.4736867, "X2": -18.958815, "Nation": "English", "language_family": "Germanic"}, {"X1": -23.942688, "X2": -33.743805, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -12.8143215, "X2": -15.487216, "Nation": "German", "language_family": "Germanic"}, {"X1": 16.287394, "X2": -9.316966, "Nation": "German", "language_family": "Germanic"}, {"X1": 24.681171, "X2": -12.072401, "Nation": "German", "language_family": "Germanic"}, {"X1": 8.614373, "X2": 34.811546, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 12.451717, "X2": -23.015066, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 1.507587, "X2": 38.78552, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 13.51765, "X2": -18.74895, "Nation": "German", "language_family": "Germanic"}, {"X1": -15.091397, "X2": -19.827137, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.650032, "X2": 11.264168, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -29.443678, "X2": 2.3117855, "Nation": "German", "language_family": "Germanic"}, {"X1": 20.97686, "X2": 6.878666, "Nation": "English", "language_family": "Germanic"}, {"X1": -7.822594, "X2": 14.131179, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 8.249574, "X2": -16.229403, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.316965, "X2": -23.38852, "Nation": "German", "language_family": "Germanic"}, {"X1": 18.867096, "X2": 12.781, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 4.514805, "X2": 33.831444, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -17.386908, "X2": 4.165768, "Nation": "English", "language_family": "Germanic"}, {"X1": 11.490815, "X2": -23.76625, "Nation": "German", "language_family": "Germanic"}, {"X1": 10.08056, "X2": -23.763872, "Nation": "German", "language_family": "Germanic"}, {"X1": 24.412594, "X2": 14.2239485, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -0.17369457, "X2": 5.6817565, "Nation": "English", "language_family": "Germanic"}, {"X1": 28.4853, "X2": -9.403199, "Nation": "German", "language_family": "Germanic"}, {"X1": -11.937211, "X2": -34.31348, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": -3.3043878, "X2": 6.091179, "Nation": "German", "language_family": "Germanic"}, {"X1": 18.856022, "X2": -37.52671, "Nation": "German", "language_family": "Germanic"}, {"X1": 14.565643, "X2": -34.44177, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 2.8498654, "X2": -30.256065, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": -10.969954, "X2": -8.684432, "Nation": "German", "language_family": "Germanic"}, {"X1": 8.518977, "X2": 34.865246, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 25.325563, "X2": -23.433552, "Nation": "German", "language_family": "Germanic"}, {"X1": -11.906709, "X2": -6.5586343, "Nation": "German", "language_family": "Germanic"}, {"X1": -22.296007, "X2": -6.178684, "Nation": "German", "language_family": "Germanic"}, {"X1": -14.454162, "X2": 8.308175, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 12.492324, "X2": -25.832748, "Nation": "German", "language_family": "Germanic"}, {"X1": -7.514919, "X2": 30.804579, "Nation": "English", "language_family": "Germanic"}, {"X1": 26.635504, "X2": 2.97019, "Nation": "English", "language_family": "Germanic"}, {"X1": 24.894844, "X2": 7.756162, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.7248335, "X2": -32.389587, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.0627503, "X2": 37.32335, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 12.559059, "X2": -29.477478, "Nation": "German", "language_family": "Germanic"}, {"X1": -8.008623, "X2": -7.700226, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 27.488043, "X2": 14.609021, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -4.8491626, "X2": -1.7304388, "Nation": "German", "language_family": "Germanic"}, {"X1": -12.6756115, "X2": -1.0601346, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.117104, "X2": 19.914005, "Nation": "English", "language_family": "Germanic"}, {"X1": 30.138887, "X2": -31.328663, "Nation": "German", "language_family": "Germanic"}, {"X1": 31.64719, "X2": 12.319737, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 0.99179214, "X2": -29.886023, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": -5.0385995, "X2": -2.872087, "Nation": "German", "language_family": "Germanic"}, {"X1": 11.452546, "X2": -36.211224, "Nation": "English", "language_family": "Germanic"}, {"X1": -8.302863, "X2": -27.95113, "Nation": "English", "language_family": "Germanic"}, {"X1": -27.610598, "X2": -26.955173, "Nation": "English", "language_family": "Germanic"}, {"X1": 10.660302, "X2": -23.782799, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.769793, "X2": -8.28871, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 12.824493, "X2": -35.065056, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 14.253454, "X2": -9.517166, "Nation": "German", "language_family": "Germanic"}, {"X1": 22.070486, "X2": 11.388043, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 19.155317, "X2": -28.196264, "Nation": "German", "language_family": "Germanic"}, {"X1": 14.982793, "X2": 18.755829, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 6.434762, "X2": 37.91805, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 5.919905, "X2": 20.07122, "Nation": "English", "language_family": "Germanic"}, {"X1": -16.598331, "X2": -22.202726, "Nation": "English", "language_family": "Germanic"}, {"X1": 20.232464, "X2": 4.879185, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 2.6243064, "X2": 36.93985, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 25.114729, "X2": 19.90942, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 20.882557, "X2": -24.023453, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 23.999582, "X2": 2.9701073, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 1.2160753, "X2": 39.520184, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 30.13022, "X2": -31.320782, "Nation": "German", "language_family": "Germanic"}, {"X1": -35.54031, "X2": -19.61761, "Nation": "German", "language_family": "Germanic"}, {"X1": 18.102861, "X2": -18.872255, "Nation": "German", "language_family": "Germanic"}, {"X1": -5.76207, "X2": 4.571585, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 17.191261, "X2": -19.022186, "Nation": "German", "language_family": "Germanic"}, {"X1": -11.916824, "X2": -19.001595, "Nation": "English", "language_family": "Germanic"}, {"X1": 29.064318, "X2": 7.21914, "Nation": "English", "language_family": "Germanic"}, {"X1": -8.252262, "X2": -27.905226, "Nation": "English", "language_family": "Germanic"}, {"X1": 14.888362, "X2": 18.232244, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 3.7831113, "X2": -28.346481, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 6.9981937, "X2": 32.785843, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -12.992127, "X2": 17.45308, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": -5.2423406, "X2": 2.6685035, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -17.493532, "X2": -24.330885, "Nation": "German", "language_family": "Germanic"}, {"X1": 14.031417, "X2": 12.994858, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 17.389872, "X2": -32.504272, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 17.123632, "X2": -17.45029, "Nation": "German", "language_family": "Germanic"}, {"X1": -2.509522, "X2": -7.266403, "Nation": "German", "language_family": "Germanic"}, {"X1": -5.3111224, "X2": 1.1191162, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -10.007045, "X2": -12.012758, "Nation": "English", "language_family": "Germanic"}, {"X1": -19.966139, "X2": -16.576555, "Nation": "English", "language_family": "Germanic"}, {"X1": 1.6249481, "X2": 5.4967966, "Nation": "German", "language_family": "Germanic"}, {"X1": 11.224574, "X2": 29.658602, "Nation": "English", "language_family": "Germanic"}, {"X1": 19.163015, "X2": -28.223312, "Nation": "German", "language_family": "Germanic"}, {"X1": 29.31703, "X2": -18.988712, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.148476, "X2": -29.177197, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 8.895354, "X2": 35.64965, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 19.9291, "X2": 17.754934, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 11.357569, "X2": 0.9684722, "Nation": "German", "language_family": "Germanic"}, {"X1": -7.57072, "X2": 3.7769964, "Nation": "English", "language_family": "Germanic"}, {"X1": 27.660532, "X2": 14.091469, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 13.957591, "X2": -15.563054, "Nation": "German", "language_family": "Germanic"}, {"X1": 19.476818, "X2": -23.547266, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.1877685, "X2": -29.471617, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 5.640637, "X2": -31.663446, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -25.791187, "X2": -9.4994135, "Nation": "German", "language_family": "Germanic"}, {"X1": -20.805136, "X2": -3.792648, "Nation": "English", "language_family": "Germanic"}, {"X1": 28.685505, "X2": -22.543747, "Nation": "German", "language_family": "Germanic"}, {"X1": 22.128033, "X2": -2.282522, "Nation": "German", "language_family": "Germanic"}, {"X1": -21.777775, "X2": 31.685188, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 3.873366, "X2": 36.823856, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 5.6058254, "X2": -33.467712, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 24.605452, "X2": 13.259877, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -8.244581, "X2": 2.7839503, "Nation": "German", "language_family": "Germanic"}, {"X1": -4.7408786, "X2": -16.933872, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -30.771898, "X2": 1.3348691, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 30.117758, "X2": -10.284246, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 16.355293, "X2": 13.172214, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 19.610369, "X2": 5.303962, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": -10.934951, "X2": -11.768139, "Nation": "English", "language_family": "Germanic"}, {"X1": 19.182077, "X2": 12.802541, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 17.614254, "X2": -24.829294, "Nation": "German", "language_family": "Germanic"}, {"X1": 33.634583, "X2": 5.928725, "Nation": "English", "language_family": "Germanic"}, {"X1": 21.08204, "X2": -20.800268, "Nation": "German", "language_family": "Germanic"}, {"X1": -3.1090498, "X2": -28.110046, "Nation": "English", "language_family": "Germanic"}, {"X1": 36.82334, "X2": -1.152739, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 24.134129, "X2": -16.952055, "Nation": "German", "language_family": "Germanic"}, {"X1": 23.034262, "X2": 16.653105, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 17.616116, "X2": 15.009481, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 3.2801795, "X2": 39.066795, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 18.409985, "X2": 17.131533, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -25.651651, "X2": -12.289272, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 2.6243582, "X2": -39.75444, "Nation": "English", "language_family": "Germanic"}, {"X1": 19.2781, "X2": 12.5044365, "Nation": "Belgian", "language_family": "Germanic"}, {"X1": 26.725697, "X2": 15.117349, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 4.723946, "X2": 37.631138, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -5.654932, "X2": 24.047123, "Nation": "English", "language_family": "Germanic"}, {"X1": 5.560316, "X2": 14.572116, "Nation": "German", "language_family": "Germanic"}, {"X1": 27.073477, "X2": 11.373871, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 9.685755, "X2": -25.667274, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.862265, "X2": 14.614412, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -28.405659, "X2": -0.61882514, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 13.2258215, "X2": -34.01352, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": -20.556648, "X2": -14.421478, "Nation": "English", "language_family": "Germanic"}, {"X1": -8.535303, "X2": 3.3786132, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -7.658608, "X2": 5.019094, "Nation": "German", "language_family": "Germanic"}, {"X1": -22.35794, "X2": -10.481752, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 17.134853, "X2": 17.325233, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 10.795794, "X2": -25.72448, "Nation": "German", "language_family": "Germanic"}, {"X1": -24.015232, "X2": -29.420176, "Nation": "German", "language_family": "Germanic"}, {"X1": 15.571578, "X2": -7.7339864, "Nation": "English", "language_family": "Germanic"}, {"X1": -14.534853, "X2": -0.8840835, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 4.4977846, "X2": 38.43838, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 21.055387, "X2": -0.8691027, "Nation": "German", "language_family": "Germanic"}, {"X1": 18.08902, "X2": -5.0170374, "Nation": "Belgian", "language_family": "Germanic"}, {"X1": -6.599885, "X2": -4.5295877, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": -27.59631, "X2": -11.8376255, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": -9.019747, "X2": -19.169497, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -8.061972, "X2": -2.8249755, "Nation": "German", "language_family": "Germanic"}, {"X1": -7.1346564, "X2": -3.4821923, "Nation": "English", "language_family": "Germanic"}, {"X1": 27.729113, "X2": 8.442547, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 10.7369375, "X2": -22.71806, "Nation": "German", "language_family": "Germanic"}, {"X1": -2.7709875, "X2": -24.65384, "Nation": "German", "language_family": "Germanic"}, {"X1": -10.671087, "X2": -33.639755, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 3.300793, "X2": -19.428143, "Nation": "German", "language_family": "Germanic"}, {"X1": 7.4051647, "X2": -17.924934, "Nation": "German", "language_family": "Germanic"}, {"X1": 4.8894644, "X2": 39.240414, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 14.061516, "X2": 1.4181341, "Nation": "German", "language_family": "Germanic"}, {"X1": 7.104345, "X2": -27.525398, "Nation": "English", "language_family": "Germanic"}, {"X1": 11.30803, "X2": -36.38251, "Nation": "English", "language_family": "Germanic"}, {"X1": 10.4665985, "X2": -17.331758, "Nation": "German", "language_family": "Germanic"}, {"X1": 13.086249, "X2": -13.812329, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -12.790611, "X2": -4.359055, "Nation": "German", "language_family": "Germanic"}, {"X1": 22.786015, "X2": -18.913975, "Nation": "German", "language_family": "Germanic"}, {"X1": 1.4736555, "X2": -29.378803, "Nation": "English", "language_family": "Germanic"}, {"X1": -20.176973, "X2": -32.338737, "Nation": "English", "language_family": "Germanic"}, {"X1": 1.7366382, "X2": 37.40118, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 29.170805, "X2": 9.522818, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 27.640837, "X2": -7.4462914, "Nation": "German", "language_family": "Germanic"}, {"X1": -19.999939, "X2": -16.639301, "Nation": "English", "language_family": "Germanic"}, {"X1": 2.2452922, "X2": 6.857691, "Nation": "English", "language_family": "Germanic"}, {"X1": 7.289863, "X2": 17.977133, "Nation": "German", "language_family": "Germanic"}, {"X1": 7.2752333, "X2": 36.100616, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -10.967241, "X2": -34.34977, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 36.28354, "X2": -4.121714, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": -17.495558, "X2": -24.329855, "Nation": "German", "language_family": "Germanic"}, {"X1": 24.454657, "X2": -5.170028, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -7.012268, "X2": -23.32168, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -7.398836, "X2": -19.141542, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -11.048806, "X2": -15.674893, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 22.651243, "X2": 17.856129, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 28.510078, "X2": 14.913777, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -28.93547, "X2": -11.629465, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -26.66421, "X2": 0.68975943, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 4.8086176, "X2": 22.736786, "Nation": "German", "language_family": "Germanic"}, {"X1": 16.164097, "X2": -22.198484, "Nation": "German", "language_family": "Germanic"}, {"X1": -1.9886109, "X2": 7.817266, "Nation": "German", "language_family": "Germanic"}, {"X1": 23.546244, "X2": -16.797363, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 11.226166, "X2": 29.37399, "Nation": "English", "language_family": "Germanic"}, {"X1": -4.2345963, "X2": -32.86946, "Nation": "English", "language_family": "Germanic"}, {"X1": 1.747351, "X2": 37.224747, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -5.6280065, "X2": -12.712574, "Nation": "German", "language_family": "Germanic"}, {"X1": -3.647592, "X2": 2.136819, "Nation": "German", "language_family": "Germanic"}, {"X1": -3.7195404, "X2": 6.084458, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 3.2493725, "X2": -30.568556, "Nation": "English", "language_family": "Germanic"}, {"X1": -11.545292, "X2": -8.909877, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 9.413112, "X2": 12.955246, "Nation": "German", "language_family": "Germanic"}, {"X1": -3.2215075, "X2": -29.832264, "Nation": "English", "language_family": "Germanic"}, {"X1": 21.45141, "X2": -7.705959, "Nation": "German", "language_family": "Germanic"}, {"X1": 9.338252, "X2": 16.323359, "Nation": "German", "language_family": "Germanic"}, {"X1": 24.618961, "X2": -25.680344, "Nation": "German", "language_family": "Germanic"}, {"X1": -25.051525, "X2": -7.192815, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 17.932745, "X2": -8.685584, "Nation": "English", "language_family": "Germanic"}, {"X1": 11.573347, "X2": -21.036297, "Nation": "German", "language_family": "Germanic"}, {"X1": 7.8615017, "X2": 16.30527, "Nation": "German", "language_family": "Germanic"}, {"X1": 27.027718, "X2": 11.343231, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 2.9389246, "X2": 37.134056, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 15.032641, "X2": -7.1600523, "Nation": "Belgian", "language_family": "Germanic"}, {"X1": -21.732924, "X2": -4.895372, "Nation": "German", "language_family": "Germanic"}, {"X1": 12.715838, "X2": 1.5473328, "Nation": "German", "language_family": "Germanic"}, {"X1": 22.61011, "X2": -30.159256, "Nation": "German", "language_family": "Germanic"}, {"X1": 26.242397, "X2": -23.962708, "Nation": "German", "language_family": "Germanic"}, {"X1": 10.830237, "X2": -17.53358, "Nation": "German", "language_family": "Germanic"}, {"X1": -7.2922688, "X2": -1.541351, "Nation": "English", "language_family": "Germanic"}, {"X1": -7.028038, "X2": -23.221441, "Nation": "German", "language_family": "Germanic"}, {"X1": 13.424817, "X2": -24.27277, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -21.08525, "X2": 30.353569, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 3.5810874, "X2": -18.814337, "Nation": "German", "language_family": "Germanic"}, {"X1": 24.236837, "X2": -10.624493, "Nation": "German", "language_family": "Germanic"}, {"X1": 7.017786, "X2": -12.30716, "Nation": "German", "language_family": "Germanic"}, {"X1": 8.227382, "X2": -24.802717, "Nation": "German", "language_family": "Germanic"}, {"X1": -23.74438, "X2": -14.324851, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.407791, "X2": -24.078129, "Nation": "German", "language_family": "Germanic"}, {"X1": -3.8151934, "X2": -10.336169, "Nation": "English", "language_family": "Germanic"}, {"X1": 17.844051, "X2": 17.649252, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -0.0018037215, "X2": -17.293062, "Nation": "German", "language_family": "Germanic"}, {"X1": 23.801388, "X2": 8.284298, "Nation": "German", "language_family": "Germanic"}, {"X1": 2.405343, "X2": 7.774345, "Nation": "German", "language_family": "Germanic"}, {"X1": -3.9307017, "X2": 0.13752913, "Nation": "German", "language_family": "Germanic"}, {"X1": 4.407473, "X2": -19.580193, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 13.567048, "X2": 30.299309, "Nation": "English", "language_family": "Germanic"}, {"X1": 11.487575, "X2": 1.8188422, "Nation": "German", "language_family": "Germanic"}, {"X1": -1.2637205, "X2": 5.798695, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 7.8778443, "X2": 34.71649, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 21.39381, "X2": -8.636486, "Nation": "German", "language_family": "Germanic"}, {"X1": 1.2025574, "X2": -36.37343, "Nation": "English", "language_family": "Germanic"}, {"X1": 26.801664, "X2": -26.289335, "Nation": "German", "language_family": "Germanic"}, {"X1": -21.091593, "X2": 30.662674, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": -19.944887, "X2": -4.9215827, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.1134944, "X2": 35.786285, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -7.88276, "X2": 14.29081, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -25.837849, "X2": 9.721723, "Nation": "English", "language_family": "Germanic"}, {"X1": 24.694757, "X2": 7.5266066, "Nation": "German", "language_family": "Germanic"}, {"X1": -15.440295, "X2": -9.761537, "Nation": "English", "language_family": "Germanic"}, {"X1": 2.7197225, "X2": 38.86197, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 23.23237, "X2": 16.579948, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 5.9369125, "X2": 36.70681, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -38.794098, "X2": -5.1898046, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 5.4020476, "X2": 38.062683, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 21.990234, "X2": 8.441121, "Nation": "German", "language_family": "Germanic"}, {"X1": 12.977382, "X2": -31.060095, "Nation": "German", "language_family": "Germanic"}, {"X1": 12.966337, "X2": -35.055763, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 9.307871, "X2": -18.169292, "Nation": "English", "language_family": "Germanic"}, {"X1": 37.092937, "X2": 18.704208, "Nation": "English", "language_family": "Germanic"}, {"X1": 13.269063, "X2": 30.90119, "Nation": "Belgian", "language_family": "Germanic"}, {"X1": -12.622986, "X2": -8.583406, "Nation": "German", "language_family": "Germanic"}, {"X1": 23.691057, "X2": -24.04822, "Nation": "German", "language_family": "Germanic"}, {"X1": -9.240862, "X2": -21.315866, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 26.514141, "X2": -20.622614, "Nation": "German", "language_family": "Germanic"}, {"X1": 24.828527, "X2": -20.955212, "Nation": "German", "language_family": "Germanic"}, {"X1": 4.7981887, "X2": -7.7138805, "Nation": "Belgian", "language_family": "Germanic"}, {"X1": 9.05822, "X2": -11.660361, "Nation": "English", "language_family": "Germanic"}, {"X1": 5.6132717, "X2": 17.448893, "Nation": "English", "language_family": "Germanic"}, {"X1": 36.517925, "X2": 13.412731, "Nation": "German", "language_family": "Germanic"}, {"X1": 26.355696, "X2": -5.572816, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -25.55508, "X2": 0.53729093, "Nation": "German", "language_family": "Germanic"}, {"X1": -0.64859265, "X2": 4.498707, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 14.046942, "X2": -0.013371971, "Nation": "German", "language_family": "Germanic"}, {"X1": 21.073843, "X2": -0.86908716, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.733295, "X2": 2.3871508, "Nation": "German", "language_family": "Germanic"}, {"X1": 15.477099, "X2": -32.595276, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 19.570143, "X2": -30.980236, "Nation": "German", "language_family": "Germanic"}, {"X1": 0.19962648, "X2": -29.765131, "Nation": "English", "language_family": "Germanic"}, {"X1": -22.775349, "X2": -10.841513, "Nation": "German", "language_family": "Germanic"}, {"X1": 26.46901, "X2": -21.990877, "Nation": "German", "language_family": "Germanic"}, {"X1": 11.777658, "X2": -25.558537, "Nation": "German", "language_family": "Germanic"}, {"X1": 7.009049, "X2": 15.246885, "Nation": "German", "language_family": "Germanic"}, {"X1": -19.611917, "X2": 3.1197731, "Nation": "German", "language_family": "Germanic"}, {"X1": -5.8286657, "X2": 4.855117, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 23.998428, "X2": 15.293392, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 29.149807, "X2": -23.225027, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -8.960832, "X2": -17.181164, "Nation": "German", "language_family": "Germanic"}, {"X1": 4.84823, "X2": 34.222244, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 6.2094975, "X2": -21.199348, "Nation": "German", "language_family": "Germanic"}, {"X1": -25.969664, "X2": -16.231695, "Nation": "English", "language_family": "Germanic"}, {"X1": 10.027442, "X2": -17.426172, "Nation": "German", "language_family": "Germanic"}, {"X1": -14.983035, "X2": -19.900318, "Nation": "German", "language_family": "Germanic"}, {"X1": 1.3541645, "X2": 10.882617, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 8.952803, "X2": -15.433575, "Nation": "German", "language_family": "Germanic"}, {"X1": 20.771843, "X2": -21.246183, "Nation": "German", "language_family": "Germanic"}, {"X1": 20.4962, "X2": -22.785925, "Nation": "English", "language_family": "Germanic"}, {"X1": 5.722025, "X2": 17.716831, "Nation": "German", "language_family": "Germanic"}, {"X1": -21.788048, "X2": -14.024105, "Nation": "English", "language_family": "Germanic"}, {"X1": 1.0032145, "X2": 12.475365, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -12.168616, "X2": -24.01822, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 10.671968, "X2": -15.708837, "Nation": "German", "language_family": "Germanic"}, {"X1": 24.432983, "X2": -19.401646, "Nation": "German", "language_family": "Germanic"}, {"X1": 13.120586, "X2": -3.968899, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 11.407562, "X2": -3.293734, "Nation": "English", "language_family": "Germanic"}, {"X1": 12.061264, "X2": -26.835423, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.187174, "X2": -12.901388, "Nation": "German", "language_family": "Germanic"}, {"X1": 25.269722, "X2": -24.921757, "Nation": "German", "language_family": "Germanic"}, {"X1": 3.2749422, "X2": 39.21978, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 2.8997195, "X2": 0.44508314, "Nation": "German", "language_family": "Germanic"}, {"X1": 23.625574, "X2": -24.130991, "Nation": "German", "language_family": "Germanic"}, {"X1": -21.73247, "X2": -21.70957, "Nation": "English", "language_family": "Germanic"}, {"X1": -33.326805, "X2": 5.065651, "Nation": "English", "language_family": "Germanic"}, {"X1": 25.456064, "X2": 5.721684, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 2.4700043, "X2": -3.2583058, "Nation": "German", "language_family": "Germanic"}, {"X1": 16.484709, "X2": -17.958456, "Nation": "German", "language_family": "Germanic"}, {"X1": 8.933976, "X2": -18.45512, "Nation": "German", "language_family": "Germanic"}, {"X1": 33.659317, "X2": -5.7818847, "Nation": "German", "language_family": "Germanic"}, {"X1": 20.099003, "X2": -25.710415, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 23.447678, "X2": 9.224367, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.7235265, "X2": 38.585857, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 16.805664, "X2": -24.23279, "Nation": "German", "language_family": "Germanic"}, {"X1": -9.591681, "X2": -29.914936, "Nation": "English", "language_family": "Germanic"}, {"X1": -1.5222719, "X2": -32.027416, "Nation": "English", "language_family": "Germanic"}, {"X1": 24.535856, "X2": -10.361003, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -16.450386, "X2": 9.345149, "Nation": "Belgian", "language_family": "Germanic"}, {"X1": -3.2499053, "X2": 11.909328, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.0148253, "X2": 36.458843, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 12.850036, "X2": -3.7980003, "Nation": "German", "language_family": "Germanic"}, {"X1": -14.858479, "X2": -8.041105, "Nation": "English", "language_family": "Germanic"}, {"X1": -25.836554, "X2": -11.443686, "Nation": "German", "language_family": "Germanic"}, {"X1": -21.339289, "X2": -6.511524, "Nation": "German", "language_family": "Germanic"}, {"X1": 3.0851827, "X2": 6.6708264, "Nation": "German", "language_family": "Germanic"}, {"X1": 26.856157, "X2": -10.574502, "Nation": "German", "language_family": "Germanic"}, {"X1": 6.7629147, "X2": -18.572319, "Nation": "English", "language_family": "Germanic"}, {"X1": -6.094772, "X2": 0.6153842, "Nation": "German", "language_family": "Germanic"}, {"X1": -7.922892, "X2": 8.419399, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -27.976458, "X2": -31.455708, "Nation": "German", "language_family": "Germanic"}, {"X1": 12.718594, "X2": -24.146019, "Nation": "German", "language_family": "Germanic"}, {"X1": 18.858484, "X2": -37.53184, "Nation": "German", "language_family": "Germanic"}, {"X1": 11.121172, "X2": 10.446193, "Nation": "German", "language_family": "Germanic"}, {"X1": 11.638114, "X2": -21.326653, "Nation": "German", "language_family": "Germanic"}, {"X1": -12.803135, "X2": -6.660986, "Nation": "German", "language_family": "Germanic"}, {"X1": -8.374211, "X2": -0.45715588, "Nation": "English", "language_family": "Germanic"}, {"X1": -4.0564485, "X2": -22.544128, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -13.793776, "X2": -9.301825, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 2.1030476, "X2": -17.859856, "Nation": "English", "language_family": "Germanic"}, {"X1": -9.127558, "X2": 1.6334015, "Nation": "German", "language_family": "Germanic"}, {"X1": -27.976088, "X2": -31.454144, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.6842513, "X2": 35.808502, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -5.1703405, "X2": 12.745279, "Nation": "English", "language_family": "Germanic"}, {"X1": 13.491183, "X2": -23.913746, "Nation": "German", "language_family": "Germanic"}, {"X1": -30.702608, "X2": 1.3506334, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 19.942461, "X2": 7.2154303, "Nation": "English", "language_family": "Germanic"}, {"X1": 18.295794, "X2": 4.9113264, "Nation": "English", "language_family": "Germanic"}, {"X1": -28.126263, "X2": 7.3763146, "Nation": "English", "language_family": "Germanic"}, {"X1": 13.020247, "X2": -32.120213, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 5.370055, "X2": 37.4453, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 17.850454, "X2": 8.385437, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 14.716552, "X2": -9.5174465, "Nation": "German", "language_family": "Germanic"}, {"X1": -1.5116209, "X2": -8.667068, "Nation": "German", "language_family": "Germanic"}, {"X1": 6.861968, "X2": 17.758726, "Nation": "German", "language_family": "Germanic"}, {"X1": -7.7720404, "X2": -8.733823, "Nation": "English", "language_family": "Germanic"}, {"X1": 14.180857, "X2": -18.05817, "Nation": "German", "language_family": "Germanic"}, {"X1": -6.148861, "X2": 22.470247, "Nation": "English", "language_family": "Germanic"}, {"X1": -23.30365, "X2": -17.74229, "Nation": "German", "language_family": "Germanic"}, {"X1": 1.4188932, "X2": -27.124739, "Nation": "English", "language_family": "Germanic"}, {"X1": -5.131732, "X2": -7.094436, "Nation": "English", "language_family": "Germanic"}, {"X1": 7.3777475, "X2": -33.372894, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": 21.661926, "X2": -20.083227, "Nation": "German", "language_family": "Germanic"}, {"X1": 0.24851307, "X2": 14.464544, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -11.668679, "X2": -6.1378465, "Nation": "German", "language_family": "Germanic"}, {"X1": 0.74270296, "X2": 4.2839117, "Nation": "German", "language_family": "Germanic"}, {"X1": 29.000154, "X2": 7.368739, "Nation": "English", "language_family": "Germanic"}, {"X1": 22.722668, "X2": 19.601355, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 37.20607, "X2": -1.0005778, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 1.4619257, "X2": 39.761158, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 15.838157, "X2": 3.2607393, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 2.0602355, "X2": -31.879948, "Nation": "English", "language_family": "Germanic"}, {"X1": 18.5309, "X2": 38.328503, "Nation": "English", "language_family": "Germanic"}, {"X1": -10.435666, "X2": 37.624165, "Nation": "German", "language_family": "Germanic"}, {"X1": 17.556967, "X2": -23.380798, "Nation": "German", "language_family": "Germanic"}, {"X1": 1.8680115, "X2": -44.05648, "Nation": "German", "language_family": "Germanic"}, {"X1": 23.344105, "X2": -21.676548, "Nation": "German", "language_family": "Germanic"}, {"X1": 23.769287, "X2": 3.5010114, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 17.301363, "X2": -17.446667, "Nation": "German", "language_family": "Germanic"}, {"X1": -19.588518, "X2": -15.600038, "Nation": "English", "language_family": "Germanic"}, {"X1": 3.7478302, "X2": 41.02614, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": 24.61282, "X2": 7.059632, "Nation": "German", "language_family": "Germanic"}, {"X1": 3.5875418, "X2": 1.4123695, "Nation": "German", "language_family": "Germanic"}, {"X1": -1.0768753, "X2": -25.431116, "Nation": "German", "language_family": "Germanic"}, {"X1": -27.243273, "X2": 0.720483, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": -7.5705867, "X2": -21.011843, "Nation": "Danish", "language_family": "Germanic"}, {"X1": 12.497542, "X2": -14.267922, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": -0.13726512, "X2": 29.50609, "Nation": "Dutch", "language_family": "Germanic"}, {"X1": 1.2014447, "X2": 39.66211, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -19.970888, "X2": -7.8935814, "Nation": "German", "language_family": "Germanic"}, {"X1": -35.53239, "X2": -19.613417, "Nation": "German", "language_family": "Germanic"}, {"X1": -0.8268679, "X2": -7.915997, "Nation": "German", "language_family": "Germanic"}, {"X1": 3.7438743, "X2": 40.973446, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 14.341496, "X2": -22.048244, "Nation": "German", "language_family": "Germanic"}, {"X1": 6.9431896, "X2": 16.368996, "Nation": "German", "language_family": "Germanic"}, {"X1": 11.994698, "X2": -10.262983, "Nation": "German", "language_family": "Germanic"}, {"X1": 27.98637, "X2": -19.158789, "Nation": "German", "language_family": "Germanic"}, {"X1": -2.1517417, "X2": 2.442314, "Nation": "Swedish", "language_family": "Germanic"}, {"X1": 6.7028856, "X2": 3.977919, "Nation": "German", "language_family": "Germanic"}, {"X1": -23.998259, "X2": -29.37687, "Nation": "German", "language_family": "Germanic"}, {"X1": 11.3462105, "X2": -12.59912, "Nation": "Belgian", "language_family": "Germanic"}, {"X1": -3.3993652, "X2": -5.760783, "Nation": "German", "language_family": "Germanic"}, {"X1": -4.625121, "X2": -0.004699428, "Nation": "German", "language_family": "Germanic"}, {"X1": 15.522395, "X2": -0.87099516, "Nation": "English", "language_family": "Germanic"}, {"X1": 15.13446, "X2": -25.054699, "Nation": "German", "language_family": "Germanic"}, {"X1": -10.19466, "X2": -4.4036074, "Nation": "German", "language_family": "Germanic"}, {"X1": 6.75227, "X2": -2.344205, "Nation": "English", "language_family": "Germanic"}, {"X1": 5.8245134, "X2": -5.4780493, "Nation": "English", "language_family": "Germanic"}, {"X1": 8.2374115, "X2": 2.1468742, "Nation": "German", "language_family": "Germanic"}, {"X1": -2.5547729, "X2": -14.901908, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": 16.076704, "X2": 0.9355953, "Nation": "Nordic", "language_family": "Germanic"}, {"X1": -5.4010835, "X2": -13.810846, "Nation": "German", "language_family": "Germanic"}, {"X1": -31.496017, "X2": 1.873342, "Nation": "Icelandic", "language_family": "Germanic"}, {"X1": 24.254452, "X2": -18.291765, "Nation": "German", "language_family": "Germanic"}, {"X1": -21.415901, "X2": -25.44322, "Nation": "Danish", "language_family": "Germanic"}, {"X1": -2.2132423, "X2": -4.0470014, "Nation": "Scandinavian", "language_family": "Germanic"}, {"X1": -1.7166142, "X2": 25.0052, "Nation": "German", "language_family": "Germanic"}, {"X1": -8.271743, "X2": -6.643932, "Nation": "German", "language_family": "Germanic"}, {"X1": 5.7655325, "X2": -33.906895, "Nation": "Norwegian", "language_family": "Germanic"}, {"X1": -1.613154, "X2": 23.311752, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 24.572065, "X2": -29.5707, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -25.241455, "X2": -7.2974453, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 3.0892344, "X2": 16.778814, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -1.6997626, "X2": -19.095814, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 32.96552, "X2": -12.859323, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 9.536993, "X2": -24.511723, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -13.560315, "X2": 14.112469, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": -31.888487, "X2": -25.387936, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 25.595566, "X2": -33.288197, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 17.77903, "X2": 2.2943015, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -1.2710183, "X2": -14.292207, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -12.701963, "X2": 6.540723, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -10.599251, "X2": -14.930558, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -40.32882, "X2": -14.779669, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 13.298612, "X2": 24.56578, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 10.146995, "X2": -32.698715, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -13.184145, "X2": 18.05904, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 32.76029, "X2": -17.142538, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 38.82628, "X2": -7.4685645, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -18.50846, "X2": -11.941418, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 34.280045, "X2": -14.8336735, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -16.712585, "X2": -5.524171, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -14.1449585, "X2": -17.436424, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -24.232542, "X2": -6.7849073, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -38.19389, "X2": -10.131686, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -11.890057, "X2": -29.865673, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -12.454628, "X2": -19.42449, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 4.2469583, "X2": -25.729677, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 30.221487, "X2": -9.767967, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -9.332784, "X2": -15.55334, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 29.530907, "X2": -15.475123, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 31.068136, "X2": -4.43709, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 38.56418, "X2": -7.515099, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 30.051058, "X2": -16.413893, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -4.03456, "X2": -4.647235, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 21.56285, "X2": -3.6951826, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": 14.32029, "X2": -4.260195, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -40.32807, "X2": -14.779175, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 23.36371, "X2": -4.1615963, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": -19.43737, "X2": -19.683521, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -27.65426, "X2": -8.275873, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": 15.8256645, "X2": -29.021992, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 4.967578, "X2": -23.066877, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 6.31187, "X2": -22.660048, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 30.078571, "X2": -10.979523, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -11.000744, "X2": -14.918365, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -31.310148, "X2": -9.933017, "Nation": "Bulgarian", "language_family": "Slavic"}, {"X1": 17.0181, "X2": -7.2202673, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 5.8951306, "X2": -19.675072, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -8.051365, "X2": -4.3595285, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 35.485134, "X2": -3.8731375, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -4.9087844, "X2": -25.06134, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -27.379335, "X2": -10.205511, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 6.400587, "X2": -21.48434, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -14.291835, "X2": -17.19119, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 20.462246, "X2": -10.742588, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -12.953335, "X2": 1.3378954, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 4.3075247, "X2": 10.409672, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -39.66552, "X2": 3.2749515, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -35.416164, "X2": -1.7677062, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -0.5664988, "X2": -24.064516, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 13.786904, "X2": -8.378399, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 5.513666, "X2": -27.345709, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -38.17791, "X2": -10.146948, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 20.817585, "X2": -10.886928, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 37.55964, "X2": -7.5937037, "Nation": "Bulgarian", "language_family": "Slavic"}, {"X1": -16.499962, "X2": -15.774546, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 3.2494597, "X2": -23.811737, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 21.633533, "X2": -33.91565, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 33.96548, "X2": -25.67879, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 25.623499, "X2": -33.32017, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 18.507399, "X2": -12.742397, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 17.726036, "X2": 1.7916023, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -31.133207, "X2": -8.579982, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 7.295456, "X2": -28.205898, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 24.585398, "X2": -29.395481, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -9.387771, "X2": -10.516911, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 34.519814, "X2": -8.703772, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 31.070967, "X2": -4.6688485, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -36.831524, "X2": -11.520588, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 13.303962, "X2": 24.57433, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -9.112122, "X2": -4.7373548, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 9.598321, "X2": -30.391457, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -11.21503, "X2": -11.61832, "Nation": "Bulgarian", "language_family": "Slavic"}, {"X1": 29.82722, "X2": -11.313745, "Nation": "Lithuanian", "language_family": "Slavic"}, {"X1": 26.3642, "X2": -4.2450867, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": -35.33453, "X2": -1.7605617, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 22.79592, "X2": -30.065176, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 28.397896, "X2": -14.830123, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -25.610312, "X2": -9.134413, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 4.5574656, "X2": 23.968145, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": -31.866337, "X2": -25.384466, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -4.9970374, "X2": -25.06322, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 9.64179, "X2": -23.848475, "Nation": "Bulgarian", "language_family": "Slavic"}, {"X1": 12.574866, "X2": -33.753235, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 31.515585, "X2": -12.319085, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 11.773969, "X2": 11.564832, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 32.196327, "X2": -13.291839, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 28.371742, "X2": -7.293865, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": 14.172158, "X2": -19.248077, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 8.047967, "X2": -26.625465, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 10.56637, "X2": -26.745384, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 31.463371, "X2": -13.533447, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -31.269804, "X2": -20.834112, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -10.290006, "X2": -10.082733, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 27.62819, "X2": -16.382088, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 34.49258, "X2": -8.696761, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 27.653252, "X2": -14.022806, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 0.7942077, "X2": 5.371467, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": -21.951775, "X2": -6.398306, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -31.292582, "X2": -5.1259713, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -23.530346, "X2": -14.806401, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 24.438158, "X2": 1.5819608, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 32.08948, "X2": -6.5114484, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 6.5552754, "X2": -26.445974, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 29.301046, "X2": -7.1139884, "Nation": "Bulgarian", "language_family": "Slavic"}, {"X1": 16.142197, "X2": -26.359612, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 24.562952, "X2": -29.582716, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 2.1946287, "X2": 11.986397, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 21.725798, "X2": -11.001682, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 36.519566, "X2": 13.413004, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 16.08577, "X2": -28.081287, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 9.563413, "X2": -30.288012, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 22.702377, "X2": -13.653002, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 15.659606, "X2": 15.394229, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": 33.073284, "X2": -12.804622, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 13.128658, "X2": -7.6145196, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": -35.618656, "X2": 0.6943438, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -11.967025, "X2": -29.832237, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -14.9745245, "X2": -11.107215, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 16.215992, "X2": -16.086447, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 8.773467, "X2": 5.803354, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 24.073204, "X2": -28.934202, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": -20.064402, "X2": -3.4898193, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 10.76344, "X2": -21.320915, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -16.294302, "X2": -5.7326136, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -35.387547, "X2": -1.7531061, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -12.449941, "X2": -19.375586, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": -26.23554, "X2": -14.973701, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -10.185307, "X2": -10.123489, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -23.008385, "X2": -11.359082, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -27.413706, "X2": -9.775618, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 35.52734, "X2": -3.9130921, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 1.2868164, "X2": 10.968555, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 12.710559, "X2": -20.339743, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 16.107538, "X2": -22.297491, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 28.219503, "X2": -15.755859, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -3.8835447, "X2": -2.089502, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 27.97333, "X2": -27.202461, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": 15.571665, "X2": 14.621026, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -38.265083, "X2": 0.60818374, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -21.533281, "X2": -8.496317, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 29.742365, "X2": -15.678521, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -20.59162, "X2": -5.966466, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 18.744675, "X2": -21.040989, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 16.0286, "X2": 10.871191, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -9.307819, "X2": -10.057967, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -13.731364, "X2": -10.782961, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 41.72053, "X2": 11.875193, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -21.996742, "X2": -21.953197, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -24.914446, "X2": -11.597103, "Nation": "Bulgarian", "language_family": "Slavic"}, {"X1": -28.403107, "X2": -1.1495116, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -18.787006, "X2": 0.9912231, "Nation": "Bulgarian", "language_family": "Slavic"}, {"X1": -21.723944, "X2": -18.040268, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -5.6125584, "X2": 1.0207146, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 33.964138, "X2": -25.677794, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 10.426632, "X2": -27.880173, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 9.263425, "X2": -22.83859, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -32.122894, "X2": -0.32170802, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 33.931744, "X2": -16.04637, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -31.472034, "X2": 0.086629786, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 15.570041, "X2": 25.806503, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -22.04778, "X2": -17.38111, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 29.593098, "X2": -6.9212594, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 3.8562002, "X2": 18.639475, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -15.227318, "X2": -19.831749, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -21.744764, "X2": -6.4450903, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 3.8247318, "X2": 18.695265, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 25.370794, "X2": -28.680466, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 6.9794807, "X2": -28.372978, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -9.789226, "X2": -5.8877206, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 5.3050838, "X2": -27.439102, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 37.37967, "X2": -7.5495133, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 37.452953, "X2": -7.7140346, "Nation": "Bulgarian", "language_family": "Slavic"}, {"X1": 12.872037, "X2": -17.760593, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 18.74707, "X2": -21.06151, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -23.266563, "X2": 7.292888, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 24.589485, "X2": -32.10538, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 33.964947, "X2": -25.679325, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": -13.906002, "X2": 2.90042, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 33.024998, "X2": -18.061325, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -12.335383, "X2": -5.5548306, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 32.17557, "X2": -13.240664, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -12.102467, "X2": -19.121418, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -12.019151, "X2": -29.870718, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 6.660866, "X2": -21.533699, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 41.721138, "X2": 11.874396, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 21.635828, "X2": -3.4597936, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 10.134629, "X2": -32.683083, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 26.579336, "X2": -4.455489, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 13.280097, "X2": -19.79136, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": 4.642136, "X2": 9.162493, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -22.272972, "X2": -17.143513, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -20.426485, "X2": -4.1621666, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -35.334064, "X2": -1.7737322, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 3.0071356, "X2": -23.730268, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 35.103897, "X2": -14.6858635, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 18.382772, "X2": -10.963789, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -39.670464, "X2": 3.2822626, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -14.259368, "X2": 1.4465302, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -5.689679, "X2": -15.789219, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 8.488079, "X2": 16.689249, "Nation": "Polish", "language_family": "Slavic"}, {"X1": -22.806831, "X2": -35.18624, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 22.401535, "X2": -8.031125, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -27.732641, "X2": -12.227613, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 32.76818, "X2": -13.465939, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 24.52367, "X2": -31.281181, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -14.91205, "X2": 25.21507, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -13.203448, "X2": -8.878114, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -17.94078, "X2": -17.244576, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 32.888176, "X2": 5.588184, "Nation": "Croatian", "language_family": "Slavic"}, {"X1": 20.620565, "X2": 0.84766525, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 15.742727, "X2": -20.485008, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -4.1723175, "X2": -27.8013, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 33.014027, "X2": -18.024805, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -5.866652, "X2": -18.18841, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -29.312696, "X2": -9.916212, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 30.006264, "X2": -16.268831, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 21.545881, "X2": 16.402119, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 15.629187, "X2": -29.67651, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 33.75945, "X2": -16.041779, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -14.329793, "X2": 3.9026544, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -6.3216066, "X2": -21.54719, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 5.8176355, "X2": -24.511024, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -6.0511947, "X2": 14.374314, "Nation": "Bulgarian", "language_family": "Slavic"}, {"X1": 14.341569, "X2": -2.6301582, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 8.46503, "X2": -27.82168, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -9.209881, "X2": 36.981888, "Nation": "Bulgarian", "language_family": "Slavic"}, {"X1": 9.554937, "X2": -30.27608, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 18.306805, "X2": -14.804173, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -13.927952, "X2": -27.46275, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 15.921481, "X2": -28.652039, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 0.14368108, "X2": -20.001001, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": 32.65326, "X2": -16.90889, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 30.051373, "X2": -15.091879, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": -14.236002, "X2": -7.1635804, "Nation": "Russian", "language_family": "Slavic"}, {"X1": -31.867117, "X2": -25.38634, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -31.863863, "X2": -25.386772, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -21.682467, "X2": -1.0052778, "Nation": "Serbian", "language_family": "Slavic"}, {"X1": 23.816088, "X2": -32.87292, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 8.405522, "X2": -30.493546, "Nation": "Ukrainian", "language_family": "Slavic"}, {"X1": 34.48819, "X2": -14.717157, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 30.514944, "X2": 1.071128, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 7.6535873, "X2": -19.154352, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": -8.145647, "X2": -4.3987017, "Nation": "Slavic", "language_family": "Slavic"}, {"X1": 2.493967, "X2": -26.76521, "Nation": "Czechoslovak", "language_family": "Slavic"}, {"X1": -8.006229, "X2": 6.271363, "Nation": "Polish", "language_family": "Slavic"}, {"X1": 37.251133, "X2": -8.731932, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 20.154846, "X2": 2.03752, "Nation": "Russian", "language_family": "Slavic"}, {"X1": 28.067266, "X2": 30.26233, "Nation": "French", "language_family": "Italic"}, {"X1": -6.010457, "X2": 29.644852, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -28.970673, "X2": -0.3129294, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -0.46943912, "X2": -21.73061, "Nation": "French", "language_family": "Italic"}, {"X1": 7.117071, "X2": -9.662554, "Nation": "French", "language_family": "Italic"}, {"X1": -22.756392, "X2": -12.799753, "Nation": "Italian", "language_family": "Italic"}, {"X1": 2.3353522, "X2": 5.0854406, "Nation": "French", "language_family": "Italic"}, {"X1": 7.383065, "X2": -23.621988, "Nation": "Italian", "language_family": "Italic"}, {"X1": 2.7223682, "X2": -23.933296, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 24.132254, "X2": 26.252348, "Nation": "French", "language_family": "Italic"}, {"X1": 15.700805, "X2": -0.78275263, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -9.063304, "X2": -6.0408816, "Nation": "French", "language_family": "Italic"}, {"X1": 8.883033, "X2": 2.6519887, "Nation": "Italian", "language_family": "Italic"}, {"X1": -21.854868, "X2": -12.604337, "Nation": "Italian", "language_family": "Italic"}, {"X1": -13.193539, "X2": 12.983721, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 12.492953, "X2": 0.5093309, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -12.723218, "X2": -12.395248, "Nation": "French", "language_family": "Italic"}, {"X1": -2.5237875, "X2": -10.977192, "Nation": "French", "language_family": "Italic"}, {"X1": -3.4850156, "X2": -1.8127526, "Nation": "Italian", "language_family": "Italic"}, {"X1": -2.3138816, "X2": 1.4821776, "Nation": "Italian", "language_family": "Italic"}, {"X1": 28.492105, "X2": 29.952524, "Nation": "French", "language_family": "Italic"}, {"X1": 8.107635, "X2": -0.42335021, "Nation": "French", "language_family": "Italic"}, {"X1": -4.111394, "X2": -4.157778, "Nation": "Italian", "language_family": "Italic"}, {"X1": 33.654575, "X2": -5.662145, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 29.941332, "X2": 27.033167, "Nation": "French", "language_family": "Italic"}, {"X1": -28.06411, "X2": -4.2246675, "Nation": "Italian", "language_family": "Italic"}, {"X1": 2.2740319, "X2": -13.930152, "Nation": "French", "language_family": "Italic"}, {"X1": 32.695793, "X2": 22.106716, "Nation": "Italian", "language_family": "Italic"}, {"X1": -1.9119139, "X2": -7.841427, "Nation": "French", "language_family": "Italic"}, {"X1": 22.037348, "X2": 1.9709352, "Nation": "Romanian", "language_family": "Italic"}, {"X1": -29.781805, "X2": -8.462687, "Nation": "Italian", "language_family": "Italic"}, {"X1": -6.223513, "X2": 1.3588576, "Nation": "Italian", "language_family": "Italic"}, {"X1": -0.9050495, "X2": -14.190726, "Nation": "French", "language_family": "Italic"}, {"X1": -22.458277, "X2": -13.017035, "Nation": "French", "language_family": "Italic"}, {"X1": 8.802336, "X2": -5.201044, "Nation": "French", "language_family": "Italic"}, {"X1": -9.526926, "X2": 5.7301126, "Nation": "Italian", "language_family": "Italic"}, {"X1": 29.951637, "X2": 29.368155, "Nation": "French", "language_family": "Italic"}, {"X1": -8.686361, "X2": 8.090215, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -1.8269455, "X2": -0.31464538, "Nation": "French", "language_family": "Italic"}, {"X1": 13.565724, "X2": -0.44557855, "Nation": "French", "language_family": "Italic"}, {"X1": -31.681084, "X2": -17.464724, "Nation": "Italian", "language_family": "Italic"}, {"X1": -30.866152, "X2": 0.52685875, "Nation": "Italian", "language_family": "Italic"}, {"X1": -4.760292, "X2": -0.9570916, "Nation": "Italian", "language_family": "Italic"}, {"X1": 10.914944, "X2": -0.36992615, "Nation": "Italian", "language_family": "Italic"}, {"X1": 26.79308, "X2": -10.356599, "Nation": "Italian", "language_family": "Italic"}, {"X1": -8.089681, "X2": -12.448028, "Nation": "Italian", "language_family": "Italic"}, {"X1": -10.24634, "X2": 13.954248, "Nation": "French", "language_family": "Italic"}, {"X1": -18.52327, "X2": 8.373103, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -10.97138, "X2": -5.2564893, "Nation": "Spanish", "language_family": "Italic"}, {"X1": 31.821964, "X2": 29.594217, "Nation": "French", "language_family": "Italic"}, {"X1": -29.075285, "X2": -22.060822, "Nation": "French", "language_family": "Italic"}, {"X1": -17.863796, "X2": 7.2919374, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 5.038779, "X2": 17.102613, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 22.541801, "X2": 1.55527, "Nation": "Romanian", "language_family": "Italic"}, {"X1": -10.09302, "X2": -2.1761785, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -3.0781536, "X2": 2.0738022, "Nation": "Italian", "language_family": "Italic"}, {"X1": 4.8399324, "X2": -18.50361, "Nation": "Italian", "language_family": "Italic"}, {"X1": 1.6635053, "X2": -5.988337, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 29.271915, "X2": 27.979422, "Nation": "French", "language_family": "Italic"}, {"X1": 13.112991, "X2": 4.2271404, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 3.5500014, "X2": -17.2483, "Nation": "Italian", "language_family": "Italic"}, {"X1": 5.2054076, "X2": -11.993707, "Nation": "French", "language_family": "Italic"}, {"X1": -4.413778, "X2": 11.577449, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 8.822366, "X2": -10.637263, "Nation": "French", "language_family": "Italic"}, {"X1": 4.2545176, "X2": 3.2968915, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 14.023275, "X2": 6.1649737, "Nation": "Spanish", "language_family": "Italic"}, {"X1": -25.061182, "X2": 0.5498746, "Nation": "Italian", "language_family": "Italic"}, {"X1": -23.534897, "X2": 17.893496, "Nation": "Cataloanian", "language_family": "Italic"}, {"X1": 11.390789, "X2": -7.985376, "Nation": "French", "language_family": "Italic"}, {"X1": 34.83997, "X2": -2.8107831, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 2.9453385, "X2": -21.938122, "Nation": "Italian", "language_family": "Italic"}, {"X1": 6.382461, "X2": -24.725697, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 0.8038865, "X2": 23.772642, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -20.353987, "X2": -1.5387168, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 5.551171, "X2": -23.835213, "Nation": "Italian", "language_family": "Italic"}, {"X1": 3.4421096, "X2": -12.999759, "Nation": "French", "language_family": "Italic"}, {"X1": -2.9129586, "X2": -20.791916, "Nation": "Italian", "language_family": "Italic"}, {"X1": 12.506827, "X2": 11.447528, "Nation": "French", "language_family": "Italic"}, {"X1": 17.406067, "X2": 7.3805513, "Nation": "Romanian", "language_family": "Italic"}, {"X1": -1.1883563, "X2": -27.056734, "Nation": "Italian", "language_family": "Italic"}, {"X1": 28.840307, "X2": -5.0153637, "Nation": "Bukovinian", "language_family": "Italic"}, {"X1": 3.7247539, "X2": -13.711516, "Nation": "French", "language_family": "Italic"}, {"X1": 1.0933117, "X2": 0.5818803, "Nation": "Italian", "language_family": "Italic"}, {"X1": -1.1114664, "X2": -9.839915, "Nation": "French", "language_family": "Italic"}, {"X1": 2.5028105, "X2": -5.6185985, "Nation": "French", "language_family": "Italic"}, {"X1": 28.25798, "X2": 25.784151, "Nation": "French", "language_family": "Italic"}, {"X1": 0.8582048, "X2": -15.249199, "Nation": "French", "language_family": "Italic"}, {"X1": 19.019812, "X2": 0.7360619, "Nation": "Bukovinian", "language_family": "Italic"}, {"X1": 4.837556, "X2": -10.887481, "Nation": "French", "language_family": "Italic"}, {"X1": -16.419935, "X2": -2.043655, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 0.7172009, "X2": 33.539497, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 15.964677, "X2": -9.153922, "Nation": "French", "language_family": "Italic"}, {"X1": 2.2605357, "X2": -6.744056, "Nation": "French", "language_family": "Italic"}, {"X1": -20.423168, "X2": 1.008298, "Nation": "Italian", "language_family": "Italic"}, {"X1": -15.075264, "X2": -24.571869, "Nation": "French", "language_family": "Italic"}, {"X1": 0.7292129, "X2": -13.036041, "Nation": "French", "language_family": "Italic"}, {"X1": -18.252623, "X2": -8.66826, "Nation": "Italian", "language_family": "Italic"}, {"X1": -6.677292, "X2": 28.252388, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 1.8416036, "X2": -2.6455767, "Nation": "French", "language_family": "Italic"}, {"X1": -19.936054, "X2": -9.258501, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 5.615179, "X2": 3.7391748, "Nation": "French", "language_family": "Italic"}, {"X1": 3.9233057, "X2": -9.988424, "Nation": "French", "language_family": "Italic"}, {"X1": 7.897116, "X2": -4.126915, "Nation": "French", "language_family": "Italic"}, {"X1": -31.593233, "X2": -17.513985, "Nation": "Italian", "language_family": "Italic"}, {"X1": -30.622154, "X2": -6.991906, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -24.4974, "X2": 0.2843675, "Nation": "Italian", "language_family": "Italic"}, {"X1": -2.2137911, "X2": 21.561045, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 7.506653, "X2": 13.790918, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 27.52688, "X2": 26.687868, "Nation": "French", "language_family": "Italic"}, {"X1": -3.5934963, "X2": 0.47798535, "Nation": "Italian", "language_family": "Italic"}, {"X1": 30.934587, "X2": 28.182375, "Nation": "French", "language_family": "Italic"}, {"X1": 9.444689, "X2": -3.2387443, "Nation": "French", "language_family": "Italic"}, {"X1": -43.02693, "X2": 0.29974234, "Nation": "French", "language_family": "Italic"}, {"X1": 15.50535, "X2": 26.17491, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 22.810066, "X2": -0.13369752, "Nation": "Spanish", "language_family": "Italic"}, {"X1": 4.88704, "X2": 1.0892975, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -23.07159, "X2": -8.46172, "Nation": "French", "language_family": "Italic"}, {"X1": -5.3756404, "X2": -19.79881, "Nation": "French", "language_family": "Italic"}, {"X1": -19.195574, "X2": 3.358972, "Nation": "Romanian", "language_family": "Italic"}, {"X1": -0.068917006, "X2": -6.2998605, "Nation": "French", "language_family": "Italic"}, {"X1": -27.438623, "X2": -20.527613, "Nation": "Italian", "language_family": "Italic"}, {"X1": -14.028454, "X2": 0.4138173, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -6.4463487, "X2": -10.741271, "Nation": "Italian", "language_family": "Italic"}, {"X1": 34.617283, "X2": -3.596391, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 29.4469, "X2": 27.9406, "Nation": "French", "language_family": "Italic"}, {"X1": -11.169527, "X2": -21.353188, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -0.6339085, "X2": 0.21685255, "Nation": "Italian", "language_family": "Italic"}, {"X1": 3.1977918, "X2": -1.0145563, "Nation": "Italian", "language_family": "Italic"}, {"X1": 6.6610966, "X2": 4.3028836, "Nation": "Italian", "language_family": "Italic"}, {"X1": 9.3952465, "X2": -6.9348974, "Nation": "French", "language_family": "Italic"}, {"X1": -3.5689738, "X2": -12.726444, "Nation": "French", "language_family": "Italic"}, {"X1": -1.4614493, "X2": -10.715585, "Nation": "French", "language_family": "Italic"}, {"X1": 9.074949, "X2": 0.5343563, "Nation": "French", "language_family": "Italic"}, {"X1": -23.235674, "X2": -8.519731, "Nation": "French", "language_family": "Italic"}, {"X1": 6.82203, "X2": 1.537158, "Nation": "French", "language_family": "Italic"}, {"X1": 13.255469, "X2": -5.8303876, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 7.737624, "X2": -12.343741, "Nation": "French", "language_family": "Italic"}, {"X1": -11.7801285, "X2": 14.831208, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 7.9144835, "X2": -8.926179, "Nation": "French", "language_family": "Italic"}, {"X1": -1.5201935, "X2": -3.4514, "Nation": "French", "language_family": "Italic"}, {"X1": -28.11274, "X2": -7.495795, "Nation": "Italian", "language_family": "Italic"}, {"X1": 34.952522, "X2": -3.2996788, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 31.676477, "X2": 26.894424, "Nation": "French", "language_family": "Italic"}, {"X1": 2.475025, "X2": -13.394838, "Nation": "French", "language_family": "Italic"}, {"X1": -12.506293, "X2": -8.013507, "Nation": "Italian", "language_family": "Italic"}, {"X1": 5.148101, "X2": -9.48509, "Nation": "French", "language_family": "Italic"}, {"X1": 7.108553, "X2": 0.34581846, "Nation": "French", "language_family": "Italic"}, {"X1": -7.8962126, "X2": -10.835295, "Nation": "Italian", "language_family": "Italic"}, {"X1": 10.806117, "X2": -11.410942, "Nation": "French", "language_family": "Italic"}, {"X1": 2.1005363, "X2": -9.55659, "Nation": "Italian", "language_family": "Italic"}, {"X1": -19.973911, "X2": 18.93392, "Nation": "Bukovinian", "language_family": "Italic"}, {"X1": 9.592025, "X2": 14.087163, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -17.147074, "X2": -8.709433, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -12.044167, "X2": -10.645655, "Nation": "Italian", "language_family": "Italic"}, {"X1": 27.561956, "X2": 27.519156, "Nation": "French", "language_family": "Italic"}, {"X1": 14.037444, "X2": 5.815087, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 7.7539887, "X2": -11.110103, "Nation": "French", "language_family": "Italic"}, {"X1": -10.002564, "X2": 4.0804105, "Nation": "Italian", "language_family": "Italic"}, {"X1": 1.7632926, "X2": 34.83453, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -9.867844, "X2": -12.677426, "Nation": "Italian", "language_family": "Italic"}, {"X1": -7.0315814, "X2": -7.372981, "Nation": "Italian", "language_family": "Italic"}, {"X1": -20.19961, "X2": -9.2970495, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 1.2816643, "X2": -3.9930308, "Nation": "Italian", "language_family": "Italic"}, {"X1": 11.778125, "X2": 14.653588, "Nation": "Italian", "language_family": "Italic"}, {"X1": 3.1587775, "X2": -21.725855, "Nation": "Italian", "language_family": "Italic"}, {"X1": 1.4879656, "X2": 16.130695, "Nation": "French", "language_family": "Italic"}, {"X1": 13.943762, "X2": 12.914416, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 14.82152, "X2": 3.6756825, "Nation": "French", "language_family": "Italic"}, {"X1": -8.779036, "X2": -14.336995, "Nation": "French", "language_family": "Italic"}, {"X1": -27.144474, "X2": 5.9590626, "Nation": "Spanish", "language_family": "Italic"}, {"X1": 17.54663, "X2": -10.6010475, "Nation": "French", "language_family": "Italic"}, {"X1": -14.686132, "X2": -21.949976, "Nation": "Spanish", "language_family": "Italic"}, {"X1": 28.532856, "X2": 28.007545, "Nation": "French", "language_family": "Italic"}, {"X1": 29.065317, "X2": 25.94711, "Nation": "French", "language_family": "Italic"}, {"X1": -22.098696, "X2": 29.283073, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -23.687538, "X2": -9.223172, "Nation": "Spanish", "language_family": "Italic"}, {"X1": 1.6885055, "X2": 4.1400666, "Nation": "Italian", "language_family": "Italic"}, {"X1": -11.069918, "X2": 12.370471, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 11.59827, "X2": -1.0037814, "Nation": "French", "language_family": "Italic"}, {"X1": -17.95873, "X2": -0.4441389, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 4.304933, "X2": -8.682141, "Nation": "French", "language_family": "Italic"}, {"X1": -12.247005, "X2": -17.155142, "Nation": "Spanish", "language_family": "Italic"}, {"X1": -22.485378, "X2": -7.96009, "Nation": "Italian", "language_family": "Italic"}, {"X1": 14.981146, "X2": -6.143347, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 4.803386, "X2": -13.460896, "Nation": "French", "language_family": "Italic"}, {"X1": -18.534485, "X2": -15.546376, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 13.905474, "X2": 9.419663, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -13.389856, "X2": -13.323074, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 7.519787, "X2": -5.932867, "Nation": "French", "language_family": "Italic"}, {"X1": -10.494291, "X2": -19.231728, "Nation": "French", "language_family": "Italic"}, {"X1": 22.633041, "X2": -30.185795, "Nation": "French", "language_family": "Italic"}, {"X1": -6.1911783, "X2": 30.990578, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 5.6490555, "X2": -10.911366, "Nation": "French", "language_family": "Italic"}, {"X1": 2.1548474, "X2": 2.5940313, "Nation": "French", "language_family": "Italic"}, {"X1": -29.175404, "X2": 4.4397044, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 4.2417154, "X2": -12.935092, "Nation": "French", "language_family": "Italic"}, {"X1": 28.31347, "X2": 25.96605, "Nation": "French", "language_family": "Italic"}, {"X1": 1.3632104, "X2": -14.051269, "Nation": "French", "language_family": "Italic"}, {"X1": 0.26865926, "X2": -0.82547, "Nation": "French", "language_family": "Italic"}, {"X1": -0.5142801, "X2": -14.294605, "Nation": "French", "language_family": "Italic"}, {"X1": -7.9993005, "X2": 7.277585, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 8.898354, "X2": -10.00935, "Nation": "French", "language_family": "Italic"}, {"X1": 30.61293, "X2": 27.93802, "Nation": "French", "language_family": "Italic"}, {"X1": 11.489505, "X2": 26.61774, "Nation": "Italian", "language_family": "Italic"}, {"X1": -8.708712, "X2": 4.6807756, "Nation": "Italian", "language_family": "Italic"}, {"X1": 10.4657755, "X2": 3.256652, "Nation": "Italian", "language_family": "Italic"}, {"X1": 10.463586, "X2": -8.887675, "Nation": "French", "language_family": "Italic"}, {"X1": 29.46001, "X2": 25.412374, "Nation": "French", "language_family": "Italic"}, {"X1": -0.18842936, "X2": -15.673284, "Nation": "French", "language_family": "Italic"}, {"X1": 3.5779774, "X2": -17.283735, "Nation": "Spanish", "language_family": "Italic"}, {"X1": -1.2463585, "X2": -1.6357901, "Nation": "French", "language_family": "Italic"}, {"X1": 6.839638, "X2": -7.564392, "Nation": "French", "language_family": "Italic"}, {"X1": -6.075912, "X2": -13.289285, "Nation": "Italian", "language_family": "Italic"}, {"X1": 14.089589, "X2": 5.4762964, "Nation": "French", "language_family": "Italic"}, {"X1": -21.84056, "X2": -17.421215, "Nation": "Italian", "language_family": "Italic"}, {"X1": -15.5026045, "X2": 0.27716163, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -18.502892, "X2": -10.163915, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 10.354367, "X2": -9.015738, "Nation": "French", "language_family": "Italic"}, {"X1": 5.9201536, "X2": -13.0567875, "Nation": "French", "language_family": "Italic"}, {"X1": 12.267113, "X2": -28.535288, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 30.211136, "X2": 28.078335, "Nation": "French", "language_family": "Italic"}, {"X1": -1.5764449, "X2": -4.6773505, "Nation": "Italian", "language_family": "Italic"}, {"X1": -31.647469, "X2": 7.7351255, "Nation": "French", "language_family": "Italic"}, {"X1": 34.84888, "X2": -4.5495496, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 31.613697, "X2": -2.873845, "Nation": "Italian", "language_family": "Italic"}, {"X1": -5.344359, "X2": 3.3903525, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 7.8135386, "X2": 4.0592985, "Nation": "Italian", "language_family": "Italic"}, {"X1": -23.673288, "X2": -25.506311, "Nation": "French", "language_family": "Italic"}, {"X1": -15.476699, "X2": -13.470433, "Nation": "French", "language_family": "Italic"}, {"X1": 18.952015, "X2": -8.800918, "Nation": "Spanish", "language_family": "Italic"}, {"X1": -1.0387753, "X2": -11.212895, "Nation": "Italian", "language_family": "Italic"}, {"X1": -24.562881, "X2": -6.346787, "Nation": "Italian", "language_family": "Italic"}, {"X1": -0.51763785, "X2": -24.085455, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 29.207972, "X2": 28.63274, "Nation": "French", "language_family": "Italic"}, {"X1": 4.9655323, "X2": 4.6927133, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -18.342428, "X2": 5.658581, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 13.572224, "X2": -0.035234522, "Nation": "Italian", "language_family": "Italic"}, {"X1": 6.0029564, "X2": -14.707644, "Nation": "French", "language_family": "Italic"}, {"X1": -23.6691, "X2": -25.508045, "Nation": "French", "language_family": "Italic"}, {"X1": 29.515066, "X2": 27.525312, "Nation": "French", "language_family": "Italic"}, {"X1": 12.33944, "X2": 31.667524, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 4.946157, "X2": -25.318205, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -5.3964725, "X2": 1.7787702, "Nation": "Italian", "language_family": "Italic"}, {"X1": 26.952084, "X2": 28.46786, "Nation": "French", "language_family": "Italic"}, {"X1": 2.3620813, "X2": -6.0419807, "Nation": "French", "language_family": "Italic"}, {"X1": -8.276187, "X2": -12.451771, "Nation": "French", "language_family": "Italic"}, {"X1": 27.326302, "X2": 25.264175, "Nation": "French", "language_family": "Italic"}, {"X1": 18.976887, "X2": 7.2456255, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 13.636293, "X2": 9.807925, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 8.084415, "X2": -16.486914, "Nation": "French", "language_family": "Italic"}, {"X1": 2.7989457, "X2": -4.5208726, "Nation": "French", "language_family": "Italic"}, {"X1": -24.194292, "X2": 0.054170147, "Nation": "French", "language_family": "Italic"}, {"X1": -22.3931, "X2": -13.023081, "Nation": "French", "language_family": "Italic"}, {"X1": -23.198803, "X2": -2.055565, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 7.314864, "X2": -9.164719, "Nation": "French", "language_family": "Italic"}, {"X1": 6.3884716, "X2": 11.121346, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 25.473776, "X2": -8.418668, "Nation": "French", "language_family": "Italic"}, {"X1": 23.799936, "X2": -10.621781, "Nation": "Spanish", "language_family": "Italic"}, {"X1": -19.975777, "X2": -10.996972, "Nation": "Italian", "language_family": "Italic"}, {"X1": -3.0152287, "X2": 8.653771, "Nation": "Italian", "language_family": "Italic"}, {"X1": -0.62121385, "X2": 9.773187, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 10.591751, "X2": -19.630667, "Nation": "Italian", "language_family": "Italic"}, {"X1": -23.09584, "X2": -25.463535, "Nation": "French", "language_family": "Italic"}, {"X1": -43.026386, "X2": 0.29774728, "Nation": "French", "language_family": "Italic"}, {"X1": -19.44846, "X2": -11.858459, "Nation": "Italian", "language_family": "Italic"}, {"X1": -16.822166, "X2": 9.248543, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -31.153675, "X2": 9.187715, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 26.062595, "X2": 23.865025, "Nation": "French", "language_family": "Italic"}, {"X1": 27.785858, "X2": 26.54618, "Nation": "French", "language_family": "Italic"}, {"X1": 22.590714, "X2": 27.09404, "Nation": "French", "language_family": "Italic"}, {"X1": 1.5392655, "X2": -17.326069, "Nation": "Spanish", "language_family": "Italic"}, {"X1": 4.559503, "X2": 3.48843, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 10.954934, "X2": 5.5088096, "Nation": "Italian", "language_family": "Italic"}, {"X1": -35.97478, "X2": -13.654521, "Nation": "Italian", "language_family": "Italic"}, {"X1": 20.507063, "X2": 1.9069641, "Nation": "Italian", "language_family": "Italic"}, {"X1": 4.0557466, "X2": -3.224999, "Nation": "French", "language_family": "Italic"}, {"X1": -16.174578, "X2": -13.239934, "Nation": "French", "language_family": "Italic"}, {"X1": 26.975483, "X2": 28.83714, "Nation": "French", "language_family": "Italic"}, {"X1": 4.851788, "X2": -1.4711652, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -29.934952, "X2": 4.6468525, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 21.429554, "X2": 2.169605, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 10.05249, "X2": -7.508959, "Nation": "French", "language_family": "Italic"}, {"X1": 10.631592, "X2": -11.331931, "Nation": "French", "language_family": "Italic"}, {"X1": 22.513855, "X2": -1.2346106, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 26.015226, "X2": -17.876986, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 5.349657, "X2": -10.065627, "Nation": "French", "language_family": "Italic"}, {"X1": 8.748151, "X2": 8.5123825, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -23.642866, "X2": -14.622609, "Nation": "Italian", "language_family": "Italic"}, {"X1": 10.911446, "X2": -19.31883, "Nation": "Italian", "language_family": "Italic"}, {"X1": -28.617552, "X2": 2.9282067, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -21.641848, "X2": -0.7511574, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 6.774964, "X2": -24.74557, "Nation": "Italian", "language_family": "Italic"}, {"X1": 28.898369, "X2": 27.7967, "Nation": "French", "language_family": "Italic"}, {"X1": -0.43263465, "X2": -22.559923, "Nation": "Italian", "language_family": "Italic"}, {"X1": -22.365847, "X2": 17.633781, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 5.8747163, "X2": -11.651841, "Nation": "French", "language_family": "Italic"}, {"X1": -4.5524387, "X2": 32.967678, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -10.8101635, "X2": -17.304825, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 1.8089589, "X2": -1.8560411, "Nation": "French", "language_family": "Italic"}, {"X1": 31.70557, "X2": 27.118334, "Nation": "French", "language_family": "Italic"}, {"X1": -35.453636, "X2": -15.113055, "Nation": "Italian", "language_family": "Italic"}, {"X1": -16.717968, "X2": -11.292251, "Nation": "Italian", "language_family": "Italic"}, {"X1": -2.8971045, "X2": -3.9378073, "Nation": "French", "language_family": "Italic"}, {"X1": 5.3687253, "X2": -8.436186, "Nation": "French", "language_family": "Italic"}, {"X1": 10.659275, "X2": -16.319555, "Nation": "French", "language_family": "Italic"}, {"X1": -30.951889, "X2": -17.819046, "Nation": "Italian", "language_family": "Italic"}, {"X1": 10.511332, "X2": 22.590929, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 6.273061, "X2": -8.650544, "Nation": "French", "language_family": "Italic"}, {"X1": 16.321335, "X2": -9.322667, "Nation": "French", "language_family": "Italic"}, {"X1": -26.516823, "X2": -22.324875, "Nation": "Italian", "language_family": "Italic"}, {"X1": -19.037699, "X2": -9.130528, "Nation": "Italian", "language_family": "Italic"}, {"X1": 11.129228, "X2": -5.654574, "Nation": "French", "language_family": "Italic"}, {"X1": 8.309688, "X2": -9.6930895, "Nation": "French", "language_family": "Italic"}, {"X1": -12.355594, "X2": -10.582414, "Nation": "Italian", "language_family": "Italic"}, {"X1": 0.088314906, "X2": -0.046786305, "Nation": "French", "language_family": "Italic"}, {"X1": -2.4728596, "X2": -10.009945, "Nation": "French", "language_family": "Italic"}, {"X1": 9.655875, "X2": 3.881093, "Nation": "French", "language_family": "Italic"}, {"X1": 9.242339, "X2": -0.63824767, "Nation": "Italian", "language_family": "Italic"}, {"X1": 1.626684, "X2": -19.9336, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -3.5352435, "X2": 1.0462121, "Nation": "Italian", "language_family": "Italic"}, {"X1": -33.610256, "X2": -12.691463, "Nation": "Italian", "language_family": "Italic"}, {"X1": 14.253516, "X2": -12.102719, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 4.1609464, "X2": -22.064802, "Nation": "Italian", "language_family": "Italic"}, {"X1": 11.161046, "X2": 5.488277, "Nation": "Italian", "language_family": "Italic"}, {"X1": -3.834386, "X2": -11.189096, "Nation": "French", "language_family": "Italic"}, {"X1": -18.033503, "X2": -38.851593, "Nation": "Italian", "language_family": "Italic"}, {"X1": 22.670488, "X2": 27.122393, "Nation": "French", "language_family": "Italic"}, {"X1": -31.192568, "X2": 4.165093, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -35.336475, "X2": -14.436886, "Nation": "Italian", "language_family": "Italic"}, {"X1": 1.81045, "X2": 32.3835, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 2.292619, "X2": -11.154945, "Nation": "French", "language_family": "Italic"}, {"X1": 5.2170615, "X2": -12.499323, "Nation": "French", "language_family": "Italic"}, {"X1": 5.947569, "X2": -24.214113, "Nation": "Italian", "language_family": "Italic"}, {"X1": 8.394687, "X2": -27.37424, "Nation": "Italian", "language_family": "Italic"}, {"X1": 2.7647376, "X2": -9.472975, "Nation": "French", "language_family": "Italic"}, {"X1": -18.632036, "X2": -19.742945, "Nation": "Italian", "language_family": "Italic"}, {"X1": 5.6521444, "X2": 9.609713, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": 0.86301214, "X2": -24.769289, "Nation": "Italian", "language_family": "Italic"}, {"X1": -7.461081, "X2": -21.053156, "Nation": "French", "language_family": "Italic"}, {"X1": 31.57807, "X2": -2.9260097, "Nation": "Italian", "language_family": "Italic"}, {"X1": -12.274056, "X2": 12.921866, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -21.641737, "X2": -8.35528, "Nation": "Italian", "language_family": "Italic"}, {"X1": 4.2451167, "X2": -10.757242, "Nation": "French", "language_family": "Italic"}, {"X1": 4.5460453, "X2": 1.8967303, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 14.054109, "X2": -9.840552, "Nation": "French", "language_family": "Italic"}, {"X1": 6.347401, "X2": -0.6360811, "Nation": "French", "language_family": "Italic"}, {"X1": 31.79636, "X2": 29.541855, "Nation": "French", "language_family": "Italic"}, {"X1": 28.121899, "X2": 25.470512, "Nation": "French", "language_family": "Italic"}, {"X1": 11.586576, "X2": 1.5066863, "Nation": "French", "language_family": "Italic"}, {"X1": -19.40908, "X2": -11.803774, "Nation": "Italian", "language_family": "Italic"}, {"X1": -34.994087, "X2": -13.987037, "Nation": "Italian", "language_family": "Italic"}, {"X1": 28.678621, "X2": 26.81366, "Nation": "French", "language_family": "Italic"}, {"X1": 5.8237944, "X2": 7.9618526, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -13.735016, "X2": -14.939095, "Nation": "French", "language_family": "Italic"}, {"X1": -7.4334397, "X2": 26.97476, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -4.4341106, "X2": -18.361612, "Nation": "French", "language_family": "Italic"}, {"X1": -2.9329054, "X2": -3.1081326, "Nation": "French", "language_family": "Italic"}, {"X1": 3.752542, "X2": -12.249268, "Nation": "French", "language_family": "Italic"}, {"X1": 4.808357, "X2": -21.091124, "Nation": "Italian", "language_family": "Italic"}, {"X1": 0.8203545, "X2": -4.4916067, "Nation": "French", "language_family": "Italic"}, {"X1": -15.270228, "X2": -1.3150724, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 10.201681, "X2": -10.333191, "Nation": "French", "language_family": "Italic"}, {"X1": 1.4937907, "X2": -12.9730835, "Nation": "French", "language_family": "Italic"}, {"X1": -15.76912, "X2": -13.46042, "Nation": "French", "language_family": "Italic"}, {"X1": 3.1046152, "X2": -21.147528, "Nation": "Romanian", "language_family": "Italic"}, {"X1": -28.123272, "X2": 2.908605, "Nation": "Portuguese", "language_family": "Italic"}, {"X1": -11.937405, "X2": 18.642796, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -8.852358, "X2": -3.313728, "Nation": "Italian", "language_family": "Italic"}, {"X1": 28.368422, "X2": -9.2545805, "Nation": "French", "language_family": "Italic"}, {"X1": -18.490059, "X2": 8.863763, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": 2.2873862, "X2": -7.280329, "Nation": "French", "language_family": "Italic"}, {"X1": 7.486508, "X2": -6.335867, "Nation": "French", "language_family": "Italic"}, {"X1": -18.820467, "X2": -8.971515, "Nation": "Italian", "language_family": "Italic"}, {"X1": -35.29993, "X2": -14.430126, "Nation": "Italian", "language_family": "Italic"}, {"X1": 27.117882, "X2": 8.078923, "Nation": "French", "language_family": "Italic"}, {"X1": -33.801144, "X2": -12.85653, "Nation": "Italian", "language_family": "Italic"}, {"X1": -1.4090229, "X2": -26.96353, "Nation": "Italian", "language_family": "Italic"}, {"X1": -12.32638, "X2": -10.652711, "Nation": "Italian", "language_family": "Italic"}, {"X1": -18.16473, "X2": -18.543732, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 28.220613, "X2": 25.116133, "Nation": "French", "language_family": "Italic"}, {"X1": 16.997011, "X2": 5.7302237, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -18.09087, "X2": -0.22974913, "Nation": "Spanish", "language_family": "Italic"}, {"X1": -18.033182, "X2": -38.85158, "Nation": "Italian", "language_family": "Italic"}, {"X1": 6.5282454, "X2": -10.579813, "Nation": "French", "language_family": "Italic"}, {"X1": -30.887663, "X2": -8.569952, "Nation": "Italian", "language_family": "Italic"}, {"X1": -2.8439744, "X2": -0.61295986, "Nation": "French", "language_family": "Italic"}, {"X1": -16.750265, "X2": -4.0697646, "Nation": "Romanian", "language_family": "Italic"}, {"X1": -2.3741484, "X2": -28.824707, "Nation": "Romanian", "language_family": "Italic"}, {"X1": 5.743775, "X2": -7.6729817, "Nation": "French", "language_family": "Italic"}, {"X1": -19.145409, "X2": -6.042368, "Nation": "Italian", "language_family": "Italic"}, {"X1": -4.089502, "X2": -14.2811775, "Nation": "Spanish", "language_family": "Italic"}, {"X1": -5.9655538, "X2": 30.48988, "Nation": "Brazilian", "language_family": "Italic"}, {"X1": -1.3569891, "X2": -3.8587322, "Nation": "French", "language_family": "Italic"}, {"X1": -17.18456, "X2": -11.282936, "Nation": "Italian", "language_family": "Italic"}, {"X1": -18.116243, "X2": 13.977902, "Nation": "Maori", "language_family": "Austronesian"}, {"X1": -14.54909, "X2": 22.478722, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -27.819311, "X2": -18.763346, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -18.961842, "X2": 15.2146015, "Nation": "Hawaiian", "language_family": "Austronesian"}, {"X1": -6.827206, "X2": -6.620586, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -14.027456, "X2": -6.456654, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -9.948974, "X2": 23.458616, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -17.100943, "X2": 24.01329, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -31.15718, "X2": -20.860712, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -16.715353, "X2": 0.8756697, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -18.7398, "X2": 16.14334, "Nation": "Maori", "language_family": "Austronesian"}, {"X1": -7.2032914, "X2": 24.364828, "Nation": "Hawaiian", "language_family": "Austronesian"}, {"X1": -13.342315, "X2": -39.56921, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -22.374897, "X2": 13.875635, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -17.347054, "X2": 13.186656, "Nation": "Maori", "language_family": "Austronesian"}, {"X1": -12.137176, "X2": 8.417453, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -22.467297, "X2": 13.701458, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -15.820875, "X2": 9.123738, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -10.272423, "X2": 18.69459, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -14.585597, "X2": 22.811064, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -6.2881727, "X2": 17.324022, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -16.612965, "X2": 0.49528173, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -17.868483, "X2": 9.2944145, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -14.396385, "X2": 23.773863, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": 4.0398664, "X2": -1.3376172, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -3.1091616, "X2": 19.56803, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -4.9079247, "X2": 3.8261003, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -9.069602, "X2": 25.892805, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -16.955435, "X2": 12.436249, "Nation": "Maori", "language_family": "Austronesian"}, {"X1": 19.909771, "X2": 9.87643, "Nation": "New_Zealand_Native", "language_family": "Austronesian"}, {"X1": -14.655245, "X2": 21.38111, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": 18.664526, "X2": 5.551967, "Nation": "New_Zealand_Native", "language_family": "Austronesian"}, {"X1": -25.884722, "X2": 16.659271, "Nation": "Maori", "language_family": "Austronesian"}, {"X1": -6.8897276, "X2": 22.194323, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -16.6698, "X2": 20.826101, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -17.872362, "X2": 13.907368, "Nation": "Maori", "language_family": "Austronesian"}, {"X1": -12.034306, "X2": 23.131935, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -15.137772, "X2": 7.224061, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -7.9730806, "X2": 1.6148882, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -14.464112, "X2": 22.450346, "Nation": "New_Zealand_Native", "language_family": "Austronesian"}, {"X1": -13.310911, "X2": 9.239173, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -4.2747054, "X2": 19.084318, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -16.336504, "X2": 19.297009, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -10.875472, "X2": 25.03649, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -16.93275, "X2": 21.771318, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -11.574953, "X2": 21.080904, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -38.051342, "X2": -5.575669, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -6.9827075, "X2": -2.8301103, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -10.3119755, "X2": 26.963373, "Nation": "Hawaiian", "language_family": "Austronesian"}, {"X1": -13.288791, "X2": 6.953418, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -17.50973, "X2": 6.42165, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -14.089005, "X2": 8.115925, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -17.586351, "X2": 22.34036, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -7.782376, "X2": -1.7684468, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -0.8710737, "X2": 36.068386, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": 20.579365, "X2": 7.461228, "Nation": "New_Zealand_Native", "language_family": "Austronesian"}, {"X1": -2.2426202, "X2": 18.54024, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -1.6793522, "X2": -22.335812, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -11.9491625, "X2": 23.754124, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -16.060595, "X2": 22.621826, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -3.214035, "X2": 13.085243, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -6.203733, "X2": 21.097542, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -10.792796, "X2": 26.100788, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -11.091331, "X2": 26.178799, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -4.179524, "X2": 22.579313, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": 9.977837, "X2": 13.516811, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": 16.61757, "X2": 5.503985, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -12.883885, "X2": 23.239353, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -38.3381, "X2": 9.960373, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -0.96256506, "X2": 18.693316, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -12.779725, "X2": 21.004293, "Nation": "Maori", "language_family": "Austronesian"}, {"X1": -14.608388, "X2": 19.89439, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -13.87987, "X2": 27.941202, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -14.278482, "X2": 31.55283, "Nation": "Maori", "language_family": "Austronesian"}, {"X1": -5.095267, "X2": 17.433258, "Nation": "Maori", "language_family": "Austronesian"}, {"X1": -22.513227, "X2": 13.766704, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -12.7565975, "X2": 21.341694, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -17.253635, "X2": 22.280783, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -14.934804, "X2": 20.472662, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -16.067078, "X2": 23.98094, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -7.2929573, "X2": 0.18919256, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -7.441616, "X2": 25.921017, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -8.420781, "X2": 0.054305773, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -16.62807, "X2": 22.379648, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -4.4086456, "X2": -5.6660953, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -14.935812, "X2": 20.18658, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -18.78608, "X2": 22.045736, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -13.375532, "X2": 23.241545, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -16.63801, "X2": 19.139174, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -23.220072, "X2": 13.376325, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -15.12107, "X2": 25.074581, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -13.612999, "X2": 10.923188, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -27.235281, "X2": -20.100977, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -13.2638445, "X2": 28.278147, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -4.5311604, "X2": 1.7988614, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -10.868195, "X2": 17.44092, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -15.8562, "X2": 24.421858, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -24.745077, "X2": 13.983164, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": 18.604301, "X2": 7.602951, "Nation": "New_Zealand_Native", "language_family": "Austronesian"}, {"X1": -9.426981, "X2": 9.0320015, "Nation": "Maori", "language_family": "Austronesian"}, {"X1": -12.323621, "X2": 22.36487, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -17.327278, "X2": 4.728227, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -12.841082, "X2": 7.4925685, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -0.029182883, "X2": 20.920738, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -11.403395, "X2": 20.562695, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -23.93008, "X2": 13.32162, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -23.635052, "X2": 13.726751, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -3.5752707, "X2": 3.3489184, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": 19.44941, "X2": 8.650822, "Nation": "New_Zealand_Native", "language_family": "Austronesian"}, {"X1": -12.375063, "X2": 8.304021, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -14.32828, "X2": 19.566566, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -7.265541, "X2": -1.8459815, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -23.264761, "X2": 15.620433, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -9.011758, "X2": -1.7615037, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": 10.013471, "X2": 13.385811, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -16.540115, "X2": 0.050525244, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -6.6255436, "X2": 1.7371863, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -4.7181244, "X2": 16.197895, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -7.6795797, "X2": 1.6068747, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -4.364757, "X2": -3.421352, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -17.845087, "X2": -2.1349888, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -19.045303, "X2": 15.177368, "Nation": "Hawaiian", "language_family": "Austronesian"}, {"X1": -19.353888, "X2": 17.354803, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -12.556218, "X2": 12.082737, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -17.56089, "X2": 1.5994737, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -1.7583137, "X2": 18.491196, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -15.655817, "X2": 5.8816442, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": 19.198837, "X2": 5.7732506, "Nation": "New_Zealand_Native", "language_family": "Austronesian"}, {"X1": -6.7019596, "X2": 16.786402, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -28.702814, "X2": -22.081469, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -12.085752, "X2": 19.140465, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -38.337635, "X2": 9.958428, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -17.56845, "X2": 24.02378, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -9.162913, "X2": 25.144371, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -13.367928, "X2": -39.58359, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -4.415141, "X2": 1.5266694, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -21.072224, "X2": 15.484239, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -7.639033, "X2": 23.824114, "Nation": "Hawaiian", "language_family": "Austronesian"}, {"X1": -0.19752954, "X2": -1.4166108, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -6.1993513, "X2": 11.794706, "Nation": "Philippine", "language_family": "Austronesian"}, {"X1": -16.899693, "X2": 20.246529, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -15.543389, "X2": 21.688515, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -15.967836, "X2": 24.088408, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}, {"X1": -13.959932, "X2": 22.06186, "Nation": "Australian_Ethnic", "language_family": "Austronesian"}]}}, {"mode": "vega-lite"});
</script>
</div>
</div>
<p><em>Scatterplots of Stories.</em><br> In this scatterplot, we have the four language families with the most nations in the dataset, with their nations separated by color. Within the Austronesian group, the Austrailian Ethnic and New Zealand stories are tightly clustered. Within the Germanic group, the Nordic and German stories are tightly clustered. There seems to be two clusters of the Nordic stories, suggesting either a further cultural subdivision not in the dataset, or a subdivision of popular story types. Within the Italic group, the French have two clusters. The Slavic group has no clear clustering.<br> <br> Here, we already see clusters of stories, suggesting that there’s an underlying pattern to the stories these cultures tell.<br></p>
<p>Let’s look at specific cultures and words.</p>
<div class="cell" data-execution_count="25">
<div class="cell-output cell-output-display">
<p><img src="_project/quarto_files/folktales/figure-html/cell-12-output-1.png" class="img-fluid"></p>
</div>
</div>
<p><em>Chinese vs.&nbsp;Greek words.</em><br> In this bar chart, we have the words with the most difference frequency of usage compared between Chinese and Greek culture. Chinese stories are more often about emperors, heaven, dragon, and spirits; while Greek cultures are more often about kings, Theseus, heros, maidens, and fairies.</p>
<div class="cell" data-execution_count="26">
<div class="cell-output cell-output-display">
<p><img src="_project/quarto_files/folktales/figure-html/cell-13-output-1.png" class="img-fluid"></p>
</div>
</div>
<p><em>Slavic vs.&nbsp;Nordic words.</em><br> From this barchart, we see that Slavic stories are more often about royalty, while Nordic stories are more often about their gods.</p>
<p>From these figures, we can see that there’s a relationship between the culture and the characters they tell stories about. Like the knight, these characters (general or specific) stand for values. However, we can’t directly know what values the culture holds based on their characters. Kings, dragons, and gods are symbols of values, but don’t directly tell us what those values are. For that, we’ll use linguistic analyses.</p>
<p>However, we can’t directly know what values the culture holds based on their characters. Kings, dragons, faries</p>
</section>
</section>
<section id="comparison-of-hofstedes-dimensions-and-word-categories" class="level2">
<h2 class="anchored" data-anchor-id="comparison-of-hofstedes-dimensions-and-word-categories">Comparison of Hofstede’s Dimensions and Word Categories</h2>
<p>To interpret this pattern of the relationship between cultural stories and values, I use LIWC word categories and Hofstede’s cultural dimension to measure story topics and cultural values. <br> <br> Geert Hofstede’s six cultural dimenions are power distance, individualism, masculinity, uncertainty avoidance, long-term orientation, and indulgence. Power distance is the amount people in lower positions of power accept the unequal distribution of power. Individualism is how independent people are, where collectivism is how interdependent communities are. Masculinity is assertiveness, while feminity is caring. Uncertainty avoidance is the intolerance of ambiguity and the unknown. Long-term orientation is the understanding that the world changes, and preperation for the future is good; while short-term orientation is the understanding that the world is today as it was before, so the tradition is good. Indulgence is the access to desires and fun, while restraint is the control of gratification through social norms. Hofstede developed his theory after gaining access to data from a questionnare administered to employees of international programs, where he found differences at the national level. (Hofstede 2007) <br> <br> Beth Morling and Markila Lamoreaux demonstrate a relationship between cultural products (such as advertisements or popular texts) and individualistic and collectivistic psyches as defined by Hofstede (Morling &amp; Lamoreaux 2008). They focused on individualism and collectivism because it is most commonly operationalized, is a central cultural syndrome, and can be compared to self-reported measures.<br> <br> Nathan DeWall et al.&nbsp;argue that cultural products can also be used to analyze psyce within cultures. They use the LIWC program to analyze the song lyrics on three levels: self-focused, using first-person pronouns; socially-disconnected, using words such as talking or sharing; and angry/anti-social, using words such as hate or swear words. Based on their linguistic analysis, they concluded that music in the US, and thus the psyche has become more self-focused, socially-disconnected, and angry over time (DeWall et al.&nbsp;2011). While their results are likely the result of change in genre popularity more than psyche, their method is useful to follow in my case. Since folktales are passed down generationally and are long traditions, there would be no confounding factor such as a change in popularity of story genre. Additionally, I am comparing across nations, rather than within a nation, so such a change still reflects cultural values, my object of study. Thus, I use the LIWC dictionary (Pennebaker et al.&nbsp;2007) for my analysis. <br> <!-- In addition to the words and categories in the dictionary, I added a few of my own categories and relevant words, specifically the categories "hero", "royalty", and "power". --> <br> I predict that storytelling is related to cultural values because it is a strong teaching tool. Michael Tomasello argues in “The Human Adaptation for Culture” that children cognitively represent the world in uniquely powerful ways. In arguing this, he follows the ontogeny of human cultural learning, of which joint attention and imitative learning are most relevant for us. Join attention is the understanding of the relationship between child, adult, and another entity. An example of a baby of using their join attentional understanding is pointing to a toy to direct the adults attention. This is only possible when they understand other people as intentional agents, who have goals and make active choices to attain goals. After join attention, infants develop the skill of imitative learning. For example, infants were able to learn what a “toma” was after an adult announced her intention to “find the toma”, and smiling after it had been found (Tomasello 1999). In relation to stories, children understand characters as intentional agents, who have goals and strategies to achieve goals. Using imitative learning, children can learn those same goals and strategies, such as how to be a good person. <br> <br> JL Fischer analyzes why folktales are a model for society. Rewards and punishments for the supporters/dissenters of society are supplied in audience reaction and events in the folktales. For example, a good hero that suffers a bad fate has its reward in the audience’s sympathy rather than the hero’s fate, while funny tales where conventions are broken has its punishment in the scorn of the audience. Within tales themselves, dissenters may be punished or heroes rewarded. He then asks whether there is a relationship between folktales and social reality: and he concludes that promiment themes of folktales within a group are often subjects of conflicts (such as the height of chiefs and the smallness of artisans), while not all conflicts are represented in folktales. Additionally, they often overexaggerate (Fischer 1963). Thus, I am validated that the topics of stories should reflect what matters to a society (although maybe not directly!).<br> <br> Additionally, it might be better that stories don’t accurately reflect society. Jack Zipes argues that our fondness for folktales across all social classes are because they contain what we lack: “In many ways, fairy tales, with their metaphorical allusions, are more truthful than so-called realistic stories because the tales are generally endowed with a sense of social justice that we do not find in our societies.” The morals in stories result from the combination of lower-class storytellers and uppper-class storytellers and writers (Zipes 2019).<br> <br> It has also been argued that the relationship between law and morality makes folktales relevant to legal theory. Alexander Shytov argues that most law is negative, defining what is not allowed, resulting in the divide between laws from morals, because laws have become a mechanism of external coercion rather than a tool of self-governance. Because folktales contain standards of what is right and wrong, it contains the spirit of law, since they represent the moral standards of the whole community, who is the author of these stories (Shytov 2008). <br> <br> Therefore, folktales are widely agreed to hold the morals of society, and the words in those folktales should correlate to the values of society.</p>
<p><em>Note: Correlation and p-value were calculated using Spearman correlation.</em></p>
<div class="cell" data-execution_count="28">
<div class="cell-output cell-output-display" data-execution_count="28">

<div>

<table class="dataframe table table-sm table-striped">
  <thead>
    <tr>
      <th></th>
      <th>Feature</th>
      <th>Correlation</th>
      <th>P-Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>4</th>
      <td>you</td>
      <td>0.499466</td>
      <td>0.007990</td>
    </tr>
    <tr>
      <th>2</th>
      <td>i</td>
      <td>0.477484</td>
      <td>0.011780</td>
    </tr>
    <tr>
      <th>22</th>
      <td>family</td>
      <td>0.440543</td>
      <td>0.021456</td>
    </tr>
    <tr>
      <th>21</th>
      <td>social</td>
      <td>0.417036</td>
      <td>0.030453</td>
    </tr>
    <tr>
      <th>1</th>
      <td>ppron</td>
      <td>0.410319</td>
      <td>0.033518</td>
    </tr>
    <tr>
      <th>51</th>
      <td>space</td>
      <td>-0.435353</td>
      <td>0.023227</td>
    </tr>
    <tr>
      <th>31</th>
      <td>cogmech</td>
      <td>-0.467410</td>
      <td>0.013961</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell" data-execution_count="29">
<div class="cell-output cell-output-display" data-execution_count="29">

<div id="altair-viz-006281b33cc64f5e9ac8b23f97dfc2b0"></div>
<script type="text/javascript">
  var VEGA_DEBUG = (typeof VEGA_DEBUG == "undefined") ? {} : VEGA_DEBUG;
  (function(spec, embedOpt){
    let outputDiv = document.currentScript.previousElementSibling;
    if (outputDiv.id !== "altair-viz-006281b33cc64f5e9ac8b23f97dfc2b0") {
      outputDiv = document.getElementById("altair-viz-006281b33cc64f5e9ac8b23f97dfc2b0");
    }
    const paths = {
      "vega": "https://cdn.jsdelivr.net/npm//vega@5?noext",
      "vega-lib": "https://cdn.jsdelivr.net/npm//vega-lib?noext",
      "vega-lite": "https://cdn.jsdelivr.net/npm//vega-lite@4.17.0?noext",
      "vega-embed": "https://cdn.jsdelivr.net/npm//vega-embed@6?noext",
    };

    function maybeLoadScript(lib, version) {
      var key = `${lib.replace("-", "")}_version`;
      return (VEGA_DEBUG[key] == version) ?
        Promise.resolve(paths[lib]) :
        new Promise(function(resolve, reject) {
          var s = document.createElement('script');
          document.getElementsByTagName("head")[0].appendChild(s);
          s.async = true;
          s.onload = () => {
            VEGA_DEBUG[key] = version;
            return resolve(paths[lib]);
          };
          s.onerror = () => reject(`Error loading script: ${paths[lib]}`);
          s.src = paths[lib];
        });
    }

    function showError(err) {
      outputDiv.innerHTML = `<div class="error" style="color:red;">${err}</div>`;
      throw err;
    }

    function displayChart(vegaEmbed) {
      vegaEmbed(outputDiv, spec, embedOpt)
        .catch(err => showError(`Javascript Error: ${err.message}<br>This usually means there's a typo in your chart specification. See the javascript console for the full traceback.`));
    }

    if(typeof define === "function" && define.amd) {
      requirejs.config({paths});
      require(["vega-embed"], displayChart, err => showError(`Error loading script: ${err.message}`));
    } else {
      maybeLoadScript("vega", "5")
        .then(() => maybeLoadScript("vega-lite", "4.17.0"))
        .then(() => maybeLoadScript("vega-embed", "6"))
        .catch(showError)
        .then(() => displayChart(vegaEmbed));
    }
  })({"config": {"view": {"continuousWidth": 400, "continuousHeight": 300}}, "layer": [{"mark": {"type": "point", "size": 50}, "encoding": {"color": {"field": "Feature", "type": "nominal"}, "tooltip": [{"field": "Culture", "type": "nominal"}, {"field": "Feature", "type": "nominal"}], "x": {"axis": {"title": "Power Distance"}, "field": "pdi", "scale": {"zero": false}, "type": "quantitative"}, "y": {"axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}, {"mark": "line", "encoding": {"color": {"field": "Feature", "type": "nominal"}, "x": {"axis": {"title": "Power Distance"}, "field": "pdi", "scale": {"zero": false}, "type": "quantitative"}, "y": {"aggregate": "mean", "axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}], "data": {"name": "data-2245303afa6ab183b9644d705de0738b"}, "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json", "datasets": {"data-2245303afa6ab183b9644d705de0738b": [{"Culture": "Albanian", "pdi": 90.0, "Feature": "family", "score": 2.4081390544071004}, {"Culture": "Arabic", "pdi": 79.375, "Feature": "family", "score": -0.7357494901670004}, {"Culture": "Armenian", "pdi": 85.0, "Feature": "family", "score": 0.8092615677259698}, {"Culture": "Bulgarian", "pdi": 70.0, "Feature": "family", "score": 1.339699443651562}, {"Culture": "Chinese", "pdi": 58.0, "Feature": "family", "score": -0.1426494717788803}, {"Culture": "Croatian", "pdi": 73.0, "Feature": "family", "score": 1.013892732224979}, {"Culture": "Danish", "pdi": 18.0, "Feature": "family", "score": -1.120526992089744}, {"Culture": "Dutch", "pdi": 51.5, "Feature": "family", "score": -0.5919689311650683}, {"Culture": "English", "pdi": 47.66666666666666, "Feature": "family", "score": -0.8377886780606637}, {"Culture": "Estonian", "pdi": 40.0, "Feature": "family", "score": -1.4218646597625535}, {"Culture": "Finnish", "pdi": 33.0, "Feature": "family", "score": 0.285851191017724}, {"Culture": "French", "pdi": 69.0, "Feature": "family", "score": -1.2614727097565988}, {"Culture": "German", "pdi": 26.666666666666668, "Feature": "family", "score": -0.3387232838156294}, {"Culture": "Greek", "pdi": 60.0, "Feature": "family", "score": -1.5643308267952931}, {"Culture": "Icelandic", "pdi": 30.0, "Feature": "family", "score": 0.0964113613006823}, {"Culture": "Italian", "pdi": 50.0, "Feature": "family", "score": 0.3046912703525679}, {"Culture": "Japanese", "pdi": 54.0, "Feature": "family", "score": -0.446290765909395}, {"Culture": "Lithuanian", "pdi": 42.0, "Feature": "family", "score": 1.2400355707571538}, {"Culture": "Polish", "pdi": 68.0, "Feature": "family", "score": -0.7886957559978481}, {"Culture": "Portuguese", "pdi": 75.0, "Feature": "family", "score": 0.1706432527466981}, {"Culture": "Romanian", "pdi": 90.0, "Feature": "family", "score": 0.0511736187929132}, {"Culture": "Russian", "pdi": 93.0, "Feature": "family", "score": 0.2313137087098722}, {"Culture": "Serbian", "pdi": 87.0, "Feature": "family", "score": 1.210660329414481}, {"Culture": "Spanish", "pdi": 66.88888888888889, "Feature": "family", "score": -0.495304258389552}, {"Culture": "Swedish", "pdi": 31.0, "Feature": "family", "score": -1.2668970730076856}, {"Culture": "Turkish", "pdi": 66.0, "Feature": "family", "score": 0.81909059878386}, {"Culture": "Ukrainian", "pdi": 92.0, "Feature": "family", "score": 1.031399196810326}, {"Culture": "Albanian", "pdi": 90.0, "Feature": "social", "score": 2.001211856963452}, {"Culture": "Arabic", "pdi": 79.375, "Feature": "social", "score": -0.377965166346479}, {"Culture": "Armenian", "pdi": 85.0, "Feature": "social", "score": 1.0785545327941353}, {"Culture": "Bulgarian", "pdi": 70.0, "Feature": "social", "score": 1.386082641911541}, {"Culture": "Chinese", "pdi": 58.0, "Feature": "social", "score": -0.9519245898084152}, {"Culture": "Croatian", "pdi": 73.0, "Feature": "social", "score": 0.5076377670018296}, {"Culture": "Danish", "pdi": 18.0, "Feature": "social", "score": -1.334350065975138}, {"Culture": "Dutch", "pdi": 51.5, "Feature": "social", "score": -2.497865136407954}, {"Culture": "English", "pdi": 47.66666666666666, "Feature": "social", "score": -0.2955786643864291}, {"Culture": "Estonian", "pdi": 40.0, "Feature": "social", "score": -0.4920382196257131}, {"Culture": "Finnish", "pdi": 33.0, "Feature": "social", "score": -0.2877771373110566}, {"Culture": "French", "pdi": 69.0, "Feature": "social", "score": -1.423496631979267}, {"Culture": "German", "pdi": 26.666666666666668, "Feature": "social", "score": -0.1024531876909128}, {"Culture": "Greek", "pdi": 60.0, "Feature": "social", "score": -0.551214847365895}, {"Culture": "Icelandic", "pdi": 30.0, "Feature": "social", "score": 0.5921794905793965}, {"Culture": "Italian", "pdi": 50.0, "Feature": "social", "score": 0.6418918320059614}, {"Culture": "Japanese", "pdi": 54.0, "Feature": "social", "score": -0.452364850038894}, {"Culture": "Lithuanian", "pdi": 42.0, "Feature": "social", "score": 1.3097122567249009}, {"Culture": "Polish", "pdi": 68.0, "Feature": "social", "score": -1.0256168033634665}, {"Culture": "Portuguese", "pdi": 75.0, "Feature": "social", "score": 0.2829384893738778}, {"Culture": "Romanian", "pdi": 90.0, "Feature": "social", "score": 0.2437203026696485}, {"Culture": "Russian", "pdi": 93.0, "Feature": "social", "score": -0.0037960259327916}, {"Culture": "Serbian", "pdi": 87.0, "Feature": "social", "score": 1.0895575242233195}, {"Culture": "Spanish", "pdi": 66.88888888888889, "Feature": "social", "score": -0.0800150771491371}, {"Culture": "Swedish", "pdi": 31.0, "Feature": "social", "score": -0.5166333369108618}, {"Culture": "Turkish", "pdi": 66.0, "Feature": "social", "score": 0.0367742605660532}, {"Culture": "Ukrainian", "pdi": 92.0, "Feature": "social", "score": 1.222828785478257}]}}, {"mode": "vega-lite"});
</script>
</div>
</div>
<p><em>Power Distance vs.&nbsp;LIWC.</em> In this scatterplot, we have the Power Distance Index on the x-axis, and the standardized score of LIWC word categories on the y-axis, with the averages graphed with lines. Power distance is positively correlated to family and social words.</p>
<div class="cell" data-execution_count="30">
<div class="cell-output cell-output-display" data-execution_count="30">

<div>

<table class="dataframe table table-sm table-striped">
  <thead>
    <tr>
      <th></th>
      <th>Feature</th>
      <th>Correlation</th>
      <th>P-Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>31</th>
      <td>cogmech</td>
      <td>0.471794</td>
      <td>0.012974</td>
    </tr>
    <tr>
      <th>62</th>
      <td>filler</td>
      <td>0.448556</td>
      <td>0.018939</td>
    </tr>
    <tr>
      <th>43</th>
      <td>feel</td>
      <td>0.423789</td>
      <td>0.027604</td>
    </tr>
    <tr>
      <th>51</th>
      <td>space</td>
      <td>0.406666</td>
      <td>0.035286</td>
    </tr>
    <tr>
      <th>55</th>
      <td>leisure</td>
      <td>0.391378</td>
      <td>0.043511</td>
    </tr>
    <tr>
      <th>1</th>
      <td>ppron</td>
      <td>-0.400857</td>
      <td>0.038251</td>
    </tr>
    <tr>
      <th>22</th>
      <td>family</td>
      <td>-0.409418</td>
      <td>0.033947</td>
    </tr>
    <tr>
      <th>4</th>
      <td>you</td>
      <td>-0.422566</td>
      <td>0.028103</td>
    </tr>
    <tr>
      <th>21</th>
      <td>social</td>
      <td>-0.432962</td>
      <td>0.024082</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell" data-execution_count="31">
<div class="cell-output cell-output-display" data-execution_count="31">

<div id="altair-viz-127f099f0d22495ea0cceaa46ee533ff"></div>
<script type="text/javascript">
  var VEGA_DEBUG = (typeof VEGA_DEBUG == "undefined") ? {} : VEGA_DEBUG;
  (function(spec, embedOpt){
    let outputDiv = document.currentScript.previousElementSibling;
    if (outputDiv.id !== "altair-viz-127f099f0d22495ea0cceaa46ee533ff") {
      outputDiv = document.getElementById("altair-viz-127f099f0d22495ea0cceaa46ee533ff");
    }
    const paths = {
      "vega": "https://cdn.jsdelivr.net/npm//vega@5?noext",
      "vega-lib": "https://cdn.jsdelivr.net/npm//vega-lib?noext",
      "vega-lite": "https://cdn.jsdelivr.net/npm//vega-lite@4.17.0?noext",
      "vega-embed": "https://cdn.jsdelivr.net/npm//vega-embed@6?noext",
    };

    function maybeLoadScript(lib, version) {
      var key = `${lib.replace("-", "")}_version`;
      return (VEGA_DEBUG[key] == version) ?
        Promise.resolve(paths[lib]) :
        new Promise(function(resolve, reject) {
          var s = document.createElement('script');
          document.getElementsByTagName("head")[0].appendChild(s);
          s.async = true;
          s.onload = () => {
            VEGA_DEBUG[key] = version;
            return resolve(paths[lib]);
          };
          s.onerror = () => reject(`Error loading script: ${paths[lib]}`);
          s.src = paths[lib];
        });
    }

    function showError(err) {
      outputDiv.innerHTML = `<div class="error" style="color:red;">${err}</div>`;
      throw err;
    }

    function displayChart(vegaEmbed) {
      vegaEmbed(outputDiv, spec, embedOpt)
        .catch(err => showError(`Javascript Error: ${err.message}<br>This usually means there's a typo in your chart specification. See the javascript console for the full traceback.`));
    }

    if(typeof define === "function" && define.amd) {
      requirejs.config({paths});
      require(["vega-embed"], displayChart, err => showError(`Error loading script: ${err.message}`));
    } else {
      maybeLoadScript("vega", "5")
        .then(() => maybeLoadScript("vega-lite", "4.17.0"))
        .then(() => maybeLoadScript("vega-embed", "6"))
        .catch(showError)
        .then(() => displayChart(vegaEmbed));
    }
  })({"config": {"view": {"continuousWidth": 400, "continuousHeight": 300}}, "layer": [{"mark": {"type": "point", "size": 50}, "encoding": {"color": {"field": "Feature", "type": "nominal"}, "tooltip": [{"field": "Culture", "type": "nominal"}, {"field": "Feature", "type": "nominal"}], "x": {"axis": {"title": "Individualism"}, "field": "idv", "scale": {"zero": false}, "type": "quantitative"}, "y": {"axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}, {"mark": "line", "encoding": {"color": {"field": "Feature", "type": "nominal"}, "x": {"axis": {"title": "Individualism"}, "field": "idv", "scale": {"zero": false}, "type": "quantitative"}, "y": {"aggregate": "mean", "axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}], "data": {"name": "data-6cc5de1c6e676889caae27e222310f80"}, "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json", "datasets": {"data-6cc5de1c6e676889caae27e222310f80": [{"Culture": "Albanian", "idv": 20.0, "Feature": "family", "score": 2.4081390544071004}, {"Culture": "Arabic", "idv": 33.625, "Feature": "family", "score": -0.7357494901670004}, {"Culture": "Armenian", "idv": 22.0, "Feature": "family", "score": 0.8092615677259698}, {"Culture": "Bulgarian", "idv": 30.0, "Feature": "family", "score": 1.339699443651562}, {"Culture": "Chinese", "idv": 17.0, "Feature": "family", "score": -0.1426494717788803}, {"Culture": "Croatian", "idv": 33.0, "Feature": "family", "score": 1.013892732224979}, {"Culture": "Danish", "idv": 74.0, "Feature": "family", "score": -1.120526992089744}, {"Culture": "Dutch", "idv": 77.5, "Feature": "family", "score": -0.5919689311650683}, {"Culture": "English", "idv": 56.0, "Feature": "family", "score": -0.8377886780606637}, {"Culture": "Estonian", "idv": 60.0, "Feature": "family", "score": -1.4218646597625535}, {"Culture": "Finnish", "idv": 63.0, "Feature": "family", "score": 0.285851191017724}, {"Culture": "French", "idv": 43.0, "Feature": "family", "score": -1.2614727097565988}, {"Culture": "German", "idv": 63.33333333333334, "Feature": "family", "score": -0.3387232838156294}, {"Culture": "Greek", "idv": 35.0, "Feature": "family", "score": -1.5643308267952931}, {"Culture": "Icelandic", "idv": 60.0, "Feature": "family", "score": 0.0964113613006823}, {"Culture": "Italian", "idv": 76.0, "Feature": "family", "score": 0.3046912703525679}, {"Culture": "Japanese", "idv": 46.0, "Feature": "family", "score": -0.446290765909395}, {"Culture": "Lithuanian", "idv": 60.0, "Feature": "family", "score": 1.2400355707571538}, {"Culture": "Polish", "idv": 60.0, "Feature": "family", "score": -0.7886957559978481}, {"Culture": "Portuguese", "idv": 23.6, "Feature": "family", "score": 0.1706432527466981}, {"Culture": "Romanian", "idv": 30.0, "Feature": "family", "score": 0.0511736187929132}, {"Culture": "Russian", "idv": 39.0, "Feature": "family", "score": 0.2313137087098722}, {"Culture": "Serbian", "idv": 24.5, "Feature": "family", "score": 1.210660329414481}, {"Culture": "Spanish", "idv": 23.0, "Feature": "family", "score": -0.495304258389552}, {"Culture": "Swedish", "idv": 71.0, "Feature": "family", "score": -1.2668970730076856}, {"Culture": "Turkish", "idv": 37.0, "Feature": "family", "score": 0.81909059878386}, {"Culture": "Ukrainian", "idv": 25.0, "Feature": "family", "score": 1.031399196810326}, {"Culture": "Albanian", "idv": 20.0, "Feature": "social", "score": 2.001211856963452}, {"Culture": "Arabic", "idv": 33.625, "Feature": "social", "score": -0.377965166346479}, {"Culture": "Armenian", "idv": 22.0, "Feature": "social", "score": 1.0785545327941353}, {"Culture": "Bulgarian", "idv": 30.0, "Feature": "social", "score": 1.386082641911541}, {"Culture": "Chinese", "idv": 17.0, "Feature": "social", "score": -0.9519245898084152}, {"Culture": "Croatian", "idv": 33.0, "Feature": "social", "score": 0.5076377670018296}, {"Culture": "Danish", "idv": 74.0, "Feature": "social", "score": -1.334350065975138}, {"Culture": "Dutch", "idv": 77.5, "Feature": "social", "score": -2.497865136407954}, {"Culture": "English", "idv": 56.0, "Feature": "social", "score": -0.2955786643864291}, {"Culture": "Estonian", "idv": 60.0, "Feature": "social", "score": -0.4920382196257131}, {"Culture": "Finnish", "idv": 63.0, "Feature": "social", "score": -0.2877771373110566}, {"Culture": "French", "idv": 43.0, "Feature": "social", "score": -1.423496631979267}, {"Culture": "German", "idv": 63.33333333333334, "Feature": "social", "score": -0.1024531876909128}, {"Culture": "Greek", "idv": 35.0, "Feature": "social", "score": -0.551214847365895}, {"Culture": "Icelandic", "idv": 60.0, "Feature": "social", "score": 0.5921794905793965}, {"Culture": "Italian", "idv": 76.0, "Feature": "social", "score": 0.6418918320059614}, {"Culture": "Japanese", "idv": 46.0, "Feature": "social", "score": -0.452364850038894}, {"Culture": "Lithuanian", "idv": 60.0, "Feature": "social", "score": 1.3097122567249009}, {"Culture": "Polish", "idv": 60.0, "Feature": "social", "score": -1.0256168033634665}, {"Culture": "Portuguese", "idv": 23.6, "Feature": "social", "score": 0.2829384893738778}, {"Culture": "Romanian", "idv": 30.0, "Feature": "social", "score": 0.2437203026696485}, {"Culture": "Russian", "idv": 39.0, "Feature": "social", "score": -0.0037960259327916}, {"Culture": "Serbian", "idv": 24.5, "Feature": "social", "score": 1.0895575242233195}, {"Culture": "Spanish", "idv": 23.0, "Feature": "social", "score": -0.0800150771491371}, {"Culture": "Swedish", "idv": 71.0, "Feature": "social", "score": -0.5166333369108618}, {"Culture": "Turkish", "idv": 37.0, "Feature": "social", "score": 0.0367742605660532}, {"Culture": "Ukrainian", "idv": 25.0, "Feature": "social", "score": 1.222828785478257}]}}, {"mode": "vega-lite"});
</script>
</div>
</div>
<p><em>Individualism vs.&nbsp;LIWC.</em><br> Individualism is negatively correlated to family and social categories. Nations that have a more collective mindset (lower individualism score) use more family and social words, while nations that have a more individualistic mindset huse less family and social words.</p>
<div class="cell" data-execution_count="32">
<div class="cell-output cell-output-display" data-execution_count="32">

<div>

<table class="dataframe table table-sm table-striped">
  <thead>
    <tr>
      <th></th>
      <th>Feature</th>
      <th>Correlation</th>
      <th>P-Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>10</th>
      <td>auxverb</td>
      <td>-0.422290</td>
      <td>0.028217</td>
    </tr>
    <tr>
      <th>14</th>
      <td>adverb</td>
      <td>-0.465038</td>
      <td>0.014520</td>
    </tr>
    <tr>
      <th>34</th>
      <td>discrep</td>
      <td>-0.542290</td>
      <td>0.003476</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell" data-execution_count="33">
<div class="cell-output cell-output-display" data-execution_count="33">

<div id="altair-viz-eee50fffac964b4da93b2952e7147bbf"></div>
<script type="text/javascript">
  var VEGA_DEBUG = (typeof VEGA_DEBUG == "undefined") ? {} : VEGA_DEBUG;
  (function(spec, embedOpt){
    let outputDiv = document.currentScript.previousElementSibling;
    if (outputDiv.id !== "altair-viz-eee50fffac964b4da93b2952e7147bbf") {
      outputDiv = document.getElementById("altair-viz-eee50fffac964b4da93b2952e7147bbf");
    }
    const paths = {
      "vega": "https://cdn.jsdelivr.net/npm//vega@5?noext",
      "vega-lib": "https://cdn.jsdelivr.net/npm//vega-lib?noext",
      "vega-lite": "https://cdn.jsdelivr.net/npm//vega-lite@4.17.0?noext",
      "vega-embed": "https://cdn.jsdelivr.net/npm//vega-embed@6?noext",
    };

    function maybeLoadScript(lib, version) {
      var key = `${lib.replace("-", "")}_version`;
      return (VEGA_DEBUG[key] == version) ?
        Promise.resolve(paths[lib]) :
        new Promise(function(resolve, reject) {
          var s = document.createElement('script');
          document.getElementsByTagName("head")[0].appendChild(s);
          s.async = true;
          s.onload = () => {
            VEGA_DEBUG[key] = version;
            return resolve(paths[lib]);
          };
          s.onerror = () => reject(`Error loading script: ${paths[lib]}`);
          s.src = paths[lib];
        });
    }

    function showError(err) {
      outputDiv.innerHTML = `<div class="error" style="color:red;">${err}</div>`;
      throw err;
    }

    function displayChart(vegaEmbed) {
      vegaEmbed(outputDiv, spec, embedOpt)
        .catch(err => showError(`Javascript Error: ${err.message}<br>This usually means there's a typo in your chart specification. See the javascript console for the full traceback.`));
    }

    if(typeof define === "function" && define.amd) {
      requirejs.config({paths});
      require(["vega-embed"], displayChart, err => showError(`Error loading script: ${err.message}`));
    } else {
      maybeLoadScript("vega", "5")
        .then(() => maybeLoadScript("vega-lite", "4.17.0"))
        .then(() => maybeLoadScript("vega-embed", "6"))
        .catch(showError)
        .then(() => displayChart(vegaEmbed));
    }
  })({"config": {"view": {"continuousWidth": 400, "continuousHeight": 300}}, "layer": [{"mark": {"type": "point", "size": 50}, "encoding": {"color": {"field": "Feature", "type": "nominal"}, "tooltip": [{"field": "Culture", "type": "nominal"}, {"field": "Feature", "type": "nominal"}], "x": {"axis": {"title": "Uncertainty Avoidance"}, "field": "uai", "scale": {"zero": false}, "type": "quantitative"}, "y": {"axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}, {"mark": "line", "encoding": {"color": {"field": "Feature", "type": "nominal"}, "x": {"axis": {"title": "Uncertainty Avoidance"}, "field": "uai", "scale": {"zero": false}, "type": "quantitative"}, "y": {"aggregate": "mean", "axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}], "data": {"name": "data-6e332dd3ca561013fb8fee185f923c31"}, "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json", "datasets": {"data-6e332dd3ca561013fb8fee185f923c31": [{"Culture": "Albanian", "uai": 70.0, "Feature": "discrep", "score": 1.148159006027147}, {"Culture": "Arabic", "uai": 70.75, "Feature": "discrep", "score": 0.4509808287386872}, {"Culture": "Armenian", "uai": 88.0, "Feature": "discrep", "score": -0.9359882496659342}, {"Culture": "Bulgarian", "uai": 85.0, "Feature": "discrep", "score": -1.000569833004519}, {"Culture": "Chinese", "uai": 69.0, "Feature": "discrep", "score": -0.8904027294961888}, {"Culture": "Croatian", "uai": 80.0, "Feature": "discrep", "score": 0.4470674513734188}, {"Culture": "Danish", "uai": 23.0, "Feature": "discrep", "score": 0.7703643419632267}, {"Culture": "Dutch", "uai": 73.5, "Feature": "discrep", "score": -0.8006847316394666}, {"Culture": "English", "uai": 49.22222222222222, "Feature": "discrep", "score": -0.2345142479190273}, {"Culture": "Estonian", "uai": 60.0, "Feature": "discrep", "score": 2.15833072219672}, {"Culture": "Finnish", "uai": 59.0, "Feature": "discrep", "score": 0.4662347422338749}, {"Culture": "French", "uai": 70.5, "Feature": "discrep", "score": 0.8313772081145268}, {"Culture": "German", "uai": 64.33333333333333, "Feature": "discrep", "score": 0.5931486343958899}, {"Culture": "Greek", "uai": 112.0, "Feature": "discrep", "score": -0.0042912243615674}, {"Culture": "Icelandic", "uai": 50.0, "Feature": "discrep", "score": 1.602750800101279}, {"Culture": "Italian", "uai": 75.0, "Feature": "discrep", "score": 0.289362851156737}, {"Culture": "Japanese", "uai": 92.0, "Feature": "discrep", "score": -1.0355152016726688}, {"Culture": "Lithuanian", "uai": 65.0, "Feature": "discrep", "score": -0.6046233394558373}, {"Culture": "Polish", "uai": 93.0, "Feature": "discrep", "score": -1.32752988935464}, {"Culture": "Portuguese", "uai": 64.8, "Feature": "discrep", "score": -0.108241321130586}, {"Culture": "Romanian", "uai": 90.0, "Feature": "discrep", "score": 1.0088123426715507}, {"Culture": "Russian", "uai": 95.0, "Feature": "discrep", "score": -1.074341301475016}, {"Culture": "Serbian", "uai": 91.0, "Feature": "discrep", "score": -0.2810075640310043}, {"Culture": "Spanish", "uai": 86.22222222222223, "Feature": "discrep", "score": 0.9963509496822832}, {"Culture": "Swedish", "uai": 29.0, "Feature": "discrep", "score": 0.3679114690756854}, {"Culture": "Turkish", "uai": 85.0, "Feature": "discrep", "score": -0.6604809863037199}, {"Culture": "Ukrainian", "uai": 95.0, "Feature": "discrep", "score": -2.17266072822086}, {"Culture": "Albanian", "uai": 70.0, "Feature": "auxverb", "score": -0.2237233063915372}, {"Culture": "Arabic", "uai": 70.75, "Feature": "auxverb", "score": 0.3678258690440458}, {"Culture": "Armenian", "uai": 88.0, "Feature": "auxverb", "score": 0.0331116583798066}, {"Culture": "Bulgarian", "uai": 85.0, "Feature": "auxverb", "score": -0.8580985418209035}, {"Culture": "Chinese", "uai": 69.0, "Feature": "auxverb", "score": 0.3967949515636372}, {"Culture": "Croatian", "uai": 80.0, "Feature": "auxverb", "score": 0.0288061730765291}, {"Culture": "Danish", "uai": 23.0, "Feature": "auxverb", "score": 1.7420229276990906}, {"Culture": "Dutch", "uai": 73.5, "Feature": "auxverb", "score": -0.538363682844121}, {"Culture": "English", "uai": 49.22222222222222, "Feature": "auxverb", "score": -1.22771580834784}, {"Culture": "Estonian", "uai": 60.0, "Feature": "auxverb", "score": 1.375929671078877}, {"Culture": "Finnish", "uai": 59.0, "Feature": "auxverb", "score": -0.4210685011007334}, {"Culture": "French", "uai": 70.5, "Feature": "auxverb", "score": -0.62856518825455}, {"Culture": "German", "uai": 64.33333333333333, "Feature": "auxverb", "score": 0.8997424844766408}, {"Culture": "Greek", "uai": 112.0, "Feature": "auxverb", "score": -0.366369608714939}, {"Culture": "Icelandic", "uai": 50.0, "Feature": "auxverb", "score": 1.52891357852972}, {"Culture": "Italian", "uai": 75.0, "Feature": "auxverb", "score": 0.6592600542087619}, {"Culture": "Japanese", "uai": 92.0, "Feature": "auxverb", "score": -0.7564125756268316}, {"Culture": "Lithuanian", "uai": 65.0, "Feature": "auxverb", "score": -0.8171596226041298}, {"Culture": "Polish", "uai": 93.0, "Feature": "auxverb", "score": -1.6436614476842402}, {"Culture": "Portuguese", "uai": 64.8, "Feature": "auxverb", "score": 1.395930176322501}, {"Culture": "Romanian", "uai": 90.0, "Feature": "auxverb", "score": 0.7783850105268649}, {"Culture": "Russian", "uai": 95.0, "Feature": "auxverb", "score": -1.1216984314432827}, {"Culture": "Serbian", "uai": 91.0, "Feature": "auxverb", "score": 0.4542652346339956}, {"Culture": "Spanish", "uai": 86.22222222222223, "Feature": "auxverb", "score": 1.114600951174211}, {"Culture": "Swedish", "uai": 29.0, "Feature": "auxverb", "score": 0.3255559887387804}, {"Culture": "Turkish", "uai": 85.0, "Feature": "auxverb", "score": -0.3901001262721569}, {"Culture": "Ukrainian", "uai": 95.0, "Feature": "auxverb", "score": -2.108207888348204}]}}, {"mode": "vega-lite"});
</script>
</div>
</div>
<p><em>Uncertainty Avoidance vs.&nbsp;LIWC.</em><br> Nations that have are less avoidant of uncertainty use more auxverbs (eg. am, will, have) and discrep words (eg. should, would, could). Since nations with a higher uncertainty avoidance are more stressed about unknown futures, this is not what I expected.</p>
<div class="cell" data-execution_count="34">
<div class="cell-output cell-output-display" data-execution_count="34">

<div>

<table class="dataframe table table-sm table-striped">
  <thead>
    <tr>
      <th></th>
      <th>Feature</th>
      <th>Correlation</th>
      <th>P-Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>47</th>
      <td>sexual</td>
      <td>0.419301</td>
      <td>0.029472</td>
    </tr>
    <tr>
      <th>46</th>
      <td>health</td>
      <td>0.416247</td>
      <td>0.030801</td>
    </tr>
    <tr>
      <th>11</th>
      <td>past</td>
      <td>-0.387540</td>
      <td>0.045797</td>
    </tr>
    <tr>
      <th>31</th>
      <td>cogmech</td>
      <td>-0.419911</td>
      <td>0.029212</td>
    </tr>
    <tr>
      <th>39</th>
      <td>excl</td>
      <td>-0.423576</td>
      <td>0.027690</td>
    </tr>
    <tr>
      <th>14</th>
      <td>adverb</td>
      <td>-0.562529</td>
      <td>0.002256</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell" data-execution_count="35">
<div class="cell-output cell-output-display" data-execution_count="35">

<div id="altair-viz-270ba724cd6d49cfa225d99ce06fac14"></div>
<script type="text/javascript">
  var VEGA_DEBUG = (typeof VEGA_DEBUG == "undefined") ? {} : VEGA_DEBUG;
  (function(spec, embedOpt){
    let outputDiv = document.currentScript.previousElementSibling;
    if (outputDiv.id !== "altair-viz-270ba724cd6d49cfa225d99ce06fac14") {
      outputDiv = document.getElementById("altair-viz-270ba724cd6d49cfa225d99ce06fac14");
    }
    const paths = {
      "vega": "https://cdn.jsdelivr.net/npm//vega@5?noext",
      "vega-lib": "https://cdn.jsdelivr.net/npm//vega-lib?noext",
      "vega-lite": "https://cdn.jsdelivr.net/npm//vega-lite@4.17.0?noext",
      "vega-embed": "https://cdn.jsdelivr.net/npm//vega-embed@6?noext",
    };

    function maybeLoadScript(lib, version) {
      var key = `${lib.replace("-", "")}_version`;
      return (VEGA_DEBUG[key] == version) ?
        Promise.resolve(paths[lib]) :
        new Promise(function(resolve, reject) {
          var s = document.createElement('script');
          document.getElementsByTagName("head")[0].appendChild(s);
          s.async = true;
          s.onload = () => {
            VEGA_DEBUG[key] = version;
            return resolve(paths[lib]);
          };
          s.onerror = () => reject(`Error loading script: ${paths[lib]}`);
          s.src = paths[lib];
        });
    }

    function showError(err) {
      outputDiv.innerHTML = `<div class="error" style="color:red;">${err}</div>`;
      throw err;
    }

    function displayChart(vegaEmbed) {
      vegaEmbed(outputDiv, spec, embedOpt)
        .catch(err => showError(`Javascript Error: ${err.message}<br>This usually means there's a typo in your chart specification. See the javascript console for the full traceback.`));
    }

    if(typeof define === "function" && define.amd) {
      requirejs.config({paths});
      require(["vega-embed"], displayChart, err => showError(`Error loading script: ${err.message}`));
    } else {
      maybeLoadScript("vega", "5")
        .then(() => maybeLoadScript("vega-lite", "4.17.0"))
        .then(() => maybeLoadScript("vega-embed", "6"))
        .catch(showError)
        .then(() => displayChart(vegaEmbed));
    }
  })({"config": {"view": {"continuousWidth": 400, "continuousHeight": 300}}, "layer": [{"mark": {"type": "point", "size": 50}, "encoding": {"color": {"field": "Feature", "type": "nominal"}, "tooltip": [{"field": "Culture", "type": "nominal"}, {"field": "Feature", "type": "nominal"}], "x": {"axis": {"title": "Masculinity"}, "field": "mas", "scale": {"zero": false}, "type": "quantitative"}, "y": {"axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}, {"mark": "line", "encoding": {"color": {"field": "Feature", "type": "nominal"}, "x": {"axis": {"title": "Masculinity"}, "field": "mas", "scale": {"zero": false}, "type": "quantitative"}, "y": {"aggregate": "mean", "axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}], "data": {"name": "data-915ea507ceb253391d3709c8008b0b18"}, "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json", "datasets": {"data-915ea507ceb253391d3709c8008b0b18": [{"Culture": "Albanian", "mas": 80.0, "Feature": "sexual", "score": -0.3060305149782678}, {"Culture": "Arabic", "mas": 53.125, "Feature": "sexual", "score": -0.4790868503932152}, {"Culture": "Armenian", "mas": 50.0, "Feature": "sexual", "score": 0.952805829456608}, {"Culture": "Bulgarian", "mas": 40.0, "Feature": "sexual", "score": -0.4625649145620029}, {"Culture": "Chinese", "mas": 45.0, "Feature": "sexual", "score": -0.791452571877867}, {"Culture": "Croatian", "mas": 40.0, "Feature": "sexual", "score": -0.2999764241624544}, {"Culture": "Danish", "mas": 16.0, "Feature": "sexual", "score": 0.2365194831817295}, {"Culture": "Dutch", "mas": 34.0, "Feature": "sexual", "score": 0.3966117056239498}, {"Culture": "English", "mas": 55.888888888888886, "Feature": "sexual", "score": 0.1476298679443517}, {"Culture": "Estonian", "mas": 30.0, "Feature": "sexual", "score": -0.9035960285181914}, {"Culture": "Finnish", "mas": 26.0, "Feature": "sexual", "score": -0.9922710087993044}, {"Culture": "French", "mas": 46.5, "Feature": "sexual", "score": 1.1136643439425524}, {"Culture": "German", "mas": 71.66666666666667, "Feature": "sexual", "score": 0.2129591251888921}, {"Culture": "Greek", "mas": 57.0, "Feature": "sexual", "score": 1.0236840230054598}, {"Culture": "Icelandic", "mas": 10.0, "Feature": "sexual", "score": -0.844646406755658}, {"Culture": "Italian", "mas": 70.0, "Feature": "sexual", "score": 1.4838613058891204}, {"Culture": "Japanese", "mas": 95.0, "Feature": "sexual", "score": 0.7647813427535353}, {"Culture": "Lithuanian", "mas": 19.0, "Feature": "sexual", "score": -2.011967301424352}, {"Culture": "Polish", "mas": 64.0, "Feature": "sexual", "score": -0.0863097917682852}, {"Culture": "Portuguese", "mas": 30.6, "Feature": "sexual", "score": 2.8666472710635205}, {"Culture": "Romanian", "mas": 42.0, "Feature": "sexual", "score": -0.4929625117767429}, {"Culture": "Russian", "mas": 36.0, "Feature": "sexual", "score": -0.2315257090959025}, {"Culture": "Serbian", "mas": 45.5, "Feature": "sexual", "score": -0.5304066426905293}, {"Culture": "Spanish", "mas": 50.0, "Feature": "sexual", "score": -0.4404045535445007}, {"Culture": "Swedish", "mas": 5.0, "Feature": "sexual", "score": -1.0552205527832157}, {"Culture": "Turkish", "mas": 45.0, "Feature": "sexual", "score": -0.5141165385288726}, {"Culture": "Ukrainian", "mas": 27.0, "Feature": "sexual", "score": 1.2433740236096498}, {"Culture": "Albanian", "mas": 80.0, "Feature": "health", "score": -0.3285740470540149}, {"Culture": "Arabic", "mas": 53.125, "Feature": "health", "score": 0.4482839829067685}, {"Culture": "Armenian", "mas": 50.0, "Feature": "health", "score": 0.594055008056703}, {"Culture": "Bulgarian", "mas": 40.0, "Feature": "health", "score": -0.833570146710585}, {"Culture": "Chinese", "mas": 45.0, "Feature": "health", "score": 0.7640272733032246}, {"Culture": "Croatian", "mas": 40.0, "Feature": "health", "score": -1.2722805667836357}, {"Culture": "Danish", "mas": 16.0, "Feature": "health", "score": -0.7743888332267183}, {"Culture": "Dutch", "mas": 34.0, "Feature": "health", "score": -1.0184692369334871}, {"Culture": "English", "mas": 55.888888888888886, "Feature": "health", "score": -0.8692042286005276}, {"Culture": "Estonian", "mas": 30.0, "Feature": "health", "score": 0.3488426843930606}, {"Culture": "Finnish", "mas": 26.0, "Feature": "health", "score": -0.5578915324723454}, {"Culture": "French", "mas": 46.5, "Feature": "health", "score": 1.0194479907187255}, {"Culture": "German", "mas": 71.66666666666667, "Feature": "health", "score": 0.2751795578987418}, {"Culture": "Greek", "mas": 57.0, "Feature": "health", "score": 1.3123448808245812}, {"Culture": "Icelandic", "mas": 10.0, "Feature": "health", "score": -0.4899417733610634}, {"Culture": "Italian", "mas": 70.0, "Feature": "health", "score": -0.2154206996966065}, {"Culture": "Japanese", "mas": 95.0, "Feature": "health", "score": 0.5960262695670664}, {"Culture": "Lithuanian", "mas": 19.0, "Feature": "health", "score": 3.040989464082677}, {"Culture": "Polish", "mas": 64.0, "Feature": "health", "score": 0.5526033949916945}, {"Culture": "Portuguese", "mas": 30.6, "Feature": "health", "score": -0.3672327171796516}, {"Culture": "Romanian", "mas": 42.0, "Feature": "health", "score": -0.7303786613701093}, {"Culture": "Russian", "mas": 36.0, "Feature": "health", "score": -1.0131042024334664}, {"Culture": "Serbian", "mas": 45.5, "Feature": "health", "score": 0.1569098554784928}, {"Culture": "Spanish", "mas": 50.0, "Feature": "health", "score": 1.4859644498826008}, {"Culture": "Swedish", "mas": 5.0, "Feature": "health", "score": -0.6516039591617042}, {"Culture": "Turkish", "mas": 45.0, "Feature": "health", "score": 0.0210824218391648}, {"Culture": "Ukrainian", "mas": 27.0, "Feature": "health", "score": -1.4936966289595683}]}}, {"mode": "vega-lite"});
</script>
</div>
</div>
<p><em>Masculinity vs.&nbsp;LIWC.</em><br> There is a positive correlation between masculinity (assertiveness) and words related to health (eg. clinic, flu, pill) and sexual (eg. horny, love, incest).</p>
<div class="cell" data-execution_count="36">
<div class="cell-output cell-output-display" data-execution_count="36">

<div>

<table class="dataframe table table-sm table-striped">
  <thead>
    <tr>
      <th></th>
      <th>Feature</th>
      <th>Correlation</th>
      <th>P-Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>7</th>
      <td>ipron</td>
      <td>-0.401709</td>
      <td>0.037803</td>
    </tr>
    <tr>
      <th>34</th>
      <td>discrep</td>
      <td>-0.409035</td>
      <td>0.034131</td>
    </tr>
    <tr>
      <th>27</th>
      <td>negemo</td>
      <td>-0.445665</td>
      <td>0.019818</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell" data-execution_count="37">
<div class="cell-output cell-output-display" data-execution_count="37">

<div id="altair-viz-fd783f31e77a46bb92954496d52c779a"></div>
<script type="text/javascript">
  var VEGA_DEBUG = (typeof VEGA_DEBUG == "undefined") ? {} : VEGA_DEBUG;
  (function(spec, embedOpt){
    let outputDiv = document.currentScript.previousElementSibling;
    if (outputDiv.id !== "altair-viz-fd783f31e77a46bb92954496d52c779a") {
      outputDiv = document.getElementById("altair-viz-fd783f31e77a46bb92954496d52c779a");
    }
    const paths = {
      "vega": "https://cdn.jsdelivr.net/npm//vega@5?noext",
      "vega-lib": "https://cdn.jsdelivr.net/npm//vega-lib?noext",
      "vega-lite": "https://cdn.jsdelivr.net/npm//vega-lite@4.17.0?noext",
      "vega-embed": "https://cdn.jsdelivr.net/npm//vega-embed@6?noext",
    };

    function maybeLoadScript(lib, version) {
      var key = `${lib.replace("-", "")}_version`;
      return (VEGA_DEBUG[key] == version) ?
        Promise.resolve(paths[lib]) :
        new Promise(function(resolve, reject) {
          var s = document.createElement('script');
          document.getElementsByTagName("head")[0].appendChild(s);
          s.async = true;
          s.onload = () => {
            VEGA_DEBUG[key] = version;
            return resolve(paths[lib]);
          };
          s.onerror = () => reject(`Error loading script: ${paths[lib]}`);
          s.src = paths[lib];
        });
    }

    function showError(err) {
      outputDiv.innerHTML = `<div class="error" style="color:red;">${err}</div>`;
      throw err;
    }

    function displayChart(vegaEmbed) {
      vegaEmbed(outputDiv, spec, embedOpt)
        .catch(err => showError(`Javascript Error: ${err.message}<br>This usually means there's a typo in your chart specification. See the javascript console for the full traceback.`));
    }

    if(typeof define === "function" && define.amd) {
      requirejs.config({paths});
      require(["vega-embed"], displayChart, err => showError(`Error loading script: ${err.message}`));
    } else {
      maybeLoadScript("vega", "5")
        .then(() => maybeLoadScript("vega-lite", "4.17.0"))
        .then(() => maybeLoadScript("vega-embed", "6"))
        .catch(showError)
        .then(() => displayChart(vegaEmbed));
    }
  })({"config": {"view": {"continuousWidth": 400, "continuousHeight": 300}}, "layer": [{"mark": {"type": "point", "size": 50}, "encoding": {"color": {"field": "Feature", "type": "nominal"}, "tooltip": [{"field": "Culture", "type": "nominal"}, {"field": "Feature", "type": "nominal"}], "x": {"axis": {"title": "Long Term Orientation"}, "field": "ltowvs", "scale": {"zero": false}, "type": "quantitative"}, "y": {"axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}, {"mark": "line", "encoding": {"color": {"field": "Feature", "type": "nominal"}, "x": {"axis": {"title": "Long Term Orientation"}, "field": "ltowvs", "scale": {"zero": false}, "type": "quantitative"}, "y": {"aggregate": "mean", "axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}], "data": {"name": "data-9b8556c80bb843385d86c8de98826511"}, "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json", "datasets": {"data-9b8556c80bb843385d86c8de98826511": [{"Culture": "Albanian", "ltowvs": 61.46095717884131, "Feature": "discrep", "score": 1.148159006027147}, {"Culture": "Arabic", "ltowvs": 20.053211586901767, "Feature": "discrep", "score": 0.4509808287386872}, {"Culture": "Armenian", "ltowvs": 60.95717884130982, "Feature": "discrep", "score": -0.9359882496659342}, {"Culture": "Bulgarian", "ltowvs": 69.0176322418136, "Feature": "discrep", "score": -1.000569833004519}, {"Culture": "Chinese", "ltowvs": 92.94710327455918, "Feature": "discrep", "score": -0.8904027294961888}, {"Culture": "Croatian", "ltowvs": 58.43828715365239, "Feature": "discrep", "score": 0.4470674513734188}, {"Culture": "Danish", "ltowvs": 34.76070528967254, "Feature": "discrep", "score": 0.7703643419632267}, {"Culture": "Dutch", "ltowvs": 74.43324937027708, "Feature": "discrep", "score": -0.8006847316394666}, {"Culture": "English", "ltowvs": 24.95689896445564, "Feature": "discrep", "score": -0.2345142479190273}, {"Culture": "Estonian", "ltowvs": 82.11586901763224, "Feature": "discrep", "score": 2.15833072219672}, {"Culture": "Finnish", "ltowvs": 38.28715365239295, "Feature": "discrep", "score": 0.4662347422338749}, {"Culture": "French", "ltowvs": 45.23803526448363, "Feature": "discrep", "score": 0.8313772081145268}, {"Culture": "German", "ltowvs": 72.29219143576826, "Feature": "discrep", "score": 0.5931486343958899}, {"Culture": "Greek", "ltowvs": 45.34005037783375, "Feature": "discrep", "score": -0.0042912243615674}, {"Culture": "Icelandic", "ltowvs": 27.95969773299748, "Feature": "discrep", "score": 1.602750800101279}, {"Culture": "Italian", "ltowvs": 61.460957178841305, "Feature": "discrep", "score": 0.289362851156737}, {"Culture": "Japanese", "ltowvs": 87.9093198992443, "Feature": "discrep", "score": -1.0355152016726688}, {"Culture": "Lithuanian", "ltowvs": 81.86397984886649, "Feature": "discrep", "score": -0.6046233394558373}, {"Culture": "Polish", "ltowvs": 37.78337531486146, "Feature": "discrep", "score": -1.32752988935464}, {"Culture": "Portuguese", "ltowvs": 22.008060453400503, "Feature": "discrep", "score": -0.108241321130586}, {"Culture": "Romanian", "ltowvs": 51.88916876574307, "Feature": "discrep", "score": 1.0088123426715507}, {"Culture": "Russian", "ltowvs": 81.360201511335, "Feature": "discrep", "score": -1.074341301475016}, {"Culture": "Serbian", "ltowvs": 63.727959697733, "Feature": "discrep", "score": -0.2810075640310043}, {"Culture": "Spanish", "ltowvs": 21.701651273439687, "Feature": "discrep", "score": 0.9963509496822832}, {"Culture": "Swedish", "ltowvs": 52.89672544080605, "Feature": "discrep", "score": 0.3679114690756854}, {"Culture": "Turkish", "ltowvs": 45.59193954659949, "Feature": "discrep", "score": -0.6604809863037199}, {"Culture": "Ukrainian", "ltowvs": 86.0, "Feature": "discrep", "score": -2.17266072822086}]}}, {"mode": "vega-lite"});
</script>
</div>
</div>
<p><em>Long Term Orientation vs.&nbsp;LIWC.</em><br> There is a negative correlation between a long term orientation and the use of discrep words (eg. should, would, could).</p>
<div class="cell" data-execution_count="38">
<div class="cell-output cell-output-display" data-execution_count="38">

<div>

<table class="dataframe table table-sm table-striped">
  <thead>
    <tr>
      <th></th>
      <th>Feature</th>
      <th>Correlation</th>
      <th>P-Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>51</th>
      <td>space</td>
      <td>0.471756</td>
      <td>0.012982</td>
    </tr>
    <tr>
      <th>56</th>
      <td>home</td>
      <td>0.432977</td>
      <td>0.024077</td>
    </tr>
    <tr>
      <th>18</th>
      <td>quant</td>
      <td>0.403359</td>
      <td>0.036950</td>
    </tr>
    <tr>
      <th>60</th>
      <td>assent</td>
      <td>0.397252</td>
      <td>0.040188</td>
    </tr>
    <tr>
      <th>0</th>
      <td>pronoun</td>
      <td>-0.429008</td>
      <td>0.025553</td>
    </tr>
    <tr>
      <th>50</th>
      <td>motion</td>
      <td>-0.502595</td>
      <td>0.007545</td>
    </tr>
    <tr>
      <th>4</th>
      <td>you</td>
      <td>-0.512061</td>
      <td>0.006324</td>
    </tr>
    <tr>
      <th>21</th>
      <td>social</td>
      <td>-0.528550</td>
      <td>0.004594</td>
    </tr>
    <tr>
      <th>22</th>
      <td>family</td>
      <td>-0.535878</td>
      <td>0.003965</td>
    </tr>
    <tr>
      <th>1</th>
      <td>ppron</td>
      <td>-0.574657</td>
      <td>0.001718</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell" data-execution_count="39">
<div class="cell-output cell-output-display" data-execution_count="39">

<div id="altair-viz-f82dcefc7284427c9080003fccc3b424"></div>
<script type="text/javascript">
  var VEGA_DEBUG = (typeof VEGA_DEBUG == "undefined") ? {} : VEGA_DEBUG;
  (function(spec, embedOpt){
    let outputDiv = document.currentScript.previousElementSibling;
    if (outputDiv.id !== "altair-viz-f82dcefc7284427c9080003fccc3b424") {
      outputDiv = document.getElementById("altair-viz-f82dcefc7284427c9080003fccc3b424");
    }
    const paths = {
      "vega": "https://cdn.jsdelivr.net/npm//vega@5?noext",
      "vega-lib": "https://cdn.jsdelivr.net/npm//vega-lib?noext",
      "vega-lite": "https://cdn.jsdelivr.net/npm//vega-lite@4.17.0?noext",
      "vega-embed": "https://cdn.jsdelivr.net/npm//vega-embed@6?noext",
    };

    function maybeLoadScript(lib, version) {
      var key = `${lib.replace("-", "")}_version`;
      return (VEGA_DEBUG[key] == version) ?
        Promise.resolve(paths[lib]) :
        new Promise(function(resolve, reject) {
          var s = document.createElement('script');
          document.getElementsByTagName("head")[0].appendChild(s);
          s.async = true;
          s.onload = () => {
            VEGA_DEBUG[key] = version;
            return resolve(paths[lib]);
          };
          s.onerror = () => reject(`Error loading script: ${paths[lib]}`);
          s.src = paths[lib];
        });
    }

    function showError(err) {
      outputDiv.innerHTML = `<div class="error" style="color:red;">${err}</div>`;
      throw err;
    }

    function displayChart(vegaEmbed) {
      vegaEmbed(outputDiv, spec, embedOpt)
        .catch(err => showError(`Javascript Error: ${err.message}<br>This usually means there's a typo in your chart specification. See the javascript console for the full traceback.`));
    }

    if(typeof define === "function" && define.amd) {
      requirejs.config({paths});
      require(["vega-embed"], displayChart, err => showError(`Error loading script: ${err.message}`));
    } else {
      maybeLoadScript("vega", "5")
        .then(() => maybeLoadScript("vega-lite", "4.17.0"))
        .then(() => maybeLoadScript("vega-embed", "6"))
        .catch(showError)
        .then(() => displayChart(vegaEmbed));
    }
  })({"config": {"view": {"continuousWidth": 400, "continuousHeight": 300}}, "layer": [{"mark": {"type": "point", "size": 50}, "encoding": {"color": {"field": "Feature", "type": "nominal"}, "tooltip": [{"field": "Culture", "type": "nominal"}, {"field": "Feature", "type": "nominal"}], "x": {"axis": {"title": "Indulgence"}, "field": "ivr", "scale": {"zero": false}, "type": "quantitative"}, "y": {"axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}, {"mark": "line", "encoding": {"color": {"field": "Feature", "type": "nominal"}, "x": {"axis": {"title": "Indulgence"}, "field": "ivr", "scale": {"zero": false}, "type": "quantitative"}, "y": {"aggregate": "mean", "axis": {"title": "Feature Score (normalized)"}, "field": "score", "scale": {"zero": false}, "type": "quantitative"}}}], "data": {"name": "data-5bcf5929cadbb667c9851aff5a8a05d2"}, "$schema": "https://vega.github.io/schema/vega-lite/v4.17.0.json", "datasets": {"data-5bcf5929cadbb667c9851aff5a8a05d2": [{"Culture": "Albanian", "ivr": 14.50892857142857, "Feature": "home", "score": 1.68193678458591}, {"Culture": "Arabic", "ivr": 29.13839285714285, "Feature": "home", "score": -0.962595195831992}, {"Culture": "Armenian", "ivr": 25.0, "Feature": "home", "score": -0.3289340641775464}, {"Culture": "Bulgarian", "ivr": 15.848214285714285, "Feature": "home", "score": -0.018471670329682}, {"Culture": "Chinese", "ivr": 49.10714285714285, "Feature": "home", "score": 0.2377480980652933}, {"Culture": "Croatian", "ivr": 33.25892857142857, "Feature": "home", "score": -1.3663164856758734}, {"Culture": "Danish", "ivr": 69.64285714285714, "Feature": "home", "score": 0.8455006280050923}, {"Culture": "Dutch", "ivr": 62.50000000000001, "Feature": "home", "score": -0.0032107138938}, {"Culture": "English", "ivr": 69.67162698412697, "Feature": "home", "score": 1.7261275972204344}, {"Culture": "Estonian", "ivr": 16.294642857142854, "Feature": "home", "score": -1.0292536469364943}, {"Culture": "Finnish", "ivr": 57.36607142857142, "Feature": "home", "score": 1.285304256309182}, {"Culture": "French", "ivr": 32.92410714285712, "Feature": "home", "score": -1.580880956425127}, {"Culture": "German", "ivr": 56.398809523809526, "Feature": "home", "score": 0.7019198680397296}, {"Culture": "Greek", "ivr": 49.55357142857142, "Feature": "home", "score": -1.8532316073619688}, {"Culture": "Icelandic", "ivr": 66.74107142857142, "Feature": "home", "score": 0.1728817169923353}, {"Culture": "Italian", "ivr": 29.6875, "Feature": "home", "score": 0.2318894748151645}, {"Culture": "Japanese", "ivr": 41.7410714285714, "Feature": "home", "score": -0.3658746322370907}, {"Culture": "Lithuanian", "ivr": 15.624999999999998, "Feature": "home", "score": -1.438455844259183}, {"Culture": "Polish", "ivr": 29.241071428571427, "Feature": "home", "score": 0.2255216292480293}, {"Culture": "Portuguese", "ivr": 67.68214285714285, "Feature": "home", "score": 0.9094325200279664}, {"Culture": "Romanian", "ivr": 19.866071428571427, "Feature": "home", "score": -0.351047718821422}, {"Culture": "Russian", "ivr": 19.866071428571427, "Feature": "home", "score": 0.3229774797991464}, {"Culture": "Serbian", "ivr": 23.99553571428571, "Feature": "home", "score": -1.0389237005788738}, {"Culture": "Spanish", "ivr": 72.73115079365078, "Feature": "home", "score": 1.5586668256365623}, {"Culture": "Swedish", "ivr": 77.67857142857142, "Feature": "home", "score": 0.0610899418203108}, {"Culture": "Turkish", "ivr": 49.10714285714285, "Feature": "home", "score": 0.6381259701799863}, {"Culture": "Ukrainian", "ivr": 14.0, "Feature": "home", "score": -0.2619265542161055}, {"Culture": "Albanian", "ivr": 14.50892857142857, "Feature": "family", "score": 2.4081390544071004}, {"Culture": "Arabic", "ivr": 29.13839285714285, "Feature": "family", "score": -0.7357494901670004}, {"Culture": "Armenian", "ivr": 25.0, "Feature": "family", "score": 0.8092615677259698}, {"Culture": "Bulgarian", "ivr": 15.848214285714285, "Feature": "family", "score": 1.339699443651562}, {"Culture": "Chinese", "ivr": 49.10714285714285, "Feature": "family", "score": -0.1426494717788803}, {"Culture": "Croatian", "ivr": 33.25892857142857, "Feature": "family", "score": 1.013892732224979}, {"Culture": "Danish", "ivr": 69.64285714285714, "Feature": "family", "score": -1.120526992089744}, {"Culture": "Dutch", "ivr": 62.50000000000001, "Feature": "family", "score": -0.5919689311650683}, {"Culture": "English", "ivr": 69.67162698412697, "Feature": "family", "score": -0.8377886780606637}, {"Culture": "Estonian", "ivr": 16.294642857142854, "Feature": "family", "score": -1.4218646597625535}, {"Culture": "Finnish", "ivr": 57.36607142857142, "Feature": "family", "score": 0.285851191017724}, {"Culture": "French", "ivr": 32.92410714285712, "Feature": "family", "score": -1.2614727097565988}, {"Culture": "German", "ivr": 56.398809523809526, "Feature": "family", "score": -0.3387232838156294}, {"Culture": "Greek", "ivr": 49.55357142857142, "Feature": "family", "score": -1.5643308267952931}, {"Culture": "Icelandic", "ivr": 66.74107142857142, "Feature": "family", "score": 0.0964113613006823}, {"Culture": "Italian", "ivr": 29.6875, "Feature": "family", "score": 0.3046912703525679}, {"Culture": "Japanese", "ivr": 41.7410714285714, "Feature": "family", "score": -0.446290765909395}, {"Culture": "Lithuanian", "ivr": 15.624999999999998, "Feature": "family", "score": 1.2400355707571538}, {"Culture": "Polish", "ivr": 29.241071428571427, "Feature": "family", "score": -0.7886957559978481}, {"Culture": "Portuguese", "ivr": 67.68214285714285, "Feature": "family", "score": 0.1706432527466981}, {"Culture": "Romanian", "ivr": 19.866071428571427, "Feature": "family", "score": 0.0511736187929132}, {"Culture": "Russian", "ivr": 19.866071428571427, "Feature": "family", "score": 0.2313137087098722}, {"Culture": "Serbian", "ivr": 23.99553571428571, "Feature": "family", "score": 1.210660329414481}, {"Culture": "Spanish", "ivr": 72.73115079365078, "Feature": "family", "score": -0.495304258389552}, {"Culture": "Swedish", "ivr": 77.67857142857142, "Feature": "family", "score": -1.2668970730076856}, {"Culture": "Turkish", "ivr": 49.10714285714285, "Feature": "family", "score": 0.81909059878386}, {"Culture": "Ukrainian", "ivr": 14.0, "Feature": "family", "score": 1.031399196810326}]}}, {"mode": "vega-lite"});
</script>
</div>
</div>
<p><em>Indulgence vs.&nbsp;LIWC.</em> There is a negative correlation between indulgence and home words, and a positive correlation between indulgence and family words.</p>
</section>
<section id="conclusion" class="level2">
<h2 class="anchored" data-anchor-id="conclusion">Conclusion</h2>
<p>Overall, I found that there are many correlations between the words used in the folktales of a nation and the nation’s values. Power distance is positively related to family and social, while individualism is negatively related to family and social. Family likely contributes to the correlation seen with social. Family’s positive correlation to power distance shows that families are a large institution where less powerful members accept their position. Thus, nations that tell more stories about families value families more, and accept their position of power more.Family’s negative association with individualism is due to the importance of families in community and interdependent lifestyles. Uncertainty avoidance is negatively related to auxverbs and discrep words. This is opposite of what I expected: since nations with a higher uncertainty avoidance are more stressed about an unknown future, I would have expected that they use more certain words in relation to the future (discrep words – should, would, could). Masculinity is positively related to health and sexual words. Since Hofstede defined masculinity using a traditional understanding of masculinity as assertive, the health component likely comes from the similarity of assertive qualities and strong qualities. The sexual component is likely due to the ideal of a man having a love interest. Long term orientation is positively related to indulgence and family words. Since short term orientation (confusingly!) refers to a strong respect for tradition, the long term oriented cultures having more indulgence words agrees with my expectation. <br> <br> Thus, we see that folktales do often reflect cultural values. Storytelling is an important way to communicate values. While folktales reflect long-standing values, other stories might be able to reveal other values of society: the way Frankenstein came out at a time galvanization was popular, or our current stories about AI.</p>
<p><a href="https://github.com/graceshaoy/folktales">GitHub link</a></p>
</section>
<section id="bibliography" class="level2">
<h2 class="anchored" data-anchor-id="bibliography">Bibliography</h2>
<p>DeWall, C.N., Pond, R.S., Jr., Campbell, W.K. &amp; Twenge, J.M. (2011). “Tuning in to Psychological Change: Linguistic Markers of Psychological Traits and Emotions Over Time in Popular U.S. Song Lyrics” Psychology of Aesthetics, Creativity, and the Arts. doi: 10.1037/a0023195<br><br> Fischer, J.L. (1963). “The Sociopsychological Analysis of Folktales” <em>Current Anthropology 4(3)</em> 233-336. https://doi.org/10.1086/20037<br><br> Hofstede, G. (2011). “Dimensionalizing Cultures: The Hofstede Model in Context” <em>Online Readings in Psychology and Culture, Unit 2</em>. https://scholarworks.gvsu.edu/orpc/vol2/iss1/8/<br><br> Morling, B., &amp; Lamoreaux, M. (2008). “Measuring Culture Outside the Head: A Meta-Analysis of Individualism–Collectivism in Cultural Products” <em>Personality and Social Psychology Reivew, 12(3)</em>, 199-221. https://doi.org/10.1177/1088868308318260<br><br> Pennebaker, J.W., Chung, C.K. (2011). “Linguistic Inquiry and Word Count (LIWC): Pronounced ‘Luke’… and Other Useful Facts” <em>Applied Natural Language Processing: Identification, Investigation, and Resolution.</em> edited by McCarthy, Philip M. and Chutima Boonthum-Denecke, 206-229. https://doi.org/10.4018/978-1-60960-741-8.ch012<br><br> Shytov, A., Mai, C. (2008). “Folktales as the Source of Law” <em>Archives for Philosophy of Law and Social Philosophy 94(3)</em> 325-336. https://www.jstor.org/stable/23680880<br><br> Tomasello, M. (1999). “The Human Adaptation for Culture” <em>Annual Review of Anthropology 28</em>, 509-529. https://www.jstor.org/stable/223404<br><br> Zipes, J. (2019). “Speaking the Truth with Folk and Fairy Tales: The Power of the Powerless.” <em>The Journal of American Folklore 132(525)</em> 243–59. https://doi.org/10.5406/jamerfolk.132.525.0243.</p>
</section>

</main>
<!-- /main column -->
<script id="quarto-html-after-body" type="application/javascript">
window.document.addEventListener("DOMContentLoaded", function (event) {
  const toggleBodyColorMode = (bsSheetEl) => {
    const mode = bsSheetEl.getAttribute("data-mode");
    const bodyEl = window.document.querySelector("body");
    if (mode === "dark") {
      bodyEl.classList.add("quarto-dark");
      bodyEl.classList.remove("quarto-light");
    } else {
      bodyEl.classList.add("quarto-light");
      bodyEl.classList.remove("quarto-dark");
    }
  }
  const toggleBodyColorPrimary = () => {
    const bsSheetEl = window.document.querySelector("link#quarto-bootstrap");
    if (bsSheetEl) {
      toggleBodyColorMode(bsSheetEl);
    }
  }
  toggleBodyColorPrimary();  
  const icon = "";
  const anchorJS = new window.AnchorJS();
  anchorJS.options = {
    placement: 'right',
    icon: icon
  };
  anchorJS.add('.anchored');
  const clipboard = new window.ClipboardJS('.code-copy-button', {
    target: function(trigger) {
      return trigger.previousElementSibling;
    }
  });
  clipboard.on('success', function(e) {
    // button target
    const button = e.trigger;
    // don't keep focus
    button.blur();
    // flash "checked"
    button.classList.add('code-copy-button-checked');
    var currentTitle = button.getAttribute("title");
    button.setAttribute("title", "Copied!");
    let tooltip;
    if (window.bootstrap) {
      button.setAttribute("data-bs-toggle", "tooltip");
      button.setAttribute("data-bs-placement", "left");
      button.setAttribute("data-bs-title", "Copied!");
      tooltip = new bootstrap.Tooltip(button, 
        { trigger: "manual", 
          customClass: "code-copy-button-tooltip",
          offset: [0, -8]});
      tooltip.show();    
    }
    setTimeout(function() {
      if (tooltip) {
        tooltip.hide();
        button.removeAttribute("data-bs-title");
        button.removeAttribute("data-bs-toggle");
        button.removeAttribute("data-bs-placement");
      }
      button.setAttribute("title", currentTitle);
      button.classList.remove('code-copy-button-checked');
    }, 1000);
    // clear code selection
    e.clearSelection();
  });
  function tippyHover(el, contentFn) {
    const config = {
      allowHTML: true,
      content: contentFn,
      maxWidth: 500,
      delay: 100,
      arrow: false,
      appendTo: function(el) {
          return el.parentElement;
      },
      interactive: true,
      interactiveBorder: 10,
      theme: 'quarto',
      placement: 'bottom-start'
    };
    window.tippy(el, config); 
  }
  const noterefs = window.document.querySelectorAll('a[role="doc-noteref"]');
  for (var i=0; i<noterefs.length; i++) {
    const ref = noterefs[i];
    tippyHover(ref, function() {
      // use id or data attribute instead here
      let href = ref.getAttribute('data-footnote-href') || ref.getAttribute('href');
      try { href = new URL(href).hash; } catch {}
      const id = href.replace(/^#\/?/, "");
      const note = window.document.getElementById(id);
      return note.innerHTML;
    });
  }
  const findCites = (el) => {
    const parentEl = el.parentElement;
    if (parentEl) {
      const cites = parentEl.dataset.cites;
      if (cites) {
        return {
          el,
          cites: cites.split(' ')
        };
      } else {
        return findCites(el.parentElement)
      }
    } else {
      return undefined;
    }
  };
  var bibliorefs = window.document.querySelectorAll('a[role="doc-biblioref"]');
  for (var i=0; i<bibliorefs.length; i++) {
    const ref = bibliorefs[i];
    const citeInfo = findCites(ref);
    if (citeInfo) {
      tippyHover(citeInfo.el, function() {
        var popup = window.document.createElement('div');
        citeInfo.cites.forEach(function(cite) {
          var citeDiv = window.document.createElement('div');
          citeDiv.classList.add('hanging-indent');
          citeDiv.classList.add('csl-entry');
          var biblioDiv = window.document.getElementById('ref-' + cite);
          if (biblioDiv) {
            citeDiv.innerHTML = biblioDiv.innerHTML;
          }
          popup.appendChild(citeDiv);
        });
        return popup.innerHTML;
      });
    }
  }
});
</script>
</div> <!-- /content -->



</body></html>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
