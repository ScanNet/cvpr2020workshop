---
layout: project
urltitle:  "ScanNet Indoor Scene Understanding Challenge"
title: "ScanNet Indoor Scene Understanding Challenge"
categories: cvpr, workshop, computer vision, computer graphics, visual learning, simulation environments, robotics, machine learning, natural language processing, reinforcement learning
permalink: /
favicon: /static/img/ico/favicon.png
bibtex: true
paper: true
acknowledgements: ""
---

<br>
<div class="row">
  <div class="col-xs-12">
    <center><h1>ScanNet Indoor Scene Understanding Challenge</h1></center>
    <center><h2>CVPR 2020 Workshop, Seattle, WA</h2></center>
    <center>June 19, 2020</center>
  </div>
</div>

<hr>

<div class="row" id="intro">
  <div class="col-md-12">
    <img src="{{ "/static/img/splash.jpg" | prepend:site.baseurl }}">
  </div>
</div>

<br>
<div class="row" id="cfp">
  <div class="col-xs-12">
    <h2>Introduction</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
    <p>
      3D scene understanding for indoor environments is becoming an increasingly important area.
      Application domains such as augmented and virtual reality, computational photography, interior design, and autonomous mobile robots all require a deep understanding of 3D interior spaces, the semantics of objects that are present, and their relative configurations in 3D space.
    </p>
    <p>
      We present the first comprehensive challenge for 3D scene understanding of entire rooms at the object instance-level with 5 tasks based on the ScanNet dataset.
      The ScanNet dataset is a large-scale semantically annotated dataset of 3D mesh reconstructions of interior spaces (approx. 1500 rooms and 2.5 million RGB-D frames).
      It is used by more than 480 research groups to develop and benchmark state-of-the-art approaches in semantic scene understanding.
      A key goal of this challenge is to compare state-of-the-art approaches operating on image data (including RGB-D) with approaches operating directly on 3D data (point cloud, or surface mesh representations).
      Additionally, we pose both object category label prediction (commonly referred to as semantic segmentation), and instance-level object recognition (object instance prediction and category label prediction).
      We propose five tasks that cover this space:
    </p>
    <ul>
      <li>
        <strong>2D semantic label prediction</strong>: prediction of object category labels from 2D image representation
      </li>
      <li>
        <strong>2D semantic instance prediction</strong>: prediction of object instance and category labels from 2D image representation
      </li>
      <li>
        <strong>3D semantic label prediction</strong>: prediction of object category labels from 3D representation
      </li>
      <li>
        <strong>3D semantic instance prediction</strong>: prediction of object instance and category labels from 3D representation
      </li>
      <li>
        <strong>Scene type classification</strong>: classification of entire 3D room into a scene type
      </li>
    </ul>
    <p>
      For each task, challenge participants are provided with prepared training, validation, and test datasets, and automated evaluation scripts.
      In addition to the public train-val-test split, benchmarking is done on a hidden test set whose raw data can be downloaded without annotations; in order to participate in the benchmark, the predictions on the hidden test set are uploaded to the evaluation server, where they are evaluated.
      Submission is restricted to submissions every two weeks to avoid finetuning on the test dataset.
      See more details at <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/documentation">http://kaldir.vc.in.tum.de/scannet_benchmark/documentation</a> if you would like to participate in the challenge.
      The evaluation server leaderboard is live at <a href="http://kaldir.vc.in.tum.de/scannet_benchmark/">http://kaldir.vc.in.tum.de/scannet_benchmark/</a>.
    </p>
  </div>
</div>
<br>

<div class="row" id="tasks">
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_label_2d.jpg" | prepend:site.baseurl }}">
    <p>2D semantic label prediction</p>
  </div>
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_instance_2d.jpg" | prepend:site.baseurl }}">
    <p>2D semantic instance prediction</p>
  </div>
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_label_3d.jpg" | prepend:site.baseurl }}">
    <p>3D semantic label prediction</p>
  </div>
  <div class="col-md-6 text-center">
    <img src="{{ "/static/img/semantic_instance_3d.jpg" | prepend:site.baseurl }}">
    <p>3D semantic instance prediction</p>
  </div>
  <!-- <div class="col-md-4">
    <p>&nbsp;</p>
  </div> -->
  <!-- <div class="col-md-4">
    <img src="{{ "/static/img/scene_type_classification.jpg" | prepend:site.baseurl }}">
    <p>Scene type classification</p>
  </div> -->
</div>

<div class="row" id="schedule">
  <div class="col-xs-12">
    <h2>Important Dates</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <table class="table table-striped">
      <tbody>
        <tr>
          <td>Poster Submission Deadline</td>
          <td>May 20 2020</td>
        </tr>
        <tr>
          <td>Notification to Authors</td>
          <td>May 25 2020</td>
        </tr>
        <tr>
          <td>Workshop Date</td>
          <td>June 19 2020</td>
        </tr>
      </tbody>
    </table>
  </div>
</div><br>

