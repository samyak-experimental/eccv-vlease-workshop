---
layout: project
urltitle:  "Embodied Question Answering"
title: "Embodied Question Answering"
categories: deep learning, computer vision, natural language processing, machine learning, reinforcement learning
permalink: /
favicon: /static/img/embodiedqa/favicon.png
bibtex: true
paper: true
acknowledgements: "We are grateful to the developers of PyTorch for building an excellent framework.
We thank Yuxin Wu for help with the House3D environment.
This work was funded in part by NSF CAREER awards to DB and DP, ONR YIP awards
to DP and DB, ONR Grant N00014-14-1-0679 to DB, ONR Grant N00014-16-1-2713 to DP,
an Allen Distinguished Investigator award to DP from the Paul G. Allen Family Foundation,
Google Faculty Research Awards to DP and DB, Amazon Academic Research Awards to DP and DB,
AWS in Education Research grant to DB, and NVIDIA GPU donations to DB. The views and
conclusions contained herein are those of the authors and should not be interpreted as
necessarily representing the official policies or endorsements, either expressed
or implied, of the U.S. Government, or any sponsor."
---

<br>
<div class="row">
  <div class="col-xs-12">
    <h2>What is Embodied Question Answering?</h2>
  </div>
</div>
<div class="row">
  <div class="col-xs-12">
    <p>
      Embodied Question Answering is a new AI task where an agent is spawned at a random location in a 3D environment and
      asked a natural language question ("What color is the car?").
      In order to answer, the agent
      must first intelligently navigate to explore the environment,
      gather information through first-person (egocentric) vision, and then answer the question ("orange").
    </p>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    <img src="/static/img/embodiedqa/teaser.png">
  </div>
</div>

<br>
<div class="row">
  <div class="col-xs-12">
    <img src="/static/img/embodiedqa/model.jpg">
  </div>
</div>

<!-- <div class="row" style="margin-top:30px;">
  <div class="col-xs-12 col-sm-7">
    <h3>What is Visual Dialog?</h3>
    <p>
      Visual Dialog is a novel task that requires an AI agent to hold a meaningful dialog with humans in natural, conversational language about visual content.
      Specifically, given an image, a dialog history, and a follow-up question about the image, the agent has to answer the question.
    </p>
  </div>
  <ul style="margin:0 10px 10px;" class="col-xs-12 col-sm-4"><a href="#visdial">VisDial dataset</a>:
    <li>
      120k images from <a href="http://mscoco.org">COCO</a>
    </li>
    <li>
      1 dialog / image
    </li>
    <li>
      10 rounds of question-answers / dialog
    </li>
    <li>
      Total 1.2M dialog question-answers
    </li>
  </ul>
  <div class="col-xs-12">
    <span style="color:#e74c3c;font-weight:400;">Apr 2017</span> — <a href="//github.com/batra-mlp-lab/visdial">Torch code for training/evaluating Visual Dialog models</a>, <a href="https://github.com/batra-mlp-lab/visdial#download-extracted-features--pretrained-models">pretrained models</a> and <a href="http://demo.visualdialog.org">Visual Chatbot demo</a> are now available!<br>
    <span style="color:#e74c3c;font-weight:400;">Mar 2017</span> — <a href="/data">VisDial v0.9 dataset</a> and <a href="//github.com/batra-mlp-lab/visdial-amt-chat">code for real-time chat interface used to collect data on AMT</a> are now available!<br>
  </div>
</div>
<hr> -->

<!-- <div class="row">
  <div class="col-sm-6">
    <span style="font-weight:400;">Email</span> — contact@visualdialog.org
    <br>
    <br>
  </div>
  <div class="col-sm-6">
    <form action="https://tinyletter.com/visualdialog" method="post" target="popupwindow" onsubmit="window.open('https://tinyletter.com/visualdialog', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true">
      <div class="form-group">
        <label class="control-label" for="tlemail">Subscribe for Visual Dialog release updates</label>
        <input class="form-control" type="text" name="email" id="tlemail" placeholder="Email address"/>
      </div>
      <input type="hidden" value="1" name="embed"/>
      <button class="btn btn-primary" type="submit">Subscribe</button>
    </form>
  </div>
</div>
<a name="/bibtex"></a>
<hr> -->

<hr>
<div class="row">
    <div class="col-xs-12">
        <h3>Embodied Question Answering</h3>
    </div>
    <div class="col-xs-12" style="margin-top: 3px; color: #666;">
        Abhishek Das, Samyak Datta, Georgia Gkioxari, Stefan Lee, Devi Parikh, Dhruv Batra<br>
    </div>
    <div class="col-xs-12" style="margin-top: 3px; color: #666;">
      [<a href="bib/embodiedqa.bib.txt">Bibtex</a>] [<a href="http://embodiedqa.org/paper.pdf">PDF</a>]
    </div>
</div>
<div class="row">
    <div class="col-xs-12">
        <a href="http://embodiedqa.org/paper.pdf">
          <img class="thumb" src="/static/img/embodiedqa/thumb.jpg">
        </a>
    </div>
</div>
<hr>

<div class="row">
  <div class="col-xs-12">
    <div class="vid-container">
      <iframe src="https://www.youtube.com/embed/gVj-TeIJfrk" allowfullscreen></iframe>
    </div>
  </div>
</div>
<hr>

{% if page.acknowledgements %}
<div class="row">
  <div class="col-xs-12">
    <h2>Acknowledgements</h2>
  </div>
</div>
<a name="/acknowledgements"></a>
<div class="row">
  <div class="col-xs-12">
    <p>
      {{ page.acknowledgements }}
    </p>
  </div>
</div>
{% endif %}

<!-- <div class="row">
  <div class="col-xs-12">
    <h2>Sponsors</h2>
  </div>
</div>
<a name="/sponsors"></a>
<div class="row">
  <div class="col-xs-12 sponsor">
    <img src="/static/img/ico/nsf_logo.jpg">
    <img src="/static/img/ico/onr_logo.jpg">
    <img src="/static/img/ico/aro_logo.jpg">
    <img src="/static/img/ico/nvidia_logo.jpg">
  </div>
</div>
<br>
<div class="row">
  <div class="col-xs-12 sponsor">
    <img src="/static/img/ico/aara_logo.png">
    <img src="/static/img/ico/gfra_logo.jpg">
  </div>
</div>
<br>
<div class="row">
  <div class="col-xs-12 sponsor">
    <img src="/static/img/ico/paul_logo.jpg">
    <img src="/static/img/ico/ictas_logo.jpg">
  </div>
</div>
<br>
<br> -->
