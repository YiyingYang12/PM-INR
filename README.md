# PM-INR: Prior-Rich Multi-Modal Implicit Large-Scale Scene Neural Representation (AAAI24, oral)

*Yiying Yang*, *Fukun Yin*, *Wen liu*, *Jiayuan Fan†*, *Xin Chen*, *Gang Yu*, *Tao Chen*


*†Corresponding author*



Recent advancements in implicit neural representations have contributed to high-fidelity surface reconstruction and photo-realistic novel view synthesis. However, with the expansion of the scene scale, such as block or city level, existing methods will encounter challenges because traditional sampling cannot cope with the cubically growing sampling space. To alleviate the dependence on filling the sampling space, we explore using multi-modal priors to assist individual points to obtain more global semantic information and propose a prior-rich multi-modal implicit neural representation network, **PM-INR**, for the outdoor unbounded large-scale scene. The core of our method is multi-modal prior extraction and cross-modal prior fusion modules. The former encodes codebooks from different modality inputs and extracts valuable priors, while the latter fuses priors to maintain view consistency and preserve unique features among multi-modal priors. Finally, feature-rich cross-modal priors are injected into the sampling regions to allow each region to perceive global information without filling the sampling space. Extensive experiments have demonstrated the effectiveness and robustness of our method for outdoor unbounded large-scale scene novel view synthesis, which outperforms state-of-the-art methods in terms of PSNR, SSIM, and LPIPS.

![image](https://github.com/YiyingYang12/PM-INR/blob/main/Pipeline.png)
