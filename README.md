<p align="center">
  <h3 align="center">Generating Synthetic Medical Images with limited data using Auxiliary Classifier Generative Adversarial Network: A Study on Thyroid Ultrasound Images</h3></p>
<br><br>
  <p align="center">Hamidreza Atri <sub>a</sub>, Mahdieh Shadi<sub>b</sub>, Mahdi Sargolzaei <sub>c</sub></p>
 <p align="center"><ol type="a">  
<li>Department of Computer Science, Azad University of Mashhad, Mashhad, Iran, Po. Box 91735-413, atri.hamidreza@gmail.com.</li>
<li>Department of Computer Science, Azad University of Mashhad, Mashhad, Iran, Po. Box 91735-413, mahdieh.shadi@gmail.com.</li>
<li>Department of Medical Informatics, Faculty of Medicine, Mashhad University of Medical Sciences, Mashhad, Iran, Po. Box 13131 – 99137, Sargolzaeim971@mums.ac.ir.</li>
</ol>
</p>
<br>

<p><b>Abstract</b></p>

<p><b>Background and objective:</b>  The availability of labeled data is crucial for training deep neural networks. However, in some cases, the available data is limited or unlabeled, which poses a significant obstacle in developing accurate models. Various approaches exist to address this issue, such as Image Augmentation, Transfer Learning, and GANs. However, these approaches often require a significant amount of training data or may not generate desired results. In this article, we present a novel method for generating synthetic images from very limited data using the ACGAN.</p>
<p><b>Methods:</b> We conducted experiments on a real dataset consisting of 198 ultrasound images of calcified and cystic thyroid gland nodules. We explored and improved different architectures and techniques in the Axillary Classifier Generative Adversarial Network (ACGAN) to generate high-quality synthetic images.  To evaluate the generated images, we used the Fréchet Inception Distance (FID) test and human observation. Additionally, we developed an image blending method to generate larger images that simulate the output of an ultrasound device. To validate the accuracy of the merged images, a specialist doctor reviewed and confirmed their authenticity.</p>
<p><b>Results:</b> The modified ACGAN architecture successfully generated new synthetic images from limited data. The output images were assessed based on the image progress ratio with the FID test and human observation. Moreover, the Image blending method was successful in producing larger output images that mimic the nature of the ultrasound device output images.  The final merged images were validated by a specialist doctor who confirmed their accuracy.</p>
<p><b>Conclusions:</b>  Our method has significant implications for medical imaging, as it enables the generation of synthetic labeled data for training deep learning models, leading to better diagnostic accuracy and improved patient outcomes. This study provides a proof-of-concept for generating synthetic medical images from limited labeled data and can inspire future research in this area.</p>