<div class="row" id="cfp">
  <div class="col-xs-12">
    <h2>Posters</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
    <p>
      To submit a poster to the workshop, please email the poster as .pdf file to scannet@googlegroups.com.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-xs-12">
    <h2>Schedule</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
     <table class="table table-striped">
      <tbody>
        <tr>
          <td>Welcome and Introduction</td>
          <td>1:45pm - 2:00pm</td>
        </tr>
        <tr>
          <td>Implicit Neural Representations: From Objects to 3D Scenes (Andreas Geiger)</td>
          <td>2:00pm - 2:30pm</td>
        </tr>
        <tr>
          <td>Winner Talk 1 </td>
          <td>2:30pm - 2:45pm</td>
        </tr>
        <tr>
          <td>Winner Talk 2 </td>
          <td>2:45pm - 3:00pm</td>
        </tr>
        <tr>
          <td>Winner Talk 3 </td>
          <td>3:00pm - 3:15pm</td>
        </tr>
        <tr>
          <td>Winner Talk 4 </td>
          <td>3:15pm - 3:30pm</td>
        </tr>
        <tr>
          <td>Break and poster session</td>
          <td>3:30pm - 4:00pm</td>
        </tr>
        <tr>
          <td>CVPR is a Contemporary Art Exhibition (Yasutaka Furukawa)</td>
          <td>4:00pm - 4:30pm</td>
        </tr>
        <tr>
          <td>Semantic Scene Reconstruction from RGBD Scans (Thomas Funkhouser)</td>
          <td>4:30pm - 5:00pm</td>
        </tr>
        <tr>
          <td>Panel Discussion and Conclusion</td>
          <td>5:00pm - 5:30pm</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>

<br>
<div class="row">
  <div class="col-xs-12">
    <h2>Invited Speakers</h2>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="http://www.cvlibs.net"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/andreas_geiger.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="http://www.cvlibs.net">Andreas Geiger</a></b> is a professor of computer science heading the Autonomous Vision Group (AVG) at the University of Tubingen and the MPI for Intelligent Systems in Tubingen, Germany. His research is focused on 3D scene understanding, reconstruction, motion estimation, generative modeling and sensory-motor control in the context of autonomous systems. His work aims to make artificial intelligent systems such as self-driving cars or household robots more autonomous, efficient, robust and safe.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://www.cs.sfu.ca/~furukawa/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/yasu_furukawa.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://www.cs.sfu.ca/~furukawa/">Yasutaka Furukawa</a></b> is an associate professor of Computing Science at Simon Fraser University. Prior to SFU, he was an assistant professor at Washington University in St. Louis. Before WUSTL, he was a software engineer at Google. Before Google, he was a post-doctoral research associate at University of Washington. He worked with Prof. Seitz and Prof. Curless at University of Washington, and Rick Szeliski at Facebook (was at Microsoft Research). He completed his Ph.D. under the supervision of Prof. Ponce at Computer Science Department of University of Illinois at Urbana-Champaign in May 2008.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-md-12">
    <a href="https://www.cs.princeton.edu/~funk/"><img class="people-pic" style="float:left;margin-right:50px;" src="{{ "/static/img/people/tom_funkhouser.png" | prepend:site.baseurl }}"></a>
    <p>
      <b><a href="https://www.cs.princeton.edu/~funk/">Thomas Funkhouser</a></b> is a senior research scientist at Google and the David
M. Siegel Professor of Computer Science, Emeritus, at Princeton University.  He received a PhD in computer science from UC Berkeley in
1993 and was a member of the technical staff at Bell Labs until 1997 before joining the faculty at Princeton.  For most of his career, he focused on research problems in computer graphics, including foundational work on 3D shape retrieval, analysis, and modeling.   His
most recent research has focused on 3D scene understanding in computer vision. He has published more than 100 research papers and received several awards, including the ACM SIGGRAPH Computer Graphics Achievement Award, ACM SIGGRAPH Academy, ACM Fellow, NSF Career Award, Emerson Electric, E. Lawrence Keyes Faculty Advancement Award, Google Faculty Research Awards, University Council Excellence in Teaching Awards, and a Sloan Fellowship.
    </p>
  </div>
</div><br>

<div class="row">
  <div class="col-xs-12">
    <h2>Organizers</h2>
  </div>
</div>

<div class="row">
  <div class="col-xs-2">
    <a href="https://angeladai.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/angela.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://angeladai.github.io/">Angela Dai</a>
      <h6>Technical University of Munich</h6>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://angelxuanchang.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/angel.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://angelxuanchang.github.io/">Angel X. Chang</a>
      <h6>Eloquent Labs, Simon Fraser University</h6>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://msavva.github.io/">
      <img class="people-pic" src="{{ "/static/img/people/manolis.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://msavva.github.io/">Manolis Savva</a>
      <h6>Simon Fraser University, Facebook AI Research</h6>
    </div>
  </div>

  <div class="col-xs-2">
    <a href="https://niessnerlab.org/members/matthias_niessner/profile.html">
      <img class="people-pic" src="{{ "/static/img/people/matthias.png" | prepend:site.baseurl }}">
    </a>
    <div class="people-name">
      <a href="https://niessnerlab.org/members/matthias_niessner/profile.html">Matthias Niessner</a>
      <h6>Technical University of Munich</h6>
    </div>
  </div>
</div>

<hr>

<div class="row">
  <div class="col-xs-12">
    <h2>Acknowledgments</h2>
  </div>
</div>
<a name="/acknowledgements"></a>
<div class="row">
  <div class="col-xs-12">
    <p>
      Thanks to <span style="color:#1a1aff;font-weight:400;"> <a href="https://visualdialog.org/">visualdialog.org</a></span> for the webpage format.
    </p>
  </div>
</div>
