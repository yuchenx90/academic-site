---
title: "Home"
type: landing

sections:
  - block: markdown
    id: style
    content:
      title: ""
      text: |
        <style>
          /* Load Inter and widen the layout */
          @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
          :root { --site-max: 1100px; }
          .hb-section .container,
          .container,
          .prose,
          .max-w-prose,
          .max-w-3xl,
          .max-w-4xl {
            max-width: min(var(--site-max), 92vw) !important;
          }
          html, body {
            font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            color:#111;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
          }
          .prose { color:#111 !important; }
          .prose h1, .prose h2, .prose h3 { color:#111 !important; font-weight:700; }
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
                 style="max-width:320px; width:100%; height:auto; border-radius:8px; display:block;">
            <figcaption style="margin-top:10px; line-height:1.35;">
              <div style="font-size:1.25rem; font-weight:700; color:#334155;">Yuchen XU</div>
              <div style="font-size:0.95rem; color:#555;">Assistant Professor in Finance</div>
              <div style="font-size:0.95rem; color:#555;">UNSW Business School</div>
            </figcaption>
          </figure>
          <div style="flex:1; min-width:280px;">
            Dr. Yuchen Xu is an Assistant Professor (Senior Lecturer) in Finance at UNSW Business School. Previously, she was an Assistant Professor at Peking University HSBC Business School. Dr. Xu completed her undergraduate and postgraduate studies in Paris, where she received dual master's degrees in Financial Engineering (2014) and Economic Psychology (2015). After that, she obtained her Ph.D in Finance from the University of Hong Kong (2020). Her research interests span across quantitative financial history and empirical corporate finance. She places special emphasis on identifying the foundational factors that influence the enduring development of finance, in particular at its genesis. Her findings have been published in prestigious international journals, including the <strong><em>Journal of Finance</em></strong>, the <strong><em>Journal of Financial Economics</em></strong>, and <strong><em>Management Science</em></strong> among others.
          <div style="display:flex; gap:24px; flex-wrap:wrap; align-items:center; margin-top:16px;">
            <span style="display:inline-flex; align-items:center; gap:6px;">
              <span aria-hidden="true" style="display:inline-block; vertical-align:-0.15em;">
                <svg width="18" height="18" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
                  <path d="M12 3v10.586l3.293-3.293 1.414 1.414L12 17.414l-4.707-4.707 1.414-1.414L11 13.586V3h2zM5 19h14v2H5z"/>
                </svg>
              </span>
              <a href="cv/CV_yuchen.pdf" target="_blank" rel="noopener"
                 style="color:#555; text-decoration-color:#bbb;">Download my CV</a>
            </span>
            <a href="https://www.unsw.edu.au/staff/yuchen-xu" target="_blank" rel="noopener"
               style="display:inline-flex; align-items:center; gap:6px; color:#555; text-decoration-color:#bbb;">
              <span aria-hidden="true" style="display:inline-block; vertical-align:-0.15em;">
                <svg width="18" height="18" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
                  <path d="M12 2a10 10 0 1 0 0 20A10 10 0 0 0 12 2zm7.93 9h-3.12a15.7 15.7 0 0 0-1.1-4.11A8.02 8.02 0 0 1 19.93 11zM12 4a13.7 13.7 0 0 1 1.7 5H10.3A13.7 13.7 0 0 1 12 4zM8.29 6.89A15.7 15.7 0 0 0 7.19 11H4.07a8.02 8.02 0 0 1 4.22-4.11zM4.07 13h3.12c.24 1.43.62 2.83 1.1 4.11A8.02 8.02 0 0 1 4.07 13zM12 20a13.7 13.7 0 0 1-1.7-5h3.4A13.7 13.7 0 0 1 12 20zm3.71-2.89c.49-1.28.86-2.68 1.1-4.11h3.12a8.02 8.02 0 0 1-4.22 4.11z"/>
                </svg>
              </span>
              <span>UNSW staff profile</span>
            </a>
          </div>
          <!-- Sections -->
            <h3 style="margin-top:22px; font-weight:700;">Education</h3>
            <ul>
              <li>Ph.D. in Finance, The University of Hong Kong (2020)</li>
              <li>MSc in Financial Engineering, Paris (2014)</li>
              <li>MA in Economic Psychology, Paris (2015)</li>
            </ul>
          
            <h3 style="margin-top:16px; font-weight:700;">Languages</h3>
            <ul>
              <li>English</li>
              <li>Mandarin Chinese</li>
              <li>French</li>
            </ul>
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
