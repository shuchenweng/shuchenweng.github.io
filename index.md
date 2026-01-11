---
layout: default
title: Shuchen Weng's Homepage
---

<style>
    /* 全局样式优化 */
    body {
        font-family: 'Lato', Verdana, Helvetica, sans-serif;
        font-size: 16px;
        line-height: 1.6;
        max-width: 900px;
        margin: 0 auto;
        padding: 20px;
        color: #333;
    }
    a { color: #0066cc; text-decoration: none; }
    a:hover { text-decoration: underline; }
    
    /* 头部布局 */
    .header-container {
        display: flex;
        align-items: center;
        margin-bottom: 40px;
        gap: 30px;
    }
    .profile-info { flex: 1; }
    .profile-img { width: 220px; flex-shrink: 0; }
    .profile-img img {
        width: 100%;
        border-radius: 50%; /* 圆形头像，如果不喜欢圆的可以删掉这行 */
        box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    
    /* 标题样式 */
    h1 { font-weight: 700; margin-bottom: 5px; }
    h2 { 
        border-bottom: 2px solid #f2f2f2; 
        padding-bottom: 10px; 
        margin-top: 40px; 
        font-size: 1.5em;
    }
    h3 { margin-top: 25px; font-size: 1.2em; color: #555; }
    
    /* 链接按钮样式 */
    .link-btn {
        display: inline-block;
        font-size: 14px;
        margin-right: 10px;
    }

    /* 论文列表样式 */
    .paper-item { margin-bottom: 15px; }
    .paper-title { font-weight: 600; color: #222; }
    .paper-author { color: #555; }
    .paper-venue { font-style: italic; color: #cc0000; font-weight: bold; }
    
    /* 移动端适配 */
    @media (max-width: 768px) {
        .header-container { flex-direction: column-reverse; text-align: center; }
        .profile-img { width: 180px; margin-bottom: 20px; }
    }
</style>

<div class="header-container">
    <div class="profile-info">
        <h1>Shuchen Weng (翁书琛)</h1>
        <p>
            <b>Technical Staff</b><br>
            Beijing Academy of Artificial Intelligence (BAAI)<br>
            Email: <code>shuchenweng [at] pku.edu.cn</code>
        </p>
        <p>
            I am currently a Technical Staff at <a href="https://www.baai.ac.cn/en">BAAI</a>. I received my Ph.D. degree from Peking University in 2024, advised by Prof. <a href="#">Boxin Shi</a>. Prior to that, I obtained my B.E. degree from Tianjin University.
        </p>
        <p class="links">
            [<a href="YOUR_GOOGLE_SCHOLAR_LINK">Google Scholar</a>] &nbsp;
            [<a href="YOUR_GITHUB_LINK">GitHub</a>] &nbsp;
            [<a href="YOUR_TWITTER_LINK">Twitter</a>]
        </p>
    </div>
    <div class="profile-img">
        <img src="photo.jpg" alt="Shuchen Weng">
    </div>
</div>

## 🔥 News
- **[2025.06]** Three papers accepted by **NeurIPS 2025**!
- **[2025.02]** One paper (VIRES) accepted by **CVPR 2025**.
- **[2024.07]** Joined BAAI as a Technical Staff.

## 🎓 Education
- **Peking University**, Beijing, China (Sep. 2019 - Jun. 2024)
  <br>Ph.D. in Computer Science (NELVT)
  <br>Advisor: Prof. Boxin Shi
- **Tianjin University**, Tianjin, China (Sep. 2015 - Jul. 2019)
  <br>B.E. in College of Intelligence and Computing

## 💼 Professional Experiences
- **Beijing Academy of Artificial Intelligence (BAAI)** | *Jul. 2024 - Present*
  <br>Technical Staff
- **Beijing Academy of Artificial Intelligence (BAAI)** | *Jan. 2023 - Jun. 2024*
  <br>Research Intern
- **Peng Cheng Lab** | *Feb. 2019 - Aug. 2019*
  <br>Research Intern
- **Tencent AI Lab** | *Aug. 2018 - Nov. 2018*
  <br>Research Intern

## 📝 Publications
<small>(* indicates equal contribution)</small>
<br>
<b>Summary:</b> TPAMI x 3, IJCV x 1, CVPR x 6, ECCV x 5, ICCV x 1, NeurIPS x 4, AAAI x 2.

### Video Generation & Editing

<div class="paper-item">
    <span class="paper-title">Audio-Sync Video Generation with Multi-Stream Temporal Control</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>*, Haojie Zheng*, Zheng Chang, Si Li, Boxin Shi, Xinlong Wang</span><br>
    <span class="paper-venue">NeurIPS 2025</span>
    <br>
    <a href="https://arxiv.org/pdf/2506.08003?">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">PanoWan: Lifting Diffusion Video Generation Models to 360 with Latitude/Longitude-aware Mechanisms</span><br>
    <span class="paper-author">Yifei Xia*, <b>Shuchen Weng</b>*, Siqi Yang, Jingqi Liu, Chengxuan Zhu, Minggui Teng, Zijian Jia, Han Jiang, Boxin Shi</span><br>
    <span class="paper-venue">NeurIPS 2025</span>
    <br>
    <a href="https://arxiv.org/pdf/2505.22016">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">VIRES: Video Instance Repainting with Sketch and Text Guidance</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>*, Haojie Zheng*, Peixuan Zhan, Yuchen Hong, Han Jiang, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">CVPR 2025</span>
    <br>
    <a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Weng_VIRES_Video_Instance_Repainting_via_Sketch_and_Text_Guided_Generation_CVPR_2025_paper.pdf">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">L-C4: Language-Based Video Colorization for Creative and Consistent Color</span><br>
    <span class="paper-author">Zheng Chang, <b>Shuchen Weng</b>, Huan Ouyang, Yu Li, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">Neurocomputing 2025</span>
    <br>
    <a href="https://arxiv.org/pdf/2410.04972">[PDF]</a>
</div>

### Image Semantic Editing

<div class="paper-item">
    <span class="paper-title">Towards Deeper Emotional Reflection: Crafting Affective Image Filters with Generative Priors</span><br>
    <span class="paper-author">Peixuan Zhang*, <b>Shuchen Weng</b>*, Jiajun Tang, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">TPAMI 2025</span>
    <br>
    [Coming Soon]
</div>

<div class="paper-item">
    <span class="paper-title">Affective Image Editing: Shaping Emotional Factors via Text Descriptions</span><br>
    <span class="paper-author">Peixuan Zhang*, <b>Shuchen Weng</b>*, Chengxuan Zhu, Binghao Tang, Zijian Jia, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">IJCV 2025</span>
    <br>
    <a href="https://arxiv.org/pdf/2505.18699?">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">PhyS-EdiT: Physics-aware Semantic Image Editing with Text Description</span><br>
    <span class="paper-author">Ziqi Cai, <b>Shuchen Weng</b>, Yifei Xia, Boxin Shi</span><br>
    <span class="paper-venue">CVPR 2025</span>
    <br>
    <a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Cai_PhyS-EdiT_Physics-aware_Semantic_Image_Editing_with_Text_Description_CVPR_2025_paper.pdf">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">Affective Image Filter: Reflecting Emotions from Text to Images</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>*, Peixuan Zhang*, Zheng Chang, Xinlong Wang, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">ICCV 2023</span>
    <br>
    <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Weng_Affective_Image_Filter_Reflecting_Emotions_from_Text_to_Images_ICCV_2023_paper.pdf">[PDF]</a>
    <a href="https://github.com/zpx0922/AIFormer">[Code]</a>
</div>

<div class="paper-item">
    <span class="paper-title">Instance Contour Adjustment via Structure-driven CNN</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>, Yi Wei, Ming-Ching Chang, Boxin Shi</span><br>
    <span class="paper-venue">ECCV 2022</span>
    <br>
    <a href="https://ci.idm.pku.edu.cn/Weng_ECCV22c.pdf">[PDF]</a>
</div>

### Low-level Vision

<div class="paper-item">
    <span class="paper-title">L-DiffER: Single image reflection removal with language-based diffusion model</span><br>
    <span class="paper-author">Yuchen Hong*, Haofeng Zhong*, <b>Shuchen Weng</b>, Jinxiu Liang, Boxin Shi</span><br>
    <span class="paper-venue">ECCV 2024</span>
    <br>
    <a href="https://assets.ctfassets.net/yreyglvi5sud/4uhN2PF7UyMGgiWQgCMSgi/41f4f9f46fbfa370b3ccd8fbcadbc2b3/2024______Hong_ECCV.pdf">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">Language-guided Image Reflection Separation</span><br>
    <span class="paper-author">Haofeng Zhong*, Yuchen Hong*, <b>Shuchen Weng</b>, Jinxiu Liang, Boxin Shi</span><br>
    <span class="paper-venue">CVPR 2024</span>
    <br>
    <a href="https://assets.ctfassets.net/yreyglvi5sud/1ptZmtvx71hLcIKH5mrxWQ/c571786893f745aa5b2f2298e55cd869/Zhong_CVPR24.pdf">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">L-CAD: Language-based Colorization with Any-level Descriptions</span><br>
    <span class="paper-author">Zheng Chang*, <b>Shuchen Weng</b>*, Peixuan Zhang, Yu Li, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">NeurIPS 2023 (Spotlight)</span>
    <br>
    <a href="https://arxiv.org/pdf/2305.15217.pdf">[PDF]</a>
    <a href="https://github.com/changzheng123/L-CAD">[Code]</a>
</div>

<div class="paper-item">
    <span class="paper-title">L-CoIns: Language-based Colorization with Instance Awareness</span><br>
    <span class="paper-author">Zheng Chang*, <b>Shuchen Weng</b>*, Peixuan Zhang, Yu Li, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">CVPR 2023</span>
    <br>
    <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Chang_L-CoIns_Language-Based_Colorization_With_Instance_Awareness_CVPR_2023_paper.pdf">[PDF]</a>
    <a href="https://github.com/changzheng123/L-CoIns">[Code]</a>
</div>

<div class="paper-item">
    <span class="paper-title">CT<sup>2</sup>: Colorization Transformer via Color Tokens</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>*, Jimeng Sun*, Yu Li, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">ECCV 2022 (Oral)</span>
    <br>
    <a href="https://ci.idm.pku.edu.cn/Weng_ECCV22b.pdf">[PDF]</a>
    <a href="https://github.com/shuchenweng/CT2">[Code]</a>
</div>

<div class="paper-item">
    <span class="paper-title">L-CoDer: Language-based Colorization with Color-object Decoupling Transformer</span><br>
    <span class="paper-author">Zheng Chang*, <b>Shuchen Weng</b>*, Yu Li, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">ECCV 2022</span>
    <br>
    <a href="https://ci.idm.pku.edu.cn/Weng_ECCV22g.pdf">[PDF]</a>
    <a href="https://github.com/changzheng123/L-CoDer">[Code]</a>
</div>

<div class="paper-item">
    <span class="paper-title">L-CoDe: Language-based Colorization using Color-object Decoupled Conditions</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>*, Hao Wu*, Zheng Chang, Jiajun Tang, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">AAAI 2022</span>
    <br>
    <a href="https://ci.idm.pku.edu.cn/Weng_AAAI22.pdf">[PDF]</a>
    <a href="https://github.com/changzheng123/L-CoDe">[Code]</a>
</div>

### Image Repainting

<div class="paper-item">
    <span class="paper-title">OpenCIR: Conditional Image Repainting with Open Condition Mixture</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>*, Xiaocheng Gong*, Haojie Zheng*, Xinlong Wang, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">TPAMI 2025</span>
    <br>
    <a href="https://ieeexplore.ieee.org/document/11122618">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">Conditional Image Repainting</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>, Boxin Shi</span><br>
    <span class="paper-venue">TPAMI 2023</span>
    <br>
    <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10313073">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">LuminAIRe: Illumination-Aware Conditional Image Repainting for Lighting-Realistic Generation</span><br>
    <span class="paper-author">Jiajun Tang, Haofeng Zhong, <b>Shuchen Weng</b>, Boxin Shi</span><br>
    <span class="paper-venue">NeurIPS 2023</span>
    <br>
    <a href="https://ci.idm.pku.edu.cn/Tang_NeurIPS23.pdf">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">UniCoRN: A Unified Conditional Image Repainting Network</span><br>
    <span class="paper-author">Jimeng Sun*, <b>Shuchen Weng</b>*, Zheng Chang, Si Li, Boxin Shi</span><br>
    <span class="paper-venue">CVPR 2022</span>
    <br>
    <a href="https://ci.idm.pku.edu.cn/Weng_CVPR22c.pdf">[PDF]</a>
    <a href="https://github.com/shuchenweng/UniCoRN">[Code]</a>
</div>

<div class="paper-item">
    <span class="paper-title">Conditional Image Repainting via Semantic Bridging and Piecewise Value Function</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>, Wenbo Li, Dawei Li, Hongxia Jin, Boxin Shi</span><br>
    <span class="paper-venue">ECCV 2020</span>
    <br>
    <a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540443.pdf">[PDF]</a>
    <a href="https://github.com/shuchenweng/TGC">[Code]</a>
</div>

<div class="paper-item">
    <span class="paper-title">MISC: Multi-condition Injection and Spatially-adaptive Compositing for Conditional Person Image Synthesis</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>*, Wenbo Li*, Dawei Li, Hongxia Jin, Boxin Shi</span><br>
    <span class="paper-venue">CVPR 2020</span>
    <br>
    <a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Weng_MISC_Multi-Condition_Injection_and_Spatially-Adaptive_Compositing_for_Conditional_Person_Image_CVPR_2020_paper.pdf">[PDF]</a>
    <a href="https://github.com/shuchenweng/MISC">[Code]</a>
</div>

### Others

<div class="paper-item">
    <span class="paper-title">Colorizing Monochromatic Radiance Fields</span><br>
    <span class="paper-author">Yean Cheng, Renjie Wan, <b>Shuchen Weng</b>, Chengxuan Zhu, Yakun Chang, Boxin Shi</span><br>
    <span class="paper-venue">AAAI 2024 (Oral)</span>
    <br>
    <a href="https://ci.idm.pku.edu.cn/Cheng_AAAI24.pdf">[PDF]</a>
</div>

<div class="paper-item">
    <span class="paper-title">Dual-stream CNN for Structured Time Series Classification</span><br>
    <span class="paper-author"><b>Shuchen Weng</b>*, Wenbo Li*, Yi Zhang, Siwei Lyu</span><br>
    <span class="paper-venue">ICASSP 2019</span>
    <br>
    <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8682410">[PDF]</a>
</div>


## 🏆 Awards
- **Huawei TopMinds Program (华为天才少年)**, 2024
- **Alibaba Taotian Group T-star Program (阿里淘天T-Star)**, 2024
- **National Scholarship for Graduate Student**, Peking University (Top 2%), 2023
- **Academic Innovation Award (Exceptional Award)**, Peking University (Top 1%), 2022
- **CCF Outstanding Undergraduate Student Award** (China's Annual Top 100), 2019
- **National Scholarship for Bachelor Student**, Tianjin University (Top 2%), 2017
