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
          html { scroll-behavior: smooth; }      /* 平滑滚动 */
          [id] { scroll-margin-top: 72px; }      /* 预留导航栏高度，避免被顶栏遮住 */
              /* Publications: 每条条目/摘要/链接样式 */
          .pub-item{ margin:18px 0; }
          .pub-ref{ margin:0 0 6px; }
          .pub-abstract{
            color:#616161;               /* 摘要浅一点 */
            margin:4px 0 8px;
            padding-left:0.9rem;         /* 缩进 */
            border-left:2px solid #e5e7eb;/* 可选左侧细线，不要就去掉这一行 */
            line-height:1.6;
          }
          .pub-links{ margin:0; }
          .pub-links a{ color:#555; text-decoration-color:#bbb; }
          /* Teaching block */
          .teach { border-top:1px solid #e5e7eb; padding-top:10px; margin-top:6px; }
          .teach-item { display:flex; align-items:flex-start; justify-content:space-between; gap:16px; padding:10px 0; }
          .teach-left { flex:1; }
          .teach-title { font-weight:600; }
          .teach-sub { color:#555; margin-top:4px; }
          .teach-right { white-space:nowrap; color:#444; }
          /* 窄屏下改为上下堆叠 */
          @media (max-width: 640px){
            .teach-item { flex-direction:column; gap:6px; }
            .teach-right { white-space:normal; }
          }
          /* Grants & Awards block */
          .awards { border-top:1px solid #e5e7eb; padding-top:10px; margin-top:6px; }
          .awards-item { display:flex; align-items:flex-start; justify-content:space-between; gap:16px; padding:10px 0; }
          .awards-left { flex:1; }
          .awards-title { font-weight:600; }
          .awards-sub { color:#555; margin-top:4px; }
          .awards-right { white-space:nowrap; color:#444; }
          
          /* 窄屏下改为上下堆叠 */
          @media (max-width: 640px){
            .awards-item { flex-direction:column; gap:6px; }
            .awards-right { white-space:normal; }
          }
        </style>

  ##################################### Bio ########################################################################
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
#          <!--加一小章节Education -->
#          <div style="display:flex; gap:36px; flex-wrap:wrap; align-items:flex-start; margin-top:18px;">
#            <!-- Education -->
#            <div style="flex:1; min-width:280px;">
#              <h3 style="margin:0 0 8px; font-weight:700; font-size:1em; line-height:inherit; display:flex; align-items:center; gap:8px;">
#                Education
#              </h3>
#              <ul style="margin:0; padding-left:0; list-style:none;">
#                <!-- 每条前也有帽子 -->
#                <li style="display:flex; gap:10px; align-items:flex-start; margin:0 0 10px;">
#                  <span aria-hidden="true" style="line-height:1;">
#                    <svg width="16" height="16" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
#                      <path d="M12 3l10 5-10 5L2 8l10-5z"/><path d="M19 11v3c0 3.3-3.58 6-7 6s-7-2.7-7-6v-3l7 3 7-3z"/>
#                    </svg>
#                  </span>
#                  <span>
#                    <strong>Ph.D. in Finance</strong>, 2020<br>
#                    <span style="color:#555;">The University of Hong Kong</span>
#                  </span>
#                </li>
#                <li style="display:flex; gap:10px; align-items:flex-start; margin:0 0 10px;">
#                  <span aria-hidden="true" style="line-height:1;">
#                    <svg width="16" height="16" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
#                      <path d="M12 3l10 5-10 5L2 8l10-5z"/><path d="M19 11v3c0 3.3-3.58 6-7 6s-7-2.7-7-6v-3l7 3 7-3z"/>
#                    </svg>
#                  </span>
#                  <span>
#                    <strong>MPhil in Economic Psychology</strong>, 2015<br>
#                    <span style="color:#555;">Paris-Sorbonne & Paris Descartes (joint)</span>
#                  </span>
#                </li>
#                <li style="display:flex; gap:10px; align-items:flex-start; margin:0 0 10px;">
#                  <span aria-hidden="true" style="line-height:1;">
#                    <svg width="16" height="16" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
#                      <path d="M12 3l10 5-10 5L2 8l10-5z"/><path d="M19 11v3c0 3.3-3.58 6-7 6s-7-2.7-7-6v-3l7 3 7-3z"/>
#                    </svg>
#                  </span>
#                  <span>
#                    <strong>MSc in Financial Engineering</strong>, 2015<br>
#                    <span style="color:#555;">Université Paris-Dauphine</span>
#                  </span>
#                </li>
#                <li style="display:flex; gap:10px; align-items:flex-start; margin:0;">
#                  <span aria-hidden="true" style="line-height:1;">
#                    <svg width="16" height="16" viewBox="0 0 24 24" fill="#444" xmlns="http://www.w3.org/2000/svg">
#                      <path d="M12 3l10 5-10 5L2 8l10-5z"/><path d="M19 11v3c0 3.3-3.58 6-7 6s-7-2.7-7-6v-3l7 3 7-3z"/>
#                    </svg>
#                  </span>
#                  <span>
#                    <strong>BSc in Applied Economics</strong>, 2012<br>
#                    <span style="color:#555;">Université Paris-Dauphine</span>
#                  </span>
#                </li>
#              </ul>
#            </div>
#          </div>



  ############# Publications #########################################################
  - block: markdown
    id: publications
    content:
      title: "Publications"
      text: |-
        <!-- Pub 1 -->
        <div class="pub-item">
         <p class="pub-ref" style="margin:0 0 4px;">
           1. The Allocation of Talent and Financial Development, 1897–1936. With
            <a href="https://www.hkubs.hku.hk/people/chen-lin/" target="_blank" rel="noopener">Chen Lin</a>,
            <a href="https://chichengma.weebly.com/" target="_blank" rel="noopener">Chicheng Ma</a>, and
            <a href="https://scholar.google.com/citations?user=wL_q58YAAAAJ&hl=en" target="_blank" rel="noopener">Yuchen Sun</a>.
            <strong><em>Management Science</em></strong>，2025
          </p>
          <p class="pub-abstract">We examine how the supply of talent affected financial development based on an experiment that abruptly changed the allocation of talent in historical China. Under the meritocratic civil examination system, government service was the main employment for the Chinese intellectuals. The abolition of this system in 1905 reduced the status and wealth attached to government service, which led the intellectuals to turn to modern banking as a high-status sector of employment. We find that regions where there were more candidates for the civil examination produced more financial professionals after 1905, which translated to a greater development of modern banking.</p>
          <p class="pub-links">
            [<a href="paper/Keju.pdf" target="_blank" rel="noopener">Paper</a>]
            [<a href="paper/Keju_Appendix.pdf" target="_blank" rel="noopener">Appendix</a>]
            [<a href="https://pubsonline.informs.org/doi/full/10.1287/mnsc.2023.00456" target="_blank" rel="noopener">Link</a>]
          </p>
        </div>
        <!-- Pub 2 -->
        <div class="pub-item">
         <p class="pub-ref" style="margin:0 0 4px;">
          2. The Legal Origins of Financial Development: Evidence from the Shanghai Concessions.</strong>
          With
          <a href="https://www.hoover.org/profiles/ross-levine" target="_blank" rel="noopener">Ross Levine</a>,
          <a href="https://www.hkubs.hku.hk/people/chen-lin/" target="_blank" rel="noopener">Chen Lin</a>, and
          <a href="https://chichengma.weebly.com/" target="_blank" rel="noopener">Chicheng Ma</a>.
          <strong><em>The Journal of Finance</em></strong>，2023
          </p>  
          <p class="pub-abstract">The primary challenge to assessing the legal origins view of comparative financial development is identifying exogenous changes in legal systems. We assemble new data on Shanghai's British and French concessions between 1845 and 1936. Two regime changes altered British and French legal jurisdiction over their respective concessions. By examining the changing application of different legal traditions to adjacent neighborhoods within the same city and controlling for military, economic, and political characteristics, we offer new evidence consistent with the legal origins view: the financial development advantage in the British concession widened after Western legal jurisdiction intensified and narrowed after it abated.</p>
          <p class="pub-links">
            [<a href="paper/Shanghai.pdf" target="_blank" rel="noopener">Paper</a>]
            [<a href="paper/Shanghai_Appendix.pdf" target="_blank" rel="noopener">Appendix</a>]
            [<a href="https://onlinelibrary.wiley.com/doi/full/10.1111/jofi.13284" target="_blank" rel="noopener">Link</a>]
          </p>
        </div>
        <!-- Pub 3 -->
        <div class="pub-item">
         <p class="pub-ref" style="margin:0 0 4px;">
           3. The Telegraph and Modern Banking Development, 1881–1936. With
            <a href="https://www.hkubs.hku.hk/people/chen-lin/" target="_blank" rel="noopener">Chen Lin</a>,
            <a href="https://chichengma.weebly.com/" target="_blank" rel="noopener">Chicheng Ma</a>, and
            <a href="https://scholar.google.com/citations?user=wL_q58YAAAAJ&hl=en" target="_blank" rel="noopener">Yuchen Sun</a>.
            <strong><em>Journal of Financial Economics</em></strong> ，2021 
          </p>  
          <p class="pub-abstract">The telegraph was introduced to China in the late 19th century, a time when China also saw the rise of modern banks. Based on this historical context, this paper documents the importance of information technology in banking development. We construct a data set on the distributions of telegraph stations and banks across 287 prefectures between 1881 and 1936. The results show that the telegraph significantly expanded banks’ branch networks in terms of both number and geographic scope. The effect of the telegraph remains robust when we instrument it using proximity to the early military telegraph trunk.</p>
          <p class="pub-links">
            [<a href="paper/Telegraph.pdf" target="_blank" rel="noopener">Paper</a>]
            [<a href="paper/Telegraph_Appendix.pdf" target="_blank" rel="noopener">Appendix</a>]
            [<a href="https://www.sciencedirect.com/science/article/pii/S0304405X21001380" target="_blank" rel="noopener">Link</a>]
          </p>
        </div>

  ############# Working Papers #########################################################
  - block: markdown
    id: working-papers
    content:
      title: "Working Papers"
      text: |-
        <!-- Bonds of Love -->
        <div class="pub-item">
          <p class="pub-ref">
            <strong>Bonds of Love: Patriotism and the Rise of Modern Banks. With <em>Yuchen Sun</em> and <em>Wanda Wang</em>.</strong>
          </p>
          <p class="pub-abstract"> This study examines the role of patriotism in fostering public trust in modern banks when they emerged as a new form of financial institution. In China, the loss of Western financial support during WWI (1914) prompted the Republican government to issue patriotic domestic bonds to address fiscal shortfalls. Modern banks underwrote these bonds and expanded into regions with stronger patriotic sentiment to attract subscriptions. Public trust in these banks was formed as an extension of patriots’ state-building efforts within the framework of social contracts. Historical evidence suggests that patriotism similarly fueled early banking development in other countries.</p>
          <p class="pub-links">
            [<a href="paper/Bonds of love.pdf" target="_blank" rel="noopener">Paper</a>]
            [<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4720595" target="_blank" rel="noopener">Link</a>]
          </p>
        </div>
        <!-- Misselling -->
        <div class="pub-item">
          <p class="pub-ref">
            <strong>Misselling in Financial Advice. With <em>Chenhao Wang</em> and <em>Ting Zhang</em>.</strong>
          </p>
          <p class="pub-abstract"> Financial advisors often steer clients toward high-commission products, leading to poor advice quality. Yet, uncertain investment returns make it challenging to detect deliberate misselling. Our study leverages Chinese Wealth Management Products (WMPs) with implicit guarantees, enabling clear identification of misselling as recommending objectively suboptimal low-return products. Using transaction data from a large Chinese retail bank, we document pervasive misselling (74%). To capture the role of advisors, we find that performance pressure, peer effects, and promotion prospects drive misselling, while client complaints deter it. Stressed advisors particularly target inexperienced clients and private banking clients, and female advisor-male client dyads.</p>
          <p class="pub-links">
            [<a href="paper/Misselling.pdf" target="_blank" rel="noopener">Paper</a>]
            [<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5368923" target="_blank" rel="noopener">Link</a>]
          </p>
        </div>        
        <!-- Birds -->
        <div class="pub-item">
          <p class="pub-ref">
            <strong>From Fine to Feathers: Enforcement Stringency, Protectionism, and Biodiversity. With <em>Chenhao Wang</em> and <em>Ting Zhang</em>.</strong>
          </p>
          <p class="pub-abstract"> Using birdwatching records and staggered reforms that enhance the independence of China’s Environmental Protection Bureaus (EPBs) during 2003-2019, this paper underscores the importance of policy enforcement stringency for biodiversity conservation. We find that greater EPB independence increased bird species richness by 22–32% and bird abundance by 35–46%. The reforms reduced local protectionism, leading to more penalties on privately owned enterprises and incentivizing them to invest in green R&D. However, state-owned enterprises continue to avoid regulatory scrutiny due to persistent central protectionism. Our findings highlight the substantial ecological costs of weak enforcement resulting from incomplete administrative independence.</p>
          <p class="pub-links">
            [<a href="paper/Birds.pdf" target="_blank" rel="noopener">Paper</a>]
            [<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5023110" target="_blank" rel="noopener">Link</a>]
          </p>
        </div>        

  ############# Grants & Awards #########################################################
  - block: markdown
    id: funds-awards
    content:
      title: "Grants & Awards"
      text: |-
        <div class="awards">
          <div class="awards-item">
            <div class="awards-left">
              <div class="awards-title">Outstanding Paper Award in Finance (China), China Finance Academic Alliance</div>
              <div class="awards-sub">Awarded for <em>The Allocation of Talent and Financial Development, 1897–1936</em>.</div>
            </div>
            <div class="awards-right">2025</div>
          </div>
          <div class="awards-item">
            <div class="awards-left">
              <div class="awards-title">UNSW Dean’s Research Fellowship</div>
              <div class="awards-sub">Grant: 10,000 AUD</div>
            </div>
            <div class="awards-right">2025</div>
          </div>
          <div class="awards-item">
            <div class="awards-left">
              <div class="awards-title">PWC5355 Best Paper Awards, PwC</div>
              <div class="awards-sub">Awarded for <em>The Legal Origins of Financial Development: Evidence from the Shanghai Concessions</em>.</div>
            </div>
            <div class="awards-right">2024</div>
          </div>
          <div class="awards-item">
            <div class="awards-left">
              <div class="awards-title">Young Scientists Funds, National Natural Science Foundation of China (NSFC)</div>
              <div class="awards-sub">Principal Investigator; Grant: 300,000 RMB</div>
            </div>
            <div class="awards-right">2022</div>
          </div>
          <div class="awards-item">
            <div class="awards-left">
              <div class="awards-title">NSFC–STINT Joint Research Program</div>
              <div class="awards-sub">Participant; Grant: 400,000 RMB (NSFC) and 599,200 SEK (STINT)</div>
            </div>
            <div class="awards-right">2022</div>
          </div>
          <div class="awards-item">
            <div class="awards-left">
              <div class="awards-title">General Program of NSFC</div>
              <div class="awards-sub">Participant; Grant: 300,000 RMB</div>
            </div>
            <div class="awards-right">2021</div>
          </div>
          <div class="awards-item">
            <div class="awards-left">
              <div class="awards-title">Overseas High-Caliber Personnel, Shenzhen</div>
              <div class="awards-sub">Grant of 1,000,000 RMB from the Shenzhen government</div>
            </div>
            <div class="awards-right">2021</div>
          </div>
          <div class="awards-item">
            <div class="awards-left">
              <div class="awards-title">Membership in Beta Gamma Sigma</div>
              <div class="awards-sub"></div>
            </div>
            <div class="awards-right">2021</div>
          </div>
          <div class="awards-item">
            <div class="awards-left">
              <div class="awards-title">FBE PhD Research Excellence Award, The University of Hong Kong</div>
              <div class="awards-sub"></div>
            </div>
            <div class="awards-right">2020</div>
          </div>
        </div>
  ############# 🟣 Teaching #########################################################
  - block: markdown
    id: teaching
    content:
      title: "Teaching"
      text: |-
        <div class="teach">
          <div class="teach-item">
            <div class="teach-left">
              <div class="teach-title">International Corporate Finance / International Business Finance</div>
              <div class="teach-sub">to undergraduates and masters</div>
            </div>
            <div class="teach-right">2023–present, spring</div>
          </div>
          <div class="teach-item">
            <div class="teach-left">
              <div class="teach-title">Financial History</div>
              <div class="teach-sub">to undergraduates, masters, and MBAs; teaching evaluation 98/100</div>
            </div>
            <div class="teach-right">2020–2022, fall and spring</div>
          </div>
          <div class="teach-item">
            <div class="teach-left">
              <div class="teach-title">Corporate Finance</div>
              <div class="teach-sub">to masters</div>
            </div>
            <div class="teach-right">2020–2022, fall and spring</div>
          </div>
        </div>
---
