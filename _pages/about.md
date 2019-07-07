---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

### About
* I'm a Research Scientist at [Criteo AI Lab](https://ailab.criteo.com/), where I work on machine learning models for recommendation.
* I have my PhD degree from Skoltech. Broadly I worked on the intersection of machine learning and graph theory. 

<h1 style="font-size: 36px">Selected publications</h1>
<!-- <> -->
<div class="row publications">
    <div class="col-sm-5 vcenter marginbottom">
        <img class="img-responsive pub-image" src="/assets/about/avatars.jpg" alt=""/>
    </div>
    <div class="col-sm-7 vcenter" style="margin-right: -4px; text-align: justify;">
        <p class="title">Textured Neural Avatars</p>
        <p class="authors">A Shysheya, E Zakharov, R Bashirov, I Pasechnik, E Burkov, D Ulyanov, Y Malkov, K Iskakov, A Aliev, A Ivakhnenko, A Vakhitov, V Lempitsky</p>
        <p class="conf">CVPR 2019</p>
        <p class="description">
            We present a system for learning full-body neural avatars, i.e. deep networks that produce full-body renderings of a person for varying body pose and camera position. Our system estimates an explicit two-dimensional texture map of the model surface and uses a fully-convolutional network to directly map the configuration of body feature points w.r.t. the camera to the 2D texture coordinates of individual pixels in the image frame.
        </p>
        <div class="links">
            <a href="https://arxiv.org/abs/1905.08776">Paper</a>
            <a href="https://saic-violet.github.io/texturedavatar/" style="font-weight: bold;">Project page</a>
            <a href="https://www.youtube.com/watch?v=3rrnUX8wWZ8" style="font-weight: bold;">Demo video</a>
        </div>
    </div>
</div>
<div class="row publications border">
    <div class="col-sm-5 vcenter marginbottom">
        <img class="img-responsive pub-image" src="/assets/about/perceptual_gan.png" alt=""/>
    </div>
    <div class="col-sm-7 vcenter" style="margin-right: -4px; text-align: justify;">
        <p class="title">Image Manipulation with Perceptual Discriminators</p>
        <p class="authors">Diana Sungatullina, Egor Zakharov, Dmitry Ulyanov, Victor Lempitsky</p>
        <p class="conf">ECCV 2018</p>
        <p class="description">
            Perceptual losses and losses based on adversarial discriminators are the two main classes of learning objectives behind these advances. In this work, we show how
            these two ideas can be combined: we use adversarial learning on top of perceptual features and improve SOtA in image translation.  
        </p>
        <div class="links">
            <a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Diana_Sungatullina_Image_Manipulation_with_ECCV_2018_paper.pdf">Paper</a>
            <a href="https://egorzakharov.github.io/perceptual_gan" style="font-weight: bold;">Project page</a>
            <a href="https://github.com/egorzakharov/PerceptualGAN">Code</a>
            <a href="https://box.skoltech.ru/index.php/s/J0pdkyYgxpMItWQ">Poster</a>
        </div>
    </div>
</div>
<div class="row publications border">
    <div class="col-sm-5 vcenter marginbottom">
    	<img class="img-responsive pub-image" src="https://raw.githubusercontent.com/DmitryUlyanov/deep-image-prior/master/data/teaser_compiled.jpg" alt=""/>
    </div>
    <div class="col-sm-7 vcenter" style="margin-right: -4px; text-align: justify;">
		<p class="title">Deep Image Prior</p>
		<p class="authors">Dmitry Ulyanov, Andrea Vedaldi, Victor Lempitsky</p>
		<p class="conf">CVPR 2018</p>
		<p class="description">
			In this paper we show that a randomly-initialized neural network can be used as a handcrafted prior with excellent results in standard inverse problems such as denoising, super-resolution, and inpainting.
		</p>
        <div class="links">
    		<a href="https://sites.skoltech.ru/app/data/uploads/sites/25/2018/04/deep_image_prior.pdf">Paper</a>
    		<a href="/deep_image_prior" style="font-weight: bold;">Project page</a>
    		<a href="https://github.com/DmitryUlyanov/deep-image-prior">Code</a>
            <a href="https://box.skoltech.ru/index.php/s/INaUzvTWLak3h7Q">Paper (journal ver.)</a>
            <a href="https://www.youtube.com/watch?v=-g1NsTuP1_I">Video</a>
            <a href="https://drive.google.com/file/d/1fA5l1wWB0s17CIIgaXe9Gydxxgs5n98i/view?usp=sharing">Slides</a>
            <a href="https://drive.google.com/file/d/1dnpOnmeZF5qg5E-Bi4yMWOZDM_qmYyJA/view?usp=sharing">Poster</a>
            <a href="http://dblp.uni-trier.de/rec/bibtex/journals/corr/abs-1711-10925">BibTeX</a>
        </div>
	</div>
