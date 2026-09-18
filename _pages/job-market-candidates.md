---
title: "Job Market Candidates"
permalink: /job-market-candidates/
layout: single
author_profile: false
---

<style>
  .jmc-wrap {
    --jmc-ink:#1a1a1a;
    --jmc-muted:#5a5a5a;
    --jmc-rule:#dcdcdc;
    --jmc-accent:#8c1515; /* swap for your own accent color */
    --jmc-card-bg:#ffffff;
  }

  .jmc-wrap * { box-sizing: border-box; }

  .jmc-intro {
    max-width:1120px;
    margin:0 auto 32px;
  }

  .jmc-intro p {
    margin:0;
    color:var(--jmc-muted);
    font-size:1rem;
    max-width:60ch;
  }

  /* ---- the card grid ---- */
  .jmc-grid{
    max-width:1120px;
    margin:0 auto;
    display:flex;
    flex-wrap:wrap;
    gap:32px;
  }

  .jmc-card{
    display:flex;
    flex-direction:column;
    width:calc((100% - 64px) / 3); /* 3 per row, accounting for 32px gaps */
    min-width:240px;
    background:var(--jmc-card-bg);
    border:1px solid var(--jmc-rule);
    border-radius:4px;
    overflow:hidden;
  }

  /* The flex container holding the headshot.
     padding-top gives the photo room to breathe from the
     card's top border, instead of sitting flush against it. */
  .jmc-photo-wrap{
    display:flex;
    justify-content:center;
    align-items:flex-start;
    padding: 28px 24px 0;   /* <-- top padding fix lives here */
    background:#f6f5f3;
  }

  .jmc-photo-wrap img{
    width:100%;
    max-width:160px;
    aspect-ratio: 1 / 1;
    object-fit:cover;
    border-radius:3px;
    display:block;
  }

  .jmc-body{
    padding:20px 24px 24px;
    display:flex;
    flex-direction:column;
    gap:6px;
    flex:1;
  }

  .jmc-name{
    font-size:1.15rem;
    font-weight:600;
    margin:0;
    line-height:1.25;
    color: var(--jmc-ink);
  }

  .jmc-fields{
    font-size:0.85rem;
    color:var(--jmc-muted);
    margin:0 0 8px;
    line-height:1.4;
  }

  .jmc-jmp{
    font-size:0.85rem;
    margin:0 0 auto;
    line-height:1.45;
    color: var(--jmc-ink);
  }

  .jmc-jmp .jmc-label{
    color:var(--jmc-muted);
    display:block;
    font-size:0.75rem;
    text-transform:uppercase;
    letter-spacing:0.04em;
    margin-bottom:2px;
  }

  .jmc-links{
    margin-top:14px;
    padding-top:12px;
    border-top:1px solid var(--jmc-rule);
    font-size:0.85rem;
    display:flex;
    gap:10px;
    flex-wrap:wrap;
  }

  .jmc-links a{
    color:var(--jmc-accent);
    text-decoration:none;
  }

  .jmc-links a:hover{
    text-decoration:underline;
  }

  .jmc-links .jmc-divider{
    color:var(--jmc-rule);
  }

  @media (max-width: 720px){
    .jmc-card{ width:calc((100% - 32px) / 2); }
  }
  @media (max-width: 480px){
    .jmc-card{ width:100%; }
  }
</style>

<div class="jmc-wrap">

  <div class="jmc-intro">
    <p>Meet this year's candidates on the job market, listed with their research fields and job market paper.</p>
  </div>

  <div class="jmc-grid">

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 1">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 1</p>
      <p class="jmc-fields">Labor Economics, Public Economics</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 2">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 2</p>
      <p class="jmc-fields">Macroeconomics, International Finance</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 3">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 3</p>
      <p class="jmc-fields">Industrial Organization, Microeconomic Theory</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 4">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 4</p>
      <p class="jmc-fields">Development Economics, Political Economy</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 5">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 5</p>
      <p class="jmc-fields">Econometrics, Applied Microeconomics</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 6">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 6</p>
      <p class="jmc-fields">Environmental Economics, Public Finance</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 7">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 7</p>
      <p class="jmc-fields">Behavioral Economics, Household Finance</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 8">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 8</p>
      <p class="jmc-fields">Health Economics, Applied Microeconomics</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 9">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 9</p>
      <p class="jmc-fields">Urban Economics, Regional Economics</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 10">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 10</p>
      <p class="jmc-fields">Financial Economics, Corporate Finance</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 11">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 11</p>
      <p class="jmc-fields">Trade Economics, Growth Theory</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 12">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 12</p>
      <p class="jmc-fields">Education Economics, Labor Economics</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 13">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 13</p>
      <p class="jmc-fields">Market Design, Game Theory</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 14">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 14</p>
      <p class="jmc-fields">Monetary Economics, Macro-Finance</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>

  <div class="jmc-card">
    <div class="jmc-photo-wrap">
      <img src="https://placehold.co/320x320/e8e6e1/5a5a5a?text=Photo" alt="Photo of Candidate 15">
    </div>
    <div class="jmc-body">
      <p class="jmc-name">Candidate Name 15</p>
      <p class="jmc-fields">Political Economy, Economic History</p>
      <p class="jmc-jmp">
        <span class="jmc-label">Job Market Paper</span>
        Title of the Job Market Paper Goes Here
      </p>
      <div class="jmc-links">
        <a href="#">CV</a><span class="jmc-divider">|</span>
        <a href="#">Website</a><span class="jmc-divider">|</span>
        <a href="#">Email</a>
      </div>
    </div>
  </div>
  </div>

</div>
