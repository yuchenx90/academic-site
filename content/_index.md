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
              <div style="font-size:0.95rem; color:#555;">
                Email:
                <a href="mailto:yuchen.xu@unsw.edu.au"
                   style="color:#555; text-decoration-color:#bbb;">
                   yuchen.xu@unsw.edu.au
                </a>
              </div>
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
                    <path d="M14 3h7v7h-2V6.414L9.707 15.707l-1.414-1.414L17.586 5H14V3z"/>
                    <path d="M19 19H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h7v2H5v12h12v-7h2v7a2 2 0 0 1-2 2z"/>
                  </svg>
                </span>
              <span>UNSW staff profile</span>
            </a>
          </div>
          <!-- 两栏：Education | Languages（并排，标题更小） -->
          <div style="display:flex; gap:36px; flex-wrap:wrap; align-items:flex-start; margin-top:18px;">
            <!-- Education -->
            <div style="flex:1; min-width:280px;">
              <h3 style="margin:0 0 8px; font-weight:700; font-size:1rem; line-height:1.5; display:flex; align-items:center; gap:8px;">
                <span aria-hidden="true" style="line-height:1;">
                  <!-- mortarboard（标题前的小帽子） -->
                  <svg width="18" height="18" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 3l10 5-10 5L2 8l10-5z"/><path d="M19 11v3c0 3.3-3.58 6-7 6s-7-2.7-7-6v-3l7 3 7-3z"/>
                  </svg>
                </span>
                Education
              </h3>
              <ul style="margin:0; padding-left:0; list-style:none;">
                <!-- 每条前也有帽子 -->
                <li style="display:flex; gap:10px; align-items:flex-start; margin:0 0 10px;">
                  <span aria-hidden="true" style="line-height:1;">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
                      <path d="M12 3l10 5-10 5L2 8l10-5z"/><path d="M19 11v3c0 3.3-3.58 6-7 6s-7-2.7-7-6v-3l7 3 7-3z"/>
                    </svg>
                  </span>
                  <span>
                    <strong>Ph.D. in Finance</strong>, 2020<br>
                    <span style="color:#555;">The University of Hong Kong</span>
                  </span>
                </li>
                <li style="display:flex; gap:10px; align-items:flex-start; margin:0 0 10px;">
                  <span aria-hidden="true" style="line-height:1;">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
                      <path d="M12 3l10 5-10 5L2 8l10-5z"/><path d="M19 11v3c0 3.3-3.58 6-7 6s-7-2.7-7-6v-3l7 3 7-3z"/>
                    </svg>
                  </span>
                  <span>
                    <strong>MPhil in Economic Psychology</strong>, 2015<br>
                    <span style="color:#555;">Paris-Sorbonne & Paris Descartes (joint)</span>
                  </span>
                </li>
                <li style="display:flex; gap:10px; align-items:flex-start; margin:0 0 10px;">
                  <span aria-hidden="true" style="line-height:1;">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
                      <path d="M12 3l10 5-10 5L2 8l10-5z"/><path d="M19 11v3c0 3.3-3.58 6-7 6s-7-2.7-7-6v-3l7 3 7-3z"/>
                    </svg>
                  </span>
                  <span>
                    <strong>MSc in Financial Engineering</strong>, 2015<br>
                    <span style="color:#555;">Université Paris-Dauphine</span>
                  </span>
                </li>
                <li style="display:flex; gap:10px; align-items:flex-start; margin:0;">
                  <span aria-hidden="true" style="line-height:1;">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
                      <path d="M12 3l10 5-10 5L2 8l10-5z"/><path d="M19 11v3c0 3.3-3.58 6-7 6s-7-2.7-7-6v-3l7 3 7-3z"/>
                    </svg>
                  </span>
                  <span>
                    <strong>BSc in Applied Economics</strong>, 2012<br>
                    <span style="color:#555;">Université Paris-Dauphine</span>
                  </span>
                </li>
              </ul>
            </div>
            <!-- Languages -->
            <div style="flex:1; min-width:280px;">
              <h3 style="margin:0 0 8px; font-weight:700; font-size:1rem; line-height:1.5; display:flex; align-items:center; gap:8px;">
                <span aria-hidden="true" style="line-height:1;">
                  <!-- 语言图标（地球） -->
                  <svg width="18" height="18" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 2a10 10 0 100 20 10 10 0 000-20zm7.9 9h-3.1a15.8 15.8 0 01-1.1-4.1A8 8 0 0119.9 11zM12 4a13.6 13.6 0 011.7 5h-3.4A13.6 13.6 0 0112 4zM8.3 6.9A15.7 15.7 0 007.2 11H4.1a8 8 0 014.2-4.1zM4.1 13h3.1c.2 1.4.6 2.8 1.1 4.1A8 8 0 014.1 13zM12 20a13.6 13.6 0 01-1.7-5h3.4A13.6 13.6 0 0112 20zm3.7-2.9c.5-1.3.9-2.7 1.1-4.1h3.1a8 8 0 01-4.2 4.1z"/>
                  </svg>
                </span>
                Languages
              </h3>
              <ul style="margin:0; padding-left:1.1em;">
                <li>Mandarin Chinese</li>
                <li>Cantonese Chinese</li>
                <li>English</li>
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