</div>
<div class="row publications border">
    <div class="col col-sm-5 vcenter marginbottom">
        <img class="img-responsive pub-image" src="/assets/about/age22.png" alt=""/>
    </div>
    <div class="col col-sm-7 vcenter" style="margin-right: -4px; text-align: justify;">
        <p class="title">It Takes (Only) Two: Adversarial Generator-Encoder Networks</p>
        <p class="authors">Dmitry Ulyanov, Andrea Vedaldi, Victor Lempitsky</p>
        <p class="conf1"><u>AAAI 2018</u> <b>(oral)</b></p>
        <p class="description">
        We present a new autoencoder-type architecture, that is trainable in an unsupervised mode, sustains both generation and inference, and has the quality of conditional and  unconditional samples boosted by adversarial learning.</p>
        <div class="links">
            <a href="http://sites.skoltech.ru/app/data/uploads/sites/25/2017/06/AGE.pdf">Paper</a>
            <a href="https://github.com/DmitryUlyanov/AGE">Code</a>
            <a href="https://drive.google.com/file/d/1rHcE_H9A0rRmziEcnzsIA_1rdBhHQFsn/view?usp=sharing">Slides</a>
            <a href="http://dblp.uni-trier.de/rec/bibtex/conf/aaai/UlyanovVL18">BibTeX</a>
        </div>
    </div>
</div>
<a name="texture_nets_v2"></a>
<div class="row publications border" >
    <div class="col col-sm-5 vcenter marginbottom">
        <img class="img-responsive pub-image" src="/assets/about/karya.png" alt=""/>
    </div>
    <div class="col col-sm-7 vcenter" style="margin-right: -4px; text-align: justify;" >
        <p class="title">Improved Texture Networks: Maximizing Quality and Diversity in Feed-forward Stylization and Texture Synthesis</p>
        <p class="authors">Dmitry Ulyanov, Andrea Vedaldi, Victor Lempitsky</p>
        <p class="conf">CVPR 2017</p>
        <p class="description">
        We introduce <i>Instance Normalization</i> for a better stylization and derive entropy loss which improves samples diversity for both texture synthesis and stylization.
        </p>
        <div class="links">
            <a href="http://sites.skoltech.ru/app/data/uploads/sites/25/2017/01/texture_nets_v2.pdf">Paper</a>
            <a href="https://github.com/DmitryUlyanov/texture_nets">Code</a>
            <a href="http://sites.skoltech.ru/app/data/uploads/sites/25/2017/01/texture_nets_v2_sup.pdf">Supplementary</a>
            <a href="https://drive.google.com/file/d/0B_-hq6gL70bUYWZaYV96elp3dzQ/view?usp=sharing">Poster</a>
            <a href="http://dblp.uni-trier.de/rec/bibtex1/conf/cvpr/UlyanovVL17">BibTeX</a>   
        </div>
    </div>
</div> 
<div class="row publications border">
    <div class="col col-sm-5 vcenter marginbottom">
        <img class="img-responsive pub-image" src="/assets/about/texture_nets_img.png" alt=""/>
    </div>
    <div class="col col-sm-7 vcenter" style="margin-right: -4px; text-align: justify;">
        <p class="title">Texture Networks: Feed-forward Synthesis of Textures and Stylized Images</p>
        <p class="authors">Dmitry Ulyanov, Vadim Lebedev, Andrea Vedaldi, Victor Lempitsky</p>
        <p class="conf">ICML 2016</p>
                        <p class="description">
        We speed up texture synthesis and famous neural style transfer of Gatys <i>et al.</i> by 500 times. The method was used by such stylization apps like <a href="http://prisma-ai.com/">Prisma</a> and <a href="http://vinci.camera/">Vinci</a>.
        </p>
        <div class="links">
            <a href="http://jmlr.org/proceedings/papers/v48/ulyanov16.pdf">Paper</a>
            <a href="https://github.com/DmitryUlyanov/texture_nets">Code</a>
            <a href="http://jmlr.org/proceedings/papers/v48/ulyanov16-supp.pdf">Supplementary</a>
            <a href="https://drive.google.com/file/d/0B_-hq6gL70bUdDBCUHVJWVlWWjQ/view?usp=sharing">Slides</a>
            <a href="https://drive.google.com/file/d/0B_-hq6gL70bURnZFcnRNemppWW8/view?usp=sharing">Poster</a>
            <a href="http://dblp.uni-trier.de/rec/bibtex0/conf/icml/UlyanovLVL16">BibTeX</a>
        </div>
    </div> 
</div>
