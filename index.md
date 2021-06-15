---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---

<!-- <img src="/images/deep.jpg"> -->
<h2 class="blackpar_title">Efficient NLP and Speech Models - Training and Inference</h2>
<p>

Despite the great success of deep neural networks in Natural Language Processing (NLP), including speech-related tasks, over-parameterization can make it very difficult to deploy such models on edge devices due to their limited computational power, memory, and storage available. To overcome that, a new research field, namely Tiny Machine Learning (TML), arises intending to enable the design and development of Machine Learning (ML) models meant to be deployed on Embedded Systems and Intent-of-Things. For instance, model compression techniques such as quantization, pruning, layer decomposition, and knowledge distillation (KD) aim at reducing the number of parameters of these models, thus optimizing memory requirements and efficiency.
<br><br>
Often, these models require pre-training on a huge amount of labeled and unlabeled data, which can be an expensive process. Even a small modification to the model requires the user to redo the expensive pre-training process. Furthermore, usually, the final hardware host is not taken into account in the design and training of the models. Another aspect is multimodal systems which can learn language and speech modalities at the same time. Since the emergence of pre-trained language models which led to a great breakthrough in the NLP domain, increasing the size of these models has become a mainstream approach for improving the performance of these models.


<!--	
The workshop will take place on <span class="blackhighlighted">DATE, 2021</span>. 
Due to the pandemic, the workshop will be <span class="blackhighlighted">VIRTUAL</span>. More details will be provided soon. 

Note that to attend the event, a registration on the ICLR website is required. All workshop events (except Poster session and open discussion) can be followed using the ICLR link or use the zoom link by clicking on “join zoom” on the ICLR link. For the Poster session participants should une the Gather.town link. Note that papers id can be found on Accepter papers section.
</p>
<br>
-->
<br><br>
<h2 class="blackpar_title" id="Overview">Overview</h2>
<p>
Given the increasing interest in TML, the development of models that takes into consideration hardware and computation constraints allowing the reduction of computational load and memory demand are mandatory. This workshop focuses particularly on the efficiency of NLP and Speech models.
</p>
<br><br>

<!-- Call for Papers -->
<h2 class="blackpar_title" id="Call for Papers">Call for Papers</h2>

<br><br>
<!--Keynote Spearkers-->
<h2 class="blackpar_title" id="keynotes">Keynote Speakers</h2>
<div class="row">
	<div class="card column">
	  <img src="/images/boxing.jpg" alt="Boxing Chen" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>X.<br>Boxing Chen</b>
			<br>
			Alibaba
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/xinjiang.jpg" alt="Xin Jiang" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Dr.<br>Xin Jiang</b>
			<br>
			Huawei
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/norouzi.jpg" alt="Mohammad Norouzi" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Dr.<br>Mohammad Norouzi</b>
			<br>
			Google Brain
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/zettlemoyer.jpg" alt="Luke Zettlemoyer" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>X.<br>Luke Zettlemoyer</b>
			<br>
			University of Washington and Facebook
		</h4>
		</center>
	  </div>
	</div>
</div>
<div class="row">
	<div class="card column">
	  <img src="/images/sameer_singh.jpg" alt="Saneer Singh" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Saneer Singh</b>
			<br>
			University of California
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/xu_sun.jpg" alt="Xu Sun" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Dr.<br>Xu Sun</b>
			<br>
			Peking University
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/kevin.jpg" alt="Kevin Duh" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Kevin Duh</b>
			<br>
			Johns Hopkins University
		</h4>
		</center>
	  </div>
	</div>	
	<div class="card column">
	  <img src="/images/danqi_2019.jpg" alt="Danqi Chen" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>X.<br>Danqi Chen</b>
			<br>
			Assistant professor, Princeton University
		</h4>
		</center>
	  </div>
	</div>	
</div>

<br> <br>
<!-- Organizers -->
<h2 class="blackpar_title" id="Organizers">Organizers</h2>
<div class="row">
	<div class="card column">
	  <img src="/images/Mehdi_Rezagholizadeh.jpg" alt="Mehdi Rezagholizadeh" style="width:100%; border-radius:50%;">
	  <div class="container" >
		<center>
		<h4>
			<b>Mehdi Rezagholizadeh</b>
			<br>
			Huawei
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/lili_mou.jpg" alt="Lili Mou" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Lili Mou</b>
			<br>
			U Alberta
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column" >
	  <img src="/images/pascal_poupart.jpg" alt="Pascal Poupart" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Pascal Poupart</b>
			<br>
			U Waterloo
		</h4>
		</center>
	  </div>
	</div>
</div>
<div class="row">
	<div class="card column">
	  <img src="/images/ali_ghodsi.jpg" alt="Ali Ghodsi" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Ali Ghodsi</b>
			<br>
			U Waterloo
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/qun_liu.png" alt="Qun Liu" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Qun Liu</b>
			<br>
			Dublin University, Huawei
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/wei_xu.png" alt="Wei Xu" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Wei Xu</b>
			<br>
			Georgia Tech
		</h4>
		</center>
	  </div>
	</div>
</div>

<br><br>
<!-- Technical Committee -->
<h2 class="blackpar_title" id="Technical Committee">Technical Committee</h2>

