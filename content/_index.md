---
title: "Home"
type: landing

sections:
  # 全站样式（第一个 section）
  - block: markdown
    id: style
    content:
      title: ""
      text: |-
        <style>
          /* 放宽主题默认容器宽度到 ~1100px，并在小屏保留两侧留白 */
          :root{ --site-max:1100px; }
          .hb-section .container,
          .container,
          .prose,
          .max-w-prose,
          .max-w-3xl,
          .max-w-4xl {
            max-width: min(var(--site-max), 92vw) !important;
          }
        </style>

  # Bio
  - block: markdown
    id: bio
    content:
      title: ""   # 不显示“Biography”标题
      text: |-
        <div style="display:flex; gap:28px; align-items:flex-start; flex-wrap:wrap;">
          <figure style="margin:0; text-align:center; flex:0 0 auto;">
            <img src="img/yuchen.jpg" alt="Yuchen Xu"
                 style="width:220px; height:220px; object-fit:cover; border-radius:8px; display:block;">
            <figcaption style="margin-top:8px; font-weight:600;">Yuchen XU</figcaption>
          </figure>
          <div style="flex:1; min-width:280px;">
            Dr. Yuchen Xu is an Assistant Professor (Senior Lecturer) in Finance at UNSW Business School. Previously, she was an Assistant Professor at Peking University HSBC Business School. Dr. Xu completed her undergraduate and postgraduate studies in Paris, where she received dual master's degrees in Financial Engineering (2014) and Economic Psychology (2015). After that, she obtained her Ph.D in Finance from the University of Hong Kong (2020). Her research interests span across quantitative financial history and empirical corporate finance. She places special emphasis on identifying the foundational factors that influence the enduring development of finance, in particular at its genesis. Her findings have been published in prestigious international journals, including the <em>Journal of Finance</em>, the <em>Journal of Financial Economics</em>, and <em>Management Science</em> among others.
          </div>
        </div>

  # Publications
  - block: markdown
    id: publications
    content:
      title: "Publications"
      text: |-
        - Paper 1. <em>Journal of Finance</em>, 2023.  
        - Paper 2. <em>Journal of Financial Economics</em>, 2022.  
        - Paper 3. <em>Management Science</em>, 2021.  

  # Working Papers
  - block: markdown
    id: working-papers
    content:
      title: "Working Papers"
      text: |-
        - Title 1. Under review at [journal].  
        - Title 2. Draft in progress.  

  # Funds & Awards
  - block: markdown
    id: funds-awards
    content:
      title: "Funds & Awards"
      text: |-
        - 2024. Awarded XYZ Research Grant.  
        - 2023. Received Best Paper Prize at ABC Conference.  

  # Teaching
  - block: markdown
    id: teaching
    content:
      title: "Teaching"
      text: |-
        - UNSW FINS5513: Corporate Finance.  
        - UNSW FINS5566: Empirical Asset Pricing.  
        - PKU HSBC: Financial Markets (2019–2023).  
---
