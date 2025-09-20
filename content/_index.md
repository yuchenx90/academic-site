---
title: "Home"
type: landing

sections:
  # 全站样式覆盖（放宽容器宽度）
  - block: markdown
    id: style
    content:
      title: ""
      text: |-
        <style>
          :root { --site-max: 1100px; }
          /* 放宽常见的容器类：hb-section、container、prose、max-w-*  */
          .hb-section .container,
          .container,
          .prose,
          .max-w-prose,
          .max-w-3xl,
          .max-w-4xl {
            max-width: min(var(--site-max), 92vw) !important;
          }
        </style>

        
sections:
  # 🟣 Bio 区块
  - block: markdown
    id: bio
    content:
      title: ""   # 不显示“Biography”字样
      text: |-
        <!-- Full-bleed wrapper：拉满到 100vw，再在里面设最大宽度 -->
        <div style="width:100vw; position:relative; left:50%; right:50%; margin-left:-50vw; margin-right:-50vw;">
          <div style="margin:0 auto; width:min(1100px,92vw);">
            <div style="display:flex; gap:28px; align-items:flex-start; flex-wrap:wrap;">
              <img src="img/yuchen.jpg" alt="Yuchen Xu" style="width:140px; border-radius:50%; flex:0 0 auto;">
              <div style="flex:1; min-width:280px;">
                Dr. Yuchen Xu is an Assistant Professor (Senior Lecturer) in Finance at UNSW Business School. Previously, she was an Assistant Professor at Peking University HSBC Business School. Dr. Xu completed her undergraduate and postgraduate studies in Paris, where she received dual master's degrees in Financial Engineering (2014) and Economic Psychology (2015). After that, she obtained her Ph.D in Finance from the University of Hong Kong (2020). Her research interests span across quantitative financial history and empirical corporate finance. She places special emphasis on identifying the foundational factors that influence the enduring development of finance, in particular at its genesis. Her findings have been published in prestigious international journals, including the <em>Journal of Finance</em>, the <em>Journal of Financial Economics</em>, and <em>Management Science</em> among others.
              </div>
            </div>
          </div>
        </div>
        
  # 🟣 Publications 区块
  - block: markdown
    id: publications
    content:
      title: "Publications"
      text: |-
        - Paper 1. *Journal of Finance*, 2023.  
        - Paper 2. *Journal of Financial Economics*, 2022.  
        - Paper 3. *Management Science*, 2021.  

  # 🟣 Working Papers 区块
  - block: markdown
    id: working-papers
    content:
      title: "Working Papers"
      text: |-
        - Title 1. Under review at [journal].  
        - Title 2. Draft in progress.  

  # 🟣 Funds & Awards 区块
  - block: markdown
    id: funds-awards
    content:
      title: "Funds & Awards"
      text: |-
        - 2024. Awarded XYZ Research Grant.  
        - 2023. Received Best Paper Prize at ABC Conference.  

  # 🟣 Teaching 区块
  - block: markdown
    id: teaching
    content:
      title: "Teaching"
      text: |-
        - UNSW FINS5513: Corporate Finance.  
        - UNSW FINS5566: Empirical Asset Pricing.  
        - PKU HSBC: Financial Markets (2019–2023).  
---
