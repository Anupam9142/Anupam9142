<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=DM+Sans:wght@400;500&display=swap');

  *{
    box-sizing:border-box;
    margin:0;
    padding:0;
  }

  .rm{
    background:#0d1117;
    border-radius:8px;
    padding:2rem 1.75rem;
    font-family:'DM Sans',sans-serif;
    color:#e6edf3;
  }

  .center{text-align:center;}

  .divider{
    border:none;
    border-top:1px solid #21262d;
    margin:16px 0;
  }

  .sec-hd{
    font-family:'Inter',sans-serif;
    font-size:11px;
    font-weight:600;
    color:#8b949e;
    letter-spacing:1.5px;
    text-transform:uppercase;
    margin:16px 0 10px;
    display:flex;
    align-items:center;
    gap:8px;
  }

  .sec-hd::after{
    content:'';
    flex:1;
    height:1px;
    background:#21262d;
  }

  .sub-hd{
    font-size:10px;
    color:#58a6ff;
    letter-spacing:1px;
    text-transform:uppercase;
    margin:10px 0 6px;
    font-family:'Inter',sans-serif;
    font-weight:500;
  }

  .badges{
    display:flex;
    flex-wrap:wrap;
    gap:5px;
    margin-bottom:4px;
  }

  .b{
    display:inline-flex;
    align-items:center;
    gap:6px;
    font-size:11px;
    font-family:'Inter',sans-serif;
    font-weight:500;
    padding:4px 10px;
    border-radius:5px;
    border:1px solid #30363d;
    background:#161b22;
    color:#c9d1d9;
  }

  .b img{
    width:14px;
    height:14px;
    object-fit:contain;
    display:block;
    flex-shrink:0;
  }

  .about-text{
    font-size:13px;
    color:#8b949e;
    line-height:1.9;
    border-left:2px solid #58a6ff;
    padding-left:14px;
  }

  .about-text strong{
    color:#e6edf3;
    font-weight:500;
  }

  .pill{
    font-size:10px;
    padding:2px 9px;
    border-radius:20px;
    border:1px solid #30363d;
    color:#8b949e;
    background:#161b22;
    display:inline-flex;
    align-items:center;
    gap:4px;
  }
</style>

<div class="rm">

  <div class="center" style="margin-bottom:1.5rem;">
    <div style="display:flex;align-items:center;justify-content:center;gap:14px;margin-bottom:10px;">
      <img src="https://avatars.githubusercontent.com/u/105556225?v=4"
           style="width:56px;height:56px;border-radius:50%;border:2px solid #30363d;"
           alt="avatar">

      <div style="text-align:left;">
        <div style="font-family:'Inter',sans-serif;font-size:20px;font-weight:600;color:#e6edf3;">
          Hey, I'm Anupam 👋
        </div>

        <div style="font-size:13px;color:#8b949e;margin-top:2px;">
          Software Developer • Tech Explorer • Problem Solver
        </div>
      </div>
    </div>

    <div style="display:flex;justify-content:center;gap:8px;flex-wrap:wrap;margin-top:6px;">
      <span class="pill">🌍 anupam9142.com</span>
      <span class="pill">👁️ visitor badge</span>
      <span class="pill">🐙 3 followers</span>
    </div>
  </div>

  <div class="divider"></div>

  <div class="sec-hd">About me</div>

  <div class="about-text">
    I'm a passionate and curious <strong>software developer</strong>
    who loves building clean, scalable, and impactful solutions.
  </div>

  <div class="divider"></div>

  <div class="sec-hd">Languages</div>

  <div class="badges">
    <span class="b">Python</span>
    <span class="b">Java</span>
    <span class="b">C++</span>
    <span class="b">JavaScript</span>
    <span class="b">TypeScript</span>
  </div>

</div>
