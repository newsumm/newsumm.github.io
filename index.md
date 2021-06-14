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
<!--Keynote Spearkers-->
<h2 class="blackpar_title" id="keynotes">Keynote Speakers</h2>
<div class="row">
	<div class="card column">
	  <img src="/images/bengio.jpg" alt="Yoshua Bengio" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Yoshua Bengio</b>
			<br>
			MILA
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/img_avatar.png" alt="Xin Jiang" style="width:100%; border-radius:50%;">
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
	  <img src="/images/img_avatar.png" alt="someone" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Someone</b>
			<br>
			Amazon
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/img_avatar.png" alt="someone" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Someone</b>
			<br>
			Google
		</h4>
		</center>
	  </div>
	</div>
</div>
<div class="row">
	<div class="card column">
	  <img src="/images/img_avatar.png" alt="someone" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Someone</b>
			<br>
			Microsoft
		</h4>
		</center>
	  </div>
	</div>
	<div class="card column">
	  <img src="/images/img_avatar.png" alt="someone" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Someone</b>
			<br>
			Darwin AI
		</h4>
		</center>
	  </div>
	</div>
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
	  <img src="/images/tiago_falk.png" alt="Tiago Falk" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Tiago Falk</b>
			<br>
			INRS
		</h4>
		</center>
	  </div>
	</div>
</div>
<div class="row">
	<div class="card column" style="margin-left:25%;">
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
	  <img src="/images/img_avatar.png" alt="someone" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Prof.<br>Someone</b>
			<br>
			Thomson Reuiters
		</h4>
		</center>
	  </div>
	</div>	
</div>

<!-- Schedule -->
<h2 class="blackpar_title" id="Schedule">Schedule</h2>
<div id="cal">
	<div class="month">      
	  <ul class="uls">
		<!--<li class="prev">&#10094;</li>
		<li class="next">&#10095;</li>-->
		<li>
		  June<br>
		  <span style="font-size:18px">2021</span>
		</li>
	  </ul>
	</div>

	<ul class="weekdays uls">
	  <li>Mo</li>
	  <li>Tu</li>
	  <li>We</li>
	  <li>Th</li>
	  <li>Fr</li>
	  <li>Sa</li>
	  <li>Su</li>
	</ul>

	<ul class="days uls">
	  <li></li>
	  <li>1</li>
	  <li>2</li>
	  <li>3</li>
	  <li>4</li>
	  <li>5</li>
	  <li>6</li>
	  <li>7</li>
	  <li>8</li>
	  <li>9</li>
	  <li><span class="task1">10</span></li>
	  <li>11</li>
	  <li>12</li>
	  <li>13</li>
	  <li>14</li>
	  <li>15</li>
	  <li>16</li>
	  <li>17</li>
	  <li>18</li>
	  <li>19</li>
	  <li><span class="task2">20</span></li>
	  <li>21</li>
	  <li>22</li>
	  <li>23</li>
	  <li>24</li>
	  <li>25</li>
	  <li>26</li>
	  <li>27</li>
	  <li>28</li>
	  <li>29</li>
	  <li>30</li>
	</ul>
</div>
<br>
<div><div class='box' id="task1"></div><span class="task_name">task 1 bla bla bla</span></div>
<br>
<div><div class='box' id="task2"></div><span class="task_name">task 2 bla bla bla</span></div>
<br><br>

<!-- Organizers -->
<h2 class="blackpar_title" id="Organizers">Organizers</h2>
<div class="row">
	<div class="card column">
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
	  <img src="/images/Mehdi_Rezagholizadeh.jpg" alt="Mehdi Rezagholizadeh" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Mehdi Rezagholizadeh</b>
			<br>
			Huawei
		</h4>
		</center>
	  </div>
	</div>
</div>
<div class="row">
	<div class="card column" style="margin-left:13%;">
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
	<div class="card column">
	  <img src="/images/peyman_passban.jpg" alt="Peyman Passban" style="width:100%; border-radius:50%;">
	  <div class="container">
		<center>
		<h4>
			<b>Peyman Passban</b>
			<br>
			Amazon
		</h4>
		</center>
	  </div>
	</div>
</div>
