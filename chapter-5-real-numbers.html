<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Sopaan · Real Numbers</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Source+Sans+3:wght@400;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap">
<style>
  html,body{margin:0;} img{max-width:100%;} [hidden]{display:none !important;}
  :root{
    --navy:#16264A; --navy-2:#1F3B6B; --gold:#C79A3E; --gold-soft:#F3E7C9;
    --paper:#FBF9F4; --paper-2:#F1EAD8; --card:#FFFFFF;
    --ink:#211E1A; --ink-soft:#655D4C; --rule:#E4DCC8;
    --success:#2E8B57; --success-soft:#E1F2E7;
    --danger:#BF4B45; --danger-soft:#FAE3E1;
    --locked:#C7BEA9;
    --focus:#1F3B6B;
    --accent-text:#1F3B6B; --retry-text:#8A661F;
    color-scheme:light;
  }
  @media (prefers-color-scheme: dark){
    :root:not([data-theme="light"]){
      --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
      --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
      --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
      --success:#7BC79A; --success-soft:#1B2E22;
      --danger:#E38884; --danger-soft:#331D1B;
      --locked:#4A4436;
      --focus:#E0B75B;
      --accent-text:#E0B75B; --retry-text:#E0B75B;
      color-scheme:dark;
    }
  }
  :root[data-theme="dark"]{
    --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
    --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
    --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
    --success:#7BC79A; --success-soft:#1B2E22;
    --danger:#E38884; --danger-soft:#331D1B;
    --locked:#4A4436;
    --focus:#E0B75B;
    --accent-text:#E0B75B; --retry-text:#E0B75B;
    color-scheme:dark;
  }

  *{box-sizing:border-box;}
  body{background:var(--paper); color:var(--ink); font-family:'Source Sans 3',-apple-system,'Segoe UI',sans-serif; padding-inline:0; padding-block:0;}
  h1,h2,h3{font-family:'Fraunces',Georgia,serif; text-wrap:balance; margin:0;}
  .num{font-family:'IBM Plex Mono',ui-monospace,monospace; font-variant-numeric:tabular-nums;}

  header.brand{
    background:linear-gradient(155deg,var(--navy) 0%, var(--navy-2) 100%);
    color:#F4EFDF; padding-block:calc(20px + env(safe-area-inset-top,0px)) 18px; padding-inline:20px;
  }
  .brand-row{display:flex; align-items:center; gap:12px; max-width:900px; margin:0 auto;}
  .crest{
    width:42px; height:42px; border-radius:10px; background:var(--gold); color:var(--navy);
    display:flex; align-items:center; justify-content:center; font-family:'Fraunces',serif; font-weight:700; font-size:18px; flex-shrink:0;
  }
  .brand-name{font-size:12px; letter-spacing:.08em; text-transform:uppercase; color:var(--gold); font-weight:700;}
  .series-name{font-size:19px; font-weight:700; font-family:'Fraunces',serif;}
  .chapter-eyebrow{max-width:900px; margin:14px auto 0; font-size:12px; letter-spacing:.06em; text-transform:uppercase; color:#AEB9D6;}
  .chapter-title{font-size:28px; max-width:900px; margin:2px auto 0;}
  .chapter-sub{font-size:14.5px; color:var(--gold); font-weight:700; max-width:900px; margin:3px auto 0;}

  .chapter-progress{max-width:900px; margin:14px auto 0; display:flex; align-items:center; gap:10px;}
  .cp-track{flex:1; height:6px; border-radius:99px; background:rgba(255,255,255,.18); overflow:hidden;}
  .cp-fill{height:100%; background:var(--gold); border-radius:99px; transition:width .3s ease;}
  .cp-label{font-size:11.5px; color:#CFD7EA; white-space:nowrap;}

  .tabbar{position:sticky; top:env(safe-area-inset-top,0px); z-index:15; background:var(--paper); border-bottom:1px solid var(--rule); overflow-x:auto; white-space:nowrap;}
  .tabbar-inner{max-width:900px; margin:0 auto; display:flex; padding-inline:16px;}
  .tab-btn{font-family:inherit; font-size:14px; font-weight:600; color:var(--ink-soft); background:none; border:none; padding:13px 16px; cursor:pointer; position:relative; flex-shrink:0;}
  .tab-btn.active{color:var(--accent-text);}
  .tab-btn.active::after{content:''; position:absolute; left:12px; right:12px; bottom:0; height:3px; background:var(--gold); border-radius:3px 3px 0 0;}
  .tab-count{font-size:11px; color:var(--ink-soft); margin-left:5px;}

  .slide-progress{max-width:900px; margin:0 auto; padding:10px 16px 0; display:flex; align-items:center; gap:10px;}
  .sp-track{flex:1; height:5px; border-radius:99px; background:var(--rule); overflow:hidden;}
  .sp-fill{height:100%; background:var(--accent-text); border-radius:99px; transition:width .3s ease;}
  .sp-label{font-size:12px; color:var(--ink-soft); white-space:nowrap; font-weight:600;}

  .wrap{max-width:900px; margin:0 auto; padding:16px 16px calc(110px + env(safe-area-inset-bottom,0px));}

  .qcard{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px;}
  .qhead{display:flex; align-items:flex-start; gap:10px; margin-bottom:10px;}
  .qnum{width:32px; height:32px; border-radius:8px; background:var(--gold-soft); color:var(--accent-text); display:flex; align-items:center; justify-content:center; font-weight:700; font-family:'Fraunces',serif; flex-shrink:0; font-size:14px;}
  .qtext{font-size:16px; line-height:1.55; flex:1;}
  .qtag{font-size:10.5px; color:var(--gold); background:var(--gold-soft); padding:2px 7px; border-radius:99px; font-weight:700; margin-left:6px; white-space:nowrap;}
  .marks-pill{font-size:11px; font-weight:700; color:var(--ink-soft); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; margin-left:auto; flex-shrink:0; white-space:nowrap;}
  .step-badge{font-size:11px; font-weight:700; color:var(--accent-text); background:var(--paper-2); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; display:inline-block; margin-bottom:12px;}

  .options{display:flex; flex-direction:column; gap:8px; margin-top:10px;}
  .opt{display:flex; align-items:center; gap:10px; padding:11px 12px; border:1.5px solid var(--rule); border-radius:10px; cursor:pointer; font-size:15px; background:var(--paper);}
  .opt input{accent-color:var(--navy-2);}
  .opt.is-correct{border-color:var(--success); background:var(--success-soft);}
  .opt.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .opt.locked{cursor:not-allowed;}

  .subpart-label{font-weight:700; font-size:12.5px; color:var(--accent-text); text-transform:uppercase; letter-spacing:.03em; margin:14px 0 6px;}
  .or-divider{text-align:center; font-size:11px; font-weight:700; letter-spacing:.08em; color:var(--ink-soft); margin:8px 0;}

  .steps{display:flex; flex-direction:column; gap:10px;}
  .step-line{font-size:14.5px; line-height:1.9; background:var(--paper); border:1px dashed var(--rule); border-radius:10px; padding:9px 12px;}
  .step-line.resolved{opacity:.9;}
  .blank-input{font-family:'IBM Plex Mono',monospace; font-size:14px; border:1.5px solid var(--rule); border-radius:6px; padding:3px 8px; width:120px; background:var(--card); color:var(--ink); margin:0 2px;}
  .blank-input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .blank-input.is-correct{border-color:var(--success); background:var(--success-soft);}
  .blank-input.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .blank-input[disabled]{opacity:.85;}
  .reveal-note{font-size:12px; color:var(--danger); padding-left:2px; margin-top:-2px;}

  .feedback{font-size:13.5px; padding:10px 12px; border-radius:9px; margin-top:14px; display:none;}
  .feedback.show{display:block;}
  .feedback.ok{background:var(--success-soft); color:var(--success);}
  .feedback.retry{background:var(--gold-soft); color:var(--retry-text);}
  .feedback.reveal{background:var(--danger-soft); color:var(--danger);}
  .feedback.err{background:var(--danger-soft); color:var(--danger);}
  .attempts-dots{display:inline-flex; gap:4px; margin-left:2px;}
  .attempts-dots span{width:6px; height:6px; border-radius:50%; background:var(--ink-soft); opacity:.3; display:inline-block;}
  .attempts-dots span.used{opacity:1; background:var(--danger);}

  .ar-box{background:var(--paper-2); border-radius:10px; padding:10px 12px; margin-bottom:12px; font-size:13px; color:var(--ink-soft);}

  .navbar{
    position:fixed; left:0; right:0; bottom:0; z-index:30; background:var(--paper);
    border-top:1px solid var(--rule); padding:10px 16px calc(10px + env(safe-area-inset-bottom,0px));
  }
  .navbar-inner{max-width:900px; margin:0 auto; display:flex; gap:8px; flex-wrap:wrap; align-items:center;}
  .btn{font-family:inherit; font-size:13.5px; font-weight:700; padding:10px 14px; border-radius:9px; border:1.5px solid var(--rule); background:var(--card); color:var(--ink); cursor:pointer;}
  .btn:hover{border-color:var(--navy-2);}
  .btn:disabled{opacity:.4; cursor:not-allowed;}
  .btn-primary{background:var(--navy-2); color:#fff; border-color:var(--navy-2);}
  .navbar .spacer{flex:1;}

  .fab{position:fixed; right:16px; bottom:calc(74px + env(safe-area-inset-bottom,0px)); background:var(--gold); color:var(--navy); border:none; border-radius:999px; padding:11px 16px; font-family:inherit; font-weight:700; font-size:13px; display:flex; align-items:center; gap:7px; cursor:pointer; box-shadow:0 6px 16px rgba(0,0,0,.18); z-index:35;}
  .fab-badge{background:rgba(255,255,255,.55); border-radius:99px; padding:1px 7px; font-size:11px;}

  .overlay{position:fixed; inset:0; background:rgba(20,18,14,.45); z-index:50; display:none; align-items:flex-end; justify-content:center;}
  .overlay.show{display:flex;}
  .palette{background:var(--card); width:min(480px,100%); max-height:78vh; overflow-y:auto; border-radius:18px 18px 0 0; padding:18px 18px calc(18px + env(safe-area-inset-bottom,0px)); border:1px solid var(--rule); border-bottom:none;}
  @media (min-width:640px){ .overlay{align-items:center;} .palette{border-radius:18px; border-bottom:1px solid var(--rule); max-height:74vh;} }
  .palette-head{display:flex; align-items:center; justify-content:space-between; margin-bottom:6px;}
  .palette-head h2{font-size:16px;}
  .palette-close{background:none; border:none; font-size:20px; color:var(--ink-soft); cursor:pointer; padding:4px;}
  .palette-legend{display:flex; gap:12px; flex-wrap:wrap; font-size:11px; color:var(--ink-soft); margin:10px 0 14px;}
  .palette-legend span{display:inline-flex; align-items:center; gap:5px;}
  .dot{width:9px; height:9px; border-radius:50%; display:inline-block;}
  .dot.correct{background:var(--success);} .dot.revealed{background:var(--danger);}
  .dot.skipped{background:var(--gold);} .dot.locked{background:var(--locked);}
  .dot.current{background:var(--navy-2);}
  .chip-grid{display:grid; grid-template-columns:repeat(auto-fill,minmax(48px,1fr)); gap:8px;}
  .chip{border:1.5px solid var(--rule); border-radius:9px; padding:8px 4px; text-align:center; font-family:'IBM Plex Mono',monospace; font-size:12.5px; font-weight:600; cursor:pointer; background:var(--paper); color:var(--ink);}
  .chip[data-status="correct"]{border-color:var(--success); background:var(--success-soft); color:var(--success);}
  .chip[data-status="revealed"]{border-color:var(--danger); background:var(--danger-soft); color:var(--danger);}
  .chip[data-status="skipped"]{border-color:var(--gold); background:var(--gold-soft); color:var(--retry-text);}
  .chip[data-status="locked"]{border-color:var(--rule); color:var(--locked); cursor:not-allowed; background:var(--paper-2);}
  .chip[data-status="current"]{outline:2px solid var(--navy-2); outline-offset:1px;}

  .toast{position:fixed; left:50%; bottom:calc(140px + env(safe-area-inset-bottom,0px)); transform:translateX(-50%); background:var(--ink); color:var(--paper); padding:9px 16px; border-radius:99px; font-size:13px; opacity:0; pointer-events:none; transition:opacity .25s ease; z-index:60;}
  .toast.show{opacity:1;}

  .done-card{text-align:center; padding:36px 20px;}
  .done-card .big{font-size:38px; margin-bottom:6px;}
  .score-pills{display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin:16px 0;}
  .score-pill{padding:8px 16px; border-radius:99px; font-size:13px; font-weight:700;}

  footer.brandfoot{max-width:900px; margin:14px auto 0; padding:0 16px calc(110px + env(safe-area-inset-bottom,0px)); text-align:center; font-size:12px; color:var(--ink-soft);}

  .mode-pill{font-family:inherit; font-size:12.5px; font-weight:700; color:var(--navy); background:var(--gold); border:none; border-radius:99px; padding:6px 14px; cursor:pointer; margin-top:12px; display:inline-flex; align-items:center; gap:6px;}
  .mode-pick{display:flex; flex-direction:column; gap:14px; padding:8px 0 24px;}
  .mode-card{background:var(--card); border:1.5px solid var(--rule); border-radius:16px; padding:22px; cursor:pointer; text-align:left;}
  .mode-card:hover{border-color:var(--navy-2);}
  .mode-card .mode-icon{font-size:26px; margin-bottom:8px;}
  .mode-card h3{font-size:18px; margin-bottom:6px;}
  .mode-card p{font-size:13.5px; color:var(--ink-soft); line-height:1.5; margin:0;}
  .quiz-hint{font-size:12.5px; color:var(--ink-soft); background:var(--paper-2); border-radius:9px; padding:8px 12px; margin-bottom:14px;}
  .review-row{border:1px solid var(--rule); border-radius:10px; padding:11px 13px; margin-bottom:10px;}
  .review-tag{font-size:11.5px; font-weight:700; margin-bottom:4px; display:block;}
  .review-tag.ok{color:var(--success);} .review-tag.bad{color:var(--danger);} .review-tag.na{color:var(--ink-soft);}
  .review-q{font-size:13.5px; margin-bottom:6px; color:var(--ink-soft);}
  .review-ans{font-size:13px; margin-bottom:2px;}

  .who-row{max-width:900px; margin:12px auto 0; display:flex; flex-wrap:wrap; gap:8px; align-items:center;}
  .who-row .mode-pill{margin-top:0;}
  .who{display:inline-flex; flex-wrap:wrap; align-items:center; gap:6px; font-size:12.5px; color:#CFD7EA;}
  .who b{color:#F4EFDF;}
  .who button{font-family:inherit; font-size:12px; font-weight:700; color:#F4EFDF; background:rgba(255,255,255,.12); border:1px solid rgba(255,255,255,.22); border-radius:99px; padding:5px 11px; cursor:pointer;}
  .who button:hover{background:rgba(255,255,255,.2);}
  .login-card{max-width:460px; margin:8px auto 0; background:var(--card); border:1px solid var(--rule); border-radius:16px; padding:22px;}
  .login-card h2{font-size:21px; margin-bottom:4px;}
  .login-card p.lead{font-size:13.5px; color:var(--ink-soft); margin:0 0 16px; line-height:1.5;}
  .fld{display:flex; flex-direction:column; gap:5px; margin-bottom:12px;}
  .fld label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .fld input{font-family:inherit; font-size:15px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:9px; background:var(--paper); color:var(--ink);}
  .fld input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .fld-row{display:grid; grid-template-columns:1fr 1fr; gap:10px;}
  .login-err{font-size:13px; color:var(--danger); background:var(--danger-soft); border-radius:8px; padding:8px 10px; margin-bottom:12px;}
  .login-note{font-size:12px; color:var(--ink-soft); margin-top:12px; line-height:1.5;}
  .known{margin:0 0 16px; display:flex; flex-direction:column; gap:6px;}
  .known-label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .known-btn{display:flex; justify-content:space-between; align-items:center; gap:10px; text-align:left; font-family:inherit; font-size:14.5px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:10px; background:var(--paper); color:var(--ink); cursor:pointer;}
  .known-btn:hover{border-color:var(--navy-2);}
  .known-btn small{font-size:12px; color:var(--ink-soft);}
  .rec-card{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px; margin-bottom:14px;}
  .rec-card h2{font-size:19px; margin-bottom:10px;}
  .rec-card h3{font-size:15px; margin:4px 0 8px;}
  .rec-table-wrap{overflow-x:auto;}
  .rec-table{width:100%; border-collapse:collapse; font-size:13.5px; font-variant-numeric:tabular-nums;}
  .rec-table th{text-align:left; font-size:11.5px; text-transform:uppercase; letter-spacing:.04em; color:var(--ink-soft); padding:6px 8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-table td{padding:8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-bar{display:inline-block; width:70px; height:6px; border-radius:99px; background:var(--rule); overflow:hidden; vertical-align:middle; margin-right:6px;}
  .rec-bar i{display:block; height:100%; background:var(--success);}
  .rec-empty{font-size:13.5px; color:var(--ink-soft);}
  .sec-sub{max-width:900px; margin:0 auto; padding:10px 16px 0; font-size:12.5px; font-weight:700; color:var(--accent-text); letter-spacing:.02em;}
  .opt{flex-wrap:wrap;}
  .opt-l{font-family:'IBM Plex Mono',monospace; font-size:13px; font-weight:600; color:var(--ink-soft);}
  .opt-t{flex:1; min-width:0;}
  .opt.is-chosen:not(.is-correct):not(.is-wrong){border-color:var(--navy-2); background:var(--gold-soft);}
  .opt-tag{font-size:11px; font-weight:700; padding:2px 8px; border-radius:99px; background:var(--card); border:1px solid currentColor; white-space:nowrap;}
  .opt.is-correct .opt-tag{color:var(--success);} .opt.is-wrong .opt-tag{color:var(--danger);} .opt.is-chosen:not(.is-correct):not(.is-wrong) .opt-tag{color:var(--accent-text);}
  .chosen{font-size:13.5px; margin-top:10px; padding:8px 12px; border-radius:9px;}
  .chosen.ok{background:var(--success-soft); color:var(--success);} .chosen.bad{background:var(--danger-soft); color:var(--danger);}
  .chosen + .chosen{margin-top:6px;}
  .solution{margin-top:14px; border:1px solid var(--rule); border-left:4px solid var(--gold); background:var(--paper-2); border-radius:10px; padding:12px 14px;}
  .sol-h{font-family:'Fraunces',Georgia,serif; font-weight:700; font-size:14px; color:var(--accent-text); margin-bottom:6px;}
  .sol-line{font-size:14.5px; line-height:1.7;}
  .rev-sol summary{cursor:pointer; font-size:12.5px; font-weight:700; color:var(--accent-text); margin-top:6px;}
  .rev-sol .solution{margin-top:8px;}
  .chapter-credit{max-width:900px; margin:4px auto 0; font-size:12px; color:#CFD7EA;}
  footer.brandfoot a{color:inherit;}
  .blank-input.wide{width:260px; max-width:100%; font-family:'Source Sans 3',sans-serif;}
  .blank-input.expr{width:170px; max-width:100%;}
  /*fix-layout*/ .cp-fill,.sp-fill{width:0;} .fld{min-width:0;} .fld input{width:100%; min-width:0; box-sizing:border-box;}
  .fig{margin:6px 0 10px; display:flex; justify-content:center;}
  .figsvg{width:100%; max-width:340px; height:auto; overflow:visible;}
  .figsvg .ln,.figsvg .arm{stroke:var(--ink); stroke-width:1.6; fill:none;}
  .figsvg .arm{stroke:var(--accent-text); stroke-width:2;}
  .figsvg .pt{fill:var(--ink);}
  .figsvg .lb{fill:var(--ink); font:600 13px 'Source Sans 3',sans-serif;}
  .figsvg .al{fill:var(--accent-text); font:700 12px 'Source Sans 3',sans-serif;}
  .figsvg .wg{fill:var(--gold-soft); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .wg2{fill:rgba(199,154,62,.35); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .ra{fill:none; stroke:var(--ink); stroke-width:1.2;}
  .figsvg .ahd{fill:var(--ink);}
  .figsvg .pr{fill:var(--paper-2); stroke:var(--ink-soft); stroke-width:1.2;}
  .figsvg .tk{stroke:var(--ink-soft); stroke-width:.8;}
  .figsvg .po{fill:var(--ink); font:600 8.5px 'IBM Plex Mono',monospace;}
  .figsvg .pi{fill:var(--danger); font:600 7.5px 'IBM Plex Mono',monospace;}
  .figsvg .sh{fill:var(--gold-soft); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh2{fill:rgba(199,154,62,.38); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh3{fill:rgba(199,154,62,.22); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .none{fill:none;}
  .figsvg .hid{stroke-dasharray:5 4; fill:none;}
  .figsvg .tick{stroke:var(--ink); stroke-width:1.4; fill:none;}
  .figsvg .shd{fill:var(--accent-text); fill-opacity:.55;}
  .figsvg .cell{fill:var(--card); stroke:var(--ink); stroke-width:1.1;}
  .figsvg .dr{fill:var(--danger);} .figsvg .dw{fill:var(--card); stroke:var(--ink); stroke-width:1.2;}
  .figsvg .dotfill{fill:var(--danger);}
  .tt{border-collapse:collapse; font-size:13.5px; margin:4px auto; font-variant-numeric:tabular-nums;} .tt th,.tt td{border:1px solid var(--rule); padding:4px 9px; text-align:left;} .tt th{background:var(--paper-2); font-weight:700;} .ttw{overflow-x:auto; max-width:100%;}
  .fq{display:inline-flex; flex-direction:column; vertical-align:middle; text-align:center; font-size:.82em; line-height:1.12; margin:0 2px;}
  .fq>span:first-child{border-bottom:1.5px solid currentColor; padding:0 2px;}
  .fq>span:last-child{padding:0 2px;}
  .mx{white-space:nowrap;}
  .blank-input.fr{width:110px;}
  @media (prefers-reduced-motion:reduce){ *{transition:none !important;} }
.datline{display:block;margin-top:8px;padding:8px 10px;border-radius:8px;background:var(--paper-2);font:500 14px/1.7 'IBM Plex Mono',monospace;word-spacing:2px;overflow-wrap:anywhere;}

  .theory{display:flex;flex-direction:column;gap:16px;padding-bottom:40px;}
  .hub{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .hub{grid-template-columns:repeat(3,1fr);} }
  .hub-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:16px;display:flex;flex-direction:column;gap:8px;}
  .hub-card h3{font-family:'Fraunces',serif;font-size:18px;margin:0;color:var(--accent-text);}
  .hub-card p{margin:0;font-size:14px;color:var(--ink-soft);line-height:1.5;}
  .hub-btns{display:flex;flex-wrap:wrap;gap:8px;margin-top:auto;}
  .hub-btn{min-height:40px;border:1.5px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:10px;padding:8px 12px;font:600 14px 'Source Sans 3',sans-serif;cursor:pointer;text-align:left;}
  .hub-btn:hover{border-color:var(--gold);}
  .hub-btn.primary{background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .note{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:18px;scroll-margin-top:120px;}
  .note h2{font-family:'Fraunces',serif;font-size:22px;margin:0 0 4px;color:var(--ink);}
  .note .lt{font-size:13.5px;color:var(--ink-soft);margin:0 0 12px;}
  .note .lt b{color:var(--accent-text);}
  .note h4{font:700 15px 'Source Sans 3',sans-serif;margin:16px 0 6px;color:var(--accent-text);}
  .note p,.note li{font-size:15.5px;line-height:1.6;}
  .note ul{padding-left:20px;margin:6px 0;}
  .keybox{background:var(--gold-soft);border-left:4px solid var(--gold);border-radius:8px;padding:10px 12px;margin:10px 0;font-size:15px;line-height:1.6;}
  .keybox b{color:var(--ink);}
  .ex{background:var(--paper-2);border-radius:10px;padding:12px;margin:10px 0;}
  .ex .exh{font-family:'Fraunces',serif;font-weight:700;color:var(--accent-text);margin-bottom:4px;}
  .ex .exl{font-size:15px;line-height:1.7;}
  .ttab{width:100%;border-collapse:collapse;font-size:14.5px;margin:8px 0;}
  .ttab th,.ttab td{border:1px solid var(--rule);padding:7px 8px;text-align:left;vertical-align:top;}
  .ttab th{background:var(--paper-2);}
  .tscroll{overflow-x:auto;}
  .mono{font-family:'IBM Plex Mono',monospace;font-size:.92em;}
  @media (max-width:480px){ .ttab{font-size:13.5px;} .ttab th,.ttab td{padding:6px;} }
  .note .figsvg{max-width:100%;height:auto;display:block;margin:8px auto;}


  .rep-top{display:flex;flex-wrap:wrap;gap:18px;align-items:center;justify-content:center;margin-top:8px;}
  .rep-legend{flex:1;min-width:220px;display:flex;flex-direction:column;gap:8px;}
  .rep-cap{font:700 13px 'Source Sans 3',sans-serif;color:var(--ink-soft);text-transform:uppercase;letter-spacing:.05em;}
  .rep-li{display:flex;align-items:center;gap:6px;font-size:15px;}
  .rep-n{margin-left:auto;white-space:nowrap;padding-left:8px;font-family:'IBM Plex Mono',monospace;font-weight:600;}
  .sw{display:inline-block;width:12px;height:12px;border-radius:3px;flex:none;}
  .rep-grid{display:grid;grid-template-columns:1fr;gap:12px;}
  @media (min-width:640px){ .rep-grid{grid-template-columns:1fr 1fr;} }
  .rep-card{background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:14px;display:flex;flex-direction:column;gap:10px;}
  .rep-h{display:flex;align-items:center;gap:8px;font:700 16px 'Source Sans 3',sans-serif;}
  .crit{display:inline-grid;place-items:center;width:28px;height:28px;border-radius:50%;color:var(--card);font:700 15px Fraunces,serif;flex:none;}
  .rep-row{display:flex;gap:14px;align-items:center;}
  .rep-stats{display:flex;flex-direction:column;gap:5px;font-size:14.5px;}
  .rep-stats div{display:flex;align-items:center;gap:6px;}
  .rep-lvl{margin-top:4px;color:var(--accent-text);} .rep-lvl span{color:var(--ink-soft);font-size:13px;}
  .rep-note{font-size:13px;color:var(--ink-soft);}


  .skip-chips{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin:12px 0;}
  .skip-chips .chip{min-width:48px;min-height:40px;cursor:pointer;border:1.5px solid var(--gold);background:var(--gold-soft);color:var(--retry-text);border-radius:10px;font:600 14px 'IBM Plex Mono',monospace;}
  .skip-btns{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-top:12px;}


  .kb-toggle{border:none;background:transparent;font-size:15px;cursor:pointer;padding:0 2px;vertical-align:middle;opacity:.7;}
  .vkb{position:fixed;left:0;right:0;bottom:0;z-index:80;background:var(--paper-2);border-top:1px solid var(--rule);box-shadow:0 -6px 20px rgba(0,0,0,.12);padding:6px 6px 8px;display:none;}
  .vkb.show{display:block;}
  .vkb-top{display:flex;justify-content:space-between;align-items:center;max-width:640px;margin:0 auto 4px;font:600 12px 'Source Sans 3',sans-serif;color:var(--ink-soft);}
  .vkb-link{border:none;background:none;color:var(--accent-text);font:600 12px 'Source Sans 3',sans-serif;cursor:pointer;text-decoration:underline;}
  .vkb-row{display:flex;gap:5px;max-width:640px;margin:0 auto 5px;}
  .vkb-k{flex:1;min-height:42px;border:1px solid var(--rule);border-radius:8px;background:var(--card);color:var(--ink);font:600 17px 'IBM Plex Mono',monospace;cursor:pointer;padding:0;}
  .vkb-k.fn{font:600 13px 'Source Sans 3',sans-serif;background:var(--gold-soft);}
  .vkb-k.done{background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .vkb-k:active{transform:scale(.96);}
  body.kb-open .wrap{padding-bottom:360px;}
  body.kb-open .fab{display:none;}
  .tool-bar{display:flex;gap:8px;flex-wrap:wrap;margin:-4px 0 10px;}
  .tool-btn{min-height:36px;border:1.5px solid var(--gold);background:var(--gold-soft);color:var(--ink);border-radius:18px;padding:4px 12px;font:600 13.5px 'Source Sans 3',sans-serif;cursor:pointer;}
  .tool-panel{position:fixed;z-index:85;background:var(--card);border:1px solid var(--rule);border-radius:14px;box-shadow:0 10px 30px rgba(0,0,0,.25);display:none;}
  .tool-panel.show{display:block;}
  .tp-head{display:flex;align-items:center;gap:8px;padding:8px 10px;border-bottom:1px solid var(--rule);font:600 14px 'Source Sans 3',sans-serif;}
  .tp-note{font-size:12px;color:var(--ink-soft);font-weight:500;}
  .tp-x{margin-left:auto;border:1px solid var(--rule);background:var(--paper-2);color:var(--ink);border-radius:8px;min-height:32px;padding:2px 10px;cursor:pointer;font:600 13px 'Source Sans 3',sans-serif;}
  .tp-x + .tp-x{margin-left:0;}
  .calc{right:12px;bottom:84px;width:min(330px,calc(100vw - 24px));}
  body.calc-open .wrap{padding-bottom:440px;}
  body.calc-open .fab{display:none;}
  @media (max-width:640px){ .calc{left:6px;right:6px;width:auto;} .calc-keys button{min-height:36px;} }
  .calc-disp{padding:8px 12px;text-align:right;background:var(--paper-2);}
  .calc-expr{font:500 13px 'IBM Plex Mono',monospace;color:var(--ink-soft);min-height:18px;word-break:break-all;}
  .calc-res{font:600 24px 'IBM Plex Mono',monospace;color:var(--ink);word-break:break-all;}
  .calc-keys{display:grid;grid-template-columns:repeat(6,1fr);gap:5px;padding:8px;}
  .calc-keys button{min-height:40px;border:1px solid var(--rule);border-radius:8px;background:var(--card);color:var(--ink);font:600 14px 'IBM Plex Mono',monospace;cursor:pointer;padding:0;}
  .calc-keys button.fn{background:var(--gold-soft);font-family:'Source Sans 3',sans-serif;font-size:13px;}
  .calc-keys button.eq{grid-column:span 2;background:var(--navy);color:#F4EFDF;border-color:var(--navy);}
  .desmos{left:50%;top:50%;transform:translate(-50%,-50%);width:min(760px,calc(100vw - 16px));height:min(560px,calc(100vh - 90px));flex-direction:column;}
  .desmos.show{display:flex;}
  #desmosBox{flex:1;min-height:0;border-radius:0 0 14px 14px;overflow:hidden;}
  .desmos-msg{padding:24px;text-align:center;color:var(--ink-soft);}
  .chip[data-status="skipped"]{cursor:pointer;}
  .chip[data-status="answered"]{border-color:var(--accent-text);color:var(--accent-text);}


  button.crest-home{border:none;padding:0;position:relative;cursor:pointer;transition:transform .15s ease;}
  button.crest-home:hover,button.crest-home:focus-visible{transform:scale(1.06);outline:2px solid var(--gold);outline-offset:2px;}
  .crest-h{position:absolute;right:-7px;bottom:-7px;width:18px;height:18px;border-radius:50%;background:#F4EFDF;color:var(--navy);font:700 12px/18px 'Source Sans 3',sans-serif;text-align:center;box-shadow:0 1px 3px rgba(0,0,0,.3);}
  .brand .brand-row{position:relative;}
  .bmasw{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);display:flex;flex-shrink:0;white-space:nowrap;align-items:center;gap:6px;background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.25);border-radius:99px;padding:5px 14px;color:#F4EFDF;}
  .bmasw-ic{font-size:16px;} .bmasw-t{font:600 20px 'IBM Plex Mono',monospace;letter-spacing:.02em;min-width:62px;text-align:center;}
  .bmasw-b{border:none;background:rgba(255,255,255,.18);color:#F4EFDF;border-radius:50%;width:30px;height:30px;cursor:pointer;font-size:13px;}
  .bmasw.off{display:none;}
  @media (max-width:560px){ .bmasw{position:static;transform:none;margin-left:auto;padding:4px 5px 4px 8px;gap:4px;} .bmasw-ic{display:none;} .bmasw-t{font-size:16px;min-width:48px;} .bmasw-b{width:26px;height:26px;} .brand .series-name{font-size:15px;} .brand .brand-name{font-size:10.5px;} .brand .brand-row>div:not(.bmasw){min-width:0;} }
  .bmasw-done{font:600 15px 'IBM Plex Mono',monospace;color:var(--accent-text);margin:4px 0 8px;}
  .sp-fab{position:fixed;left:14px;bottom:84px;z-index:60;border:1.5px solid var(--navy-2);background:var(--card);color:var(--ink);border-radius:99px;padding:9px 14px;font:700 14px 'Source Sans 3',sans-serif;box-shadow:0 4px 14px rgba(0,0,0,.15);cursor:pointer;}
  .sp-fab.on{background:var(--navy);color:#F4EFDF;}
  body.kb-open .sp-fab{display:none;}
  .sp-canvas{position:absolute;z-index:55;display:none;touch-action:none;cursor:crosshair;}
  .sp-canvas.passive{pointer-events:none;cursor:default;}
  .sp-bar{position:fixed;top:8px;left:8px;right:8px;margin:0 auto;width:max-content;z-index:90;display:none;align-items:center;gap:6px;background:var(--card);border:1px solid var(--rule);border-radius:14px;padding:6px 8px;box-shadow:0 6px 20px rgba(0,0,0,.2);max-width:calc(100vw - 16px);flex-wrap:wrap;justify-content:center;}
  .sp-lbl{font:700 13px 'Source Sans 3',sans-serif;color:var(--ink-soft);margin-right:2px;}
  .sp-pen,.sp-tool{width:38px;height:38px;border-radius:10px;border:1.5px solid var(--rule);background:var(--paper);cursor:pointer;display:inline-flex;align-items:center;justify-content:center;font-size:17px;padding:0;color:var(--ink);}
  .sp-pen i{width:20px;height:20px;border-radius:50%;display:block;}
  .sp-pen.on,.sp-tool.on{border-color:var(--navy-2);box-shadow:0 0 0 3px var(--gold-soft);}
  @media (max-width:560px){ .sp-lbl{display:none;} .sp-pen,.sp-tool{width:34px;height:34px;} .sp-fab span{display:none;} }

  /* larger reading sizes */
  .chapter-eyebrow{font-size:13.5px;}
  .chapter-title{font-size:36px;line-height:1.15;}
  .chapter-sub{font-size:16.5px;}
  .tab-btn{font-size:15.5px;}
  .sec-sub{font-size:15px;}
  .qtext{font-size:19px;line-height:1.55;}
  .qnum{width:36px;height:36px;font-size:16px;}
  .opt{font-size:17.5px;padding:12px 14px;}
  .step-line{font-size:17.5px;line-height:2;}
  .blank-input{font-size:16px;}
  .sol-line{font-size:16.5px;}
  .feedback{font-size:15px;}
  .note h2{font-size:28px;}
  .note h4{font-size:19px;}
  .note p,.note li{font-size:17.5px;line-height:1.65;}
  .note .lt{font-size:15.5px;}
  .ex .exh{font-size:18px;} .ex .exl{font-size:16.5px;}
  .keybox{font-size:16.5px;}
  .ttab{font-size:15.5px;}
  .hub-card h3{font-size:21px;} .hub-card p{font-size:15.5px;} .hub-btn{font-size:15px;}
  @media (max-width:480px){ .chapter-title{font-size:30px;} .qtext{font-size:18px;} .opt,.step-line{font-size:16.5px;} .note h2{font-size:24px;} .note p,.note li{font-size:16.5px;} }
</style>
</head>
<body>
<header class="brand">
  <div class="brand-row">
    <div class="crest">BM</div>
    <div>
      <div class="brand-name">Brain &amp; Mind Academy</div>
      <div class="series-name">Sopaan <span style="font-weight:400;font-size:14px;color:#CFD7EA;">Practice Series</span></div>
    </div>
  </div>
  <div class="chapter-eyebrow">Class 8 Mathematics · Chapter 5</div>
  <div class="chapter-title">Real Numbers</div>
  <div class="chapter-sub">Theory Notes · Practice by Learning Objective · Learning Assessment</div><div class="chapter-credit">Mixed multiple-choice and fill-in-the-blank practice · Chapter 5</div>
  <div class="chapter-progress">
    <div class="cp-track"><div class="cp-fill" id="cpFill"></div></div>
    <div class="cp-label" id="cpLabel">0% complete</div>
  </div>
  <div class="who-row"><button class="mode-pill" id="modePill" hidden>Choose a mode</button><span class="who" id="whoBar" hidden></span></div>
</header>

<nav class="tabbar"><div class="tabbar-inner" id="tabbar"></div></nav>
<div class="sec-sub" id="secSub"></div><div class="slide-progress"><div class="sp-track"><div class="sp-fill" id="spFill"></div></div><div class="sp-label" id="spLabel">Question 1 of 49</div></div>
<div class="wrap" id="wrap"></div>
<footer class="brandfoot">Brain &amp; Mind Academy · Sopaan Practice Series · Class 8 Mathematics · Chapter 5<br>Chapter follows the Class 8 mathematics syllabus (New Enjoying Mathematics, Class 8). Theory notes, questions, learning assessments and worked solutions are written by Brain &amp; Mind Academy.</footer>

<div class="navbar"><div class="navbar-inner" id="navbarInner"></div></div>
<button class="fab" id="paletteFab"><span>Questions</span><span class="fab-badge" id="fabBadge">0/49</span></button>

<div class="overlay" id="overlay">
  <div class="palette" role="dialog" aria-label="Question palette">
    <div class="palette-head"><h2 id="paletteTitle">Question palette</h2><button class="palette-close" id="paletteClose">&times;</button></div>
    <div class="palette-legend">
      <span><i class="dot current"></i>Current</span><span><i class="dot correct"></i>Correct</span>
      <span><i class="dot revealed"></i>Revealed</span><span><i class="dot skipped"></i>Skipped</span>
      <span><i class="dot locked"></i>Locked</span>
    </div>
    <div class="chip-grid" id="paletteBody"></div>
  </div>
</div>
<div class="toast" id="toast"></div>

<script>
(function(){
"use strict";

/* ================= audio ================= */
var audioCtx=null;
function ensureAudio(){ if(!audioCtx){ try{ audioCtx=new (window.AudioContext||window.webkitAudioContext)(); }catch(e){} } return audioCtx; }
function playTone(freqs,dur,type){
  var ctx=ensureAudio(); if(!ctx) return;
  try{
    var t0=ctx.currentTime;
    freqs.forEach(function(f,i){
      var o=ctx.createOscillator(), g=ctx.createGain();
      o.type=type||'sine'; o.frequency.value=f;
      var start=t0+i*dur;
      g.gain.setValueAtTime(0.0001,start);
      g.gain.exponentialRampToValueAtTime(0.16,start+0.02);
      g.gain.exponentialRampToValueAtTime(0.0001,start+dur);
      o.connect(g); g.connect(ctx.destination);
      o.start(start); o.stop(start+dur+0.02);
    });
  }catch(e){}
}
function playSuccess(){ playTone([523.25,659.25,783.99],0.11,'sine'); }
function playWrong(){ playTone([220,185],0.14,'square'); }
function playReveal(){ playTone([300,220],0.16,'triangle'); }

/* ================= helpers ================= */
function norm(s){
  return String(s===undefined||s===null?'':s).trim().toLowerCase().replace(/\s+/g,'')
    .replace(/[×∗*·]/g,'x').replace(/÷/g,'/').replace(/–|—|−/g,'-')
    .replace(/[²]/g,'^2').replace(/[³]/g,'^3').replace(/[⁴]/g,'^4').replace(/[⁵]/g,'^5')
    .replace(/[⁶]/g,'^6').replace(/[⁷]/g,'^7').replace(/[⁸]/g,'^8').replace(/[⁹]/g,'^9')
    .replace(/\^/g,'');
}
function parseNum(s){
  if(s===undefined||s===null) return null;
  var t=String(s).trim().replace(/,/g,'').replace(/[−–—]/g,'-').replace(/\s+/g,''); if(t==='') return null;
  var neg=false; if(t[0]==='-'){neg=true;t=t.slice(1);}
  var m=t.match(/^(\d+)\/(\d+)$/);
  if(m){ var v=parseInt(m[1],10)/parseInt(m[2],10); return neg?-v:v; }
  if(/^\d+(\.\d+)?$/.test(t)){ var v2=parseFloat(t); return neg?-v2:v2; }
  return null;
}
/* ---- expression checker: compares answers like (P-2w)/2 and P/2-w at random values ---- */
function exprPrep(s){
  return String(s).toLowerCase().replace(/\s+/g,'').replace(/^[a-z]\(x\)=/i,'').replace(/^y=/i,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^2').replace(/³/g,'^3').replace(/⁴/g,'^4').replace(/⁵/g,'^5').replace(/⁶/g,'^6').replace(/⁷/g,'^7').replace(/⁸/g,'^8').replace(/⁹/g,'^9').replace(/π/g,'#').replace(/pi/gi,'#').replace(/½/g,'(1/2)');
}
function exprCompile(src){
  var s=exprPrep(src), i=0, toks=[], absDepth=0;
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length && /[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(/[a-zA-Z#]/.test(ch)){ toks.push({k:'v',v:ch}); i++; continue; }
    if(ch==='|'){ var pv=toks[toks.length-1]; var opn=(absDepth===0)||!pv||('+-*/^(['.indexOf(pv.k)>=0); if(opn){ absDepth++; toks.push({k:'['}); } else { absDepth--; toks.push({k:']'}); } i++; continue; }
    if('+-*/^()'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  var out=[];
  for(var t=0;t<toks.length;t++){
    var a=toks[t], b=out[out.length-1];
    if(b && (b.k==='n'||b.k==='v'||b.k===')'||b.k===']') && (a.k==='n'||a.k==='v'||a.k==='('||a.k==='[')) out.push({k:'&'});
    out.push(a);
  }
  var p=0;
  function peek(){ return out[p]; }
  function parseE(){ var n=parseT(); while(peek() && (peek().k==='+'||peek().k==='-')){ var o=out[p++].k, r=parseT(); n=(function(l,r,o){return function(e){ return o==='+'?l(e)+r(e):l(e)-r(e); };})(n,r,o); } return n; }
  function parseI(){ var n=parseU(); while(peek() && peek().k==='&'){ p++; var r=parseP(); n=(function(l,r){return function(e){ return l(e)*r(e); };})(n,r); } return n; }
  function parseT(){ var n=parseI(); while(peek() && (peek().k==='*'||peek().k==='/')){ var o=out[p++].k, r=parseI(); n=(function(l,r,o){return function(e){ return o==='*'?l(e)*r(e):l(e)/r(e); };})(n,r,o); } return n; }
  function parseU(){ if(peek() && peek().k==='-'){ p++; var u=parseU(); return function(e){ return -u(e); }; } if(peek() && peek().k==='+'){ p++; return parseU(); } return parseP(); }
  function parseP(){ var b=parseA(); if(peek() && peek().k==='^'){ p++; var x=parseU(); return function(e){ return Math.pow(b(e),x(e)); }; } return b; }
  function parseA(){
    var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){ return t.v; };
    if(t.k==='v') return t.v==='#' ? function(){ return Math.PI; } : function(e){ return e[t.v]; };
    if(t.k==='('){ var n=parseE(); if(!peek()||peek().k!==')') throw 0; p++; return n; }
    if(t.k==='['){ var m=parseE(); if(!peek()||peek().k!==']') throw 0; p++; return function(e){ return Math.abs(m(e)); }; }
    throw 0;
  }
  try{ var f=parseE(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function exprEqual(input,answer){
  var f=exprCompile(input), g=exprCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<8;trial++){
    var env={}; 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=1.3+Math.random()*4.1; });
    var x=f(env), y=g(env);
    if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-7*Math.max(1,Math.abs(x),Math.abs(y))) return false;
    hits++;
  }
  return hits>=3;
}
function wordsNorm(s){ return String(s||'').toLowerCase().replace(/\band\b/g,' ').replace(/[^a-z]/g,''); }
function listNorm(s){ return (String(s||'').replace(/[−–—]/g,'-').replace(/(\d) (?=\d{3}\b)/g,'$1').match(/-?\d+(\.\d+)?/g)||[]).join(','); }
function powNorm(s){ return String(s||'').toLowerCase().replace(/\s+/g,'').replace(/[×∗*·.]/g,'x').replace(/[⁰¹²³⁴⁵⁶⁷⁸⁹]+/g,function(m){ return '^'+m.split('').map(function(c){ return '⁰¹²³⁴⁵⁶⁷⁸⁹'.indexOf(c); }).join(''); }).replace(/\^1(?!\d)/g,''); }
function fr(s){ return String(s).replace(/\{(\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>').replace(/\{(\d+)\/(\d+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); }
function gcdI(a,b){ a=Math.abs(a); b=Math.abs(b); while(b){ var t=a%b; a=b; b=t; } return a; }
function fracParse(s){ s=String(s===undefined||s===null?'':s).trim().replace(/[\u2044\u2215\u00f7]/g,'/').replace(/\s+/g,' ').replace(/\s*\/\s*/g,'/'); var m;
  if((m=s.match(/^(-?\d+)$/))) return {v:+m[1],form:'int',n:+m[1],d:1};
  if((m=s.match(/^(-?\d+)\/(\d+)$/))){ if(+m[2]===0) return null; return {v:m[1]/m[2],form:'frac',n:+m[1],d:+m[2]}; }
  if((m=s.match(/^(-?)(\d+)(?: |\+)(\d+)\/(\d+)$/))){ if(+m[4]===0) return null; var sg=m[1]?-1:1; return {v:sg*(+m[2]+m[3]/m[4]),form:'mixed',w:sg*m[2],n:+m[3],d:+m[4]}; }
  if((m=s.match(/^-?\d*\.\d+$/))) return {v:parseFloat(s),form:'dec'};
  return null; }
function fracOK(mode,input,answer){
  if(mode==='flist'){ var A=String(input).split(/[,;]/).map(function(x){return x.trim();}).filter(Boolean), K=String(answer).split(/[,;]/).map(function(x){return x.trim();});
    if(A.length!==K.length) return false; return A.every(function(x,i){ var a=fracParse(x), k=fracParse(K[i]); return a&&k&&Math.abs(a.v-k.v)<1e-9; }); }
  var a=fracParse(input), k=fracParse(answer); if(!a||!k) return false;
  var same=Math.abs(a.v-k.v)<1e-9; if(!same) return false;
  if(mode==='fv') return true;
  if(mode==='dec') return a.form==='dec'||a.form==='int';
  if(mode==='fe') return (a.form==='frac'&&k.form==='frac'&&a.n===k.n&&a.d===k.d)||(a.form==='int'&&k.form==='int');
  if(mode==='fi') return a.form==='frac'||(a.form==='int'&&k.form==='int');
  if(mode==='fl') return a.form==='int'||(a.form==='frac'&&gcdI(a.n,a.d)===1)||(a.form==='mixed'&&a.n<a.d&&gcdI(a.n,a.d)===1);
  if(mode==='fm') return a.form==='int'||(a.form==='mixed'&&a.n>0&&a.n<a.d&&gcdI(a.n,a.d)===1);
  return false; }
function answerMatches(input,answer,accept,expr){
  if(expr==='dec'||expr==='fv'||expr==='fe'||expr==='fl'||expr==='fm'||expr==='fi'||expr==='flist'){ if(input===undefined||input===null||String(input).trim()==='') return false; return fracOK(expr,input,answer); }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  if(expr==='words'){ return [answer].concat(accept||[]).some(function(a){ if(/\d/.test(a)) return norm(a)===norm(input); var w=wordsNorm(a); return w!=='' && w===wordsNorm(input); }); }
  if(expr==='list'){ return [answer].concat(accept||[]).some(function(a){ return listNorm(a)===listNorm(input); }); }
  if(expr==='pow'){ return [answer].concat(accept||[]).some(function(a){ return powNorm(a)===powNorm(input); }); }
  if(expr==='time'){ var tn=function(x){ var t=String(x).toLowerCase().replace(/[\s.]/g,'').replace(/[:h]/g,''); if(/^\d{3}(am|pm)?$/.test(t)) t='0'+t; return t; }; return [answer].concat(accept||[]).some(function(a){ return tn(a)===tn(input); }); }
  if(expr==='glist'){ var gn=function(x){ return String(x).toUpperCase().split(/[\s,;]+/).filter(Boolean).sort().join(','); }; return [answer].concat(accept||[]).some(function(a){ return gn(a)===gn(input); }); }
  if(expr==='coord'){ var cn=function(x){ return String(x).replace(/[\u2212\u2013\u2014]/g,'-').replace(/[\s()\[\]]/g,''); }; return [answer].concat(accept||[]).some(function(a){ return cn(a)===cn(input); }); }
  if(expr==='dlist'){ var dn=function(x){ return (String(x).replace(/[−–—]/g,'-').match(/-?\d*\.?\d+/g)||[]).map(Number).join(','); }; return [answer].concat(accept||[]).some(function(a){ return dn(a)===dn(input); }); }
  if(expr==='set'){ var sn=function(x){ return (String(x).match(/-?\d+/g)||[]).map(Number).sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return sn(a)===sn(input); }); }
  if(expr==='primes'){ var pn=function(x){ var t=powNorm(x).replace(/[^0-9x^]/g,''); var out=[]; t.split('x').forEach(function(tok){ if(!tok) return; var m=tok.split('^'); var b=+m[0], e=m[1]?+m[1]:1; for(var i=0;i<e;i++) out.push(b); }); return out.sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return pn(a)===pn(input); }); }
  if(expr==='angle'){ var an=function(x){ return String(x).toUpperCase().replace(/[^A-Z]/g,''); }; var k=an(answer), v=an(input); return v===k || v===k.split('').reverse().join(''); }
  if(expr==='trans'){ var tv=function(x){ var s=String(x).toLowerCase().replace(/[−–—]/g,'-').replace(/\b(units?|squares?|and|then|steps?|to|the|a)\b/g,' ').replace(/[,;.]/g,' '); var re=/(\d+)\s*(right|left|up|down|r|l|u|d)\b/g, m, dx=0, dy=0, n=0; while((m=re.exec(s))){ var v=+m[1], d=m[2][0]; if(d==='r')dx+=v; else if(d==='l')dx-=v; else if(d==='u')dy+=v; else dy-=v; n++; } if(!n||s.replace(re,'').replace(/\s+/g,'')!=='') return null; return dx+','+dy; }; var ti=tv(input); return ti!==null && [answer].concat(accept||[]).some(function(a){ return tv(a)===ti; }); }
  if(expr==='rot'){ var rv=function(x){ var s=String(x).toLowerCase().replace(/quarter[\s-]*turn/g,'90').replace(/half[\s-]*turn/g,'180').replace(/three[\s-]*quarter[\s-]*turn/g,'270'); var m=s.match(/\b(90|180|270)\b/); if(!m) return null; var a=+m[1]; if(a===180) return '180'; var dir=/anti|counter|acw|ccw/.test(s)?-1:(/clockwise|\bcw\b/.test(s)?1:0); if(!dir) return null; return String(((a*dir)%360+360)%360); }; var ri=rv(input); return ri!==null && ri===rv(answer); }
  if(expr==='expanded'){ var f=function(x){ return String(x).replace(/\s+/g,'').replace(/,/g,''); }; return [answer].concat(accept||[]).some(function(a){ return f(a)===f(input); }); }
  if(expr===true && input!==undefined && input!==null && String(input).trim()!==''){
    if(exprEqual(input,answer)) return true;
    var alt=String(input).replace(/\/\s*(\d+(?:\.\d+)?)\s*([a-zA-Z(])/g,'/$1*$2'); if(alt!==String(input) && exprEqual(alt,answer)) return true;
    return (accept||[]).some(function(a){ return exprEqual(input,a); });
  }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  var n1=parseNum(input), n2=parseNum(answer);
  if(n1!==null && n2!==null){ if(Math.abs(n1-n2)<1e-3) return true; return (accept||[]).some(function(a){ var n3=parseNum(a); return n3!==null && Math.abs(n1-n3)<1e-3; }); }
  var cands=[answer].concat(accept||[]); var ni=norm(input);
  for(var i=0;i<cands.length;i++){ if(norm(cands[i])===ni) return true; }
  return false;
}
function esc(s){ return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;'); }

/* ================= DATA ================= */
var AR_OPTIONS = ["Both A and R are true, and R is the correct explanation of A","Both A and R are true, but R is NOT the correct explanation of A","A is true but R is false","A is false but R is true"];
var THEORY = "<div class=\"hub\"><div class=\"hub-card\"><h3>📖 Theory notes</h3><p>Explained notes for every part of the chapter, with number-line constructions and the book’s worked examples.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-jump=\"n51\">5.1 notes</button><button class=\"hub-btn\" data-jump=\"n52\">5.2 notes</button><button class=\"hub-btn\" data-jump=\"n53\">5.3 notes</button><button class=\"hub-btn\" data-jump=\"n54\">5.4 notes</button><button class=\"hub-btn\" data-jump=\"n55\">5.5 notes</button></div></div><div class=\"hub-card\"><h3>🎯 Practice by learning objective</h3><p>Every Example, Try This and Exercise question from the chapter, sorted by objective, mixing multiple-choice and fill-in-the-blank questions.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s1\">5.1 · Irrational numbers</button><button class=\"hub-btn\" data-go=\"s2\">5.2 · Irrational numbers on the number line</button><button class=\"hub-btn\" data-go=\"s3\">5.3 · Adding and subtracting irrational numbers</button><button class=\"hub-btn\" data-go=\"s4\">5.4 · Multiplying, dividing and rationalising factors</button><button class=\"hub-btn\" data-go=\"s5\">5.5 · Real numbers and their properties</button></div></div><div class=\"hub-card\"><h3>📝 Learning assessment</h3><p>Four short assessments built from the Chapter Check-up. Take them in Quiz mode and open the report to see your results as pie charts.</p><div class=\"hub-btns\"><button class=\"hub-btn\" data-go=\"s6\">A · Knowing and understanding</button><button class=\"hub-btn\" data-go=\"s7\">B · Investigating patterns</button><button class=\"hub-btn\" data-go=\"s8\">C · Communicating</button><button class=\"hub-btn\" data-go=\"s9\">D · Applying mathematics in real-life contexts</button><button class=\"hub-btn primary\" data-go=\"report\">📊 View my report</button></div></div></div><section class=\"note\" id=\"nintro\"><h2>About this chapter</h2><p>So far every number we have met could be written as {p/q} with integers p, q and q ≠ 0. Numbers such as √2, √3, π and e cannot be written this way: they are <b>irrational</b>. Rational and irrational numbers together make up the <b>real numbers</b>.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Assessment</th><th>Skill area</th><th>What it checks</th></tr><tr><td>A</td><td>Knowing and understanding</td><td>Identifying irrational numbers, simplifying and rationalising factors.</td></tr><tr><td>B</td><td>Investigating patterns</td><td>Locating irrational numbers, square-root patterns and the Brain Teaser.</td></tr><tr><td>C</td><td>Communicating</td><td>Describing constructions, stating properties, spotting errors.</td></tr><tr><td>D</td><td>Applying mathematics in real-life contexts</td><td>Areas, ramps, javelin throws and the Statue of Unity.</td></tr></table></div><p><b>Tools:</b> ⏱ at the top shows the time since you signed in. ✏️ opens a scratchpad with four pens for rough work. Tap the BM badge to go back to the home page.</p><p><b>Typing answers:</b> an answer such as 7√2 has two boxes, <b>__ √ __</b>: type the number in front (7) in the first box and the number under the root (2) in the second. Always simplify the root first (√8 = 2√2), so the number under the root has no square factor. Type −2√5 as <span class=\"mono\">-2</span> and <span class=\"mono\">5</span>. Type rational/irrational as a word.</p></section><section class=\"note\" id=\"n51\"><h2>5.1 Irrational numbers</h2><p class=\"lt\"><b>Objective:</b> Tell rational and irrational numbers apart and use the properties of irrational numbers.</p><p>Numbers that <b>cannot</b> be written in the form {p/q}, where p and q are integers and q ≠ 0, are called <b>irrational numbers</b>. Their decimals never end and never repeat.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Rational</th><th>Irrational</th></tr><tr><td>terminating decimals: 0.75, −2.5</td><td>non-terminating, non-recurring decimals</td></tr><tr><td>recurring decimals: 0.333…, 7.777…</td><td>√2 = 1.41421…, √3 = 1.73205…</td></tr><tr><td>square roots of perfect squares: √64 = 8</td><td>square roots of non-perfect squares: √10</td></tr><tr><td>{22/7} (an approximation of π)</td><td>π = 3.14159…, e = 2.71828…</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example (Example 1)</div><div class=\"exl\">2 = {2/1} is <b>rational</b>.<br>√3 = 1.732… never ends or repeats: <b>irrational</b>.<br>√64 = 8 = {8/1}: <b>rational</b>.<br>7.777… = {70/9}: <b>rational</b>.</div></div><h4>Properties of irrational numbers</h4><ul><li>The negative of an irrational number is irrational: −√6.</li><li>Rational + irrational is irrational: 4 + √5.</li><li>(Non-zero rational) × irrational is irrational: 3 × √7 = 3√7.</li><li>The sum or difference of two irrational numbers is often irrational (√5 + √2), but not always: (2 + √3) + (2 − √3) = 4.</li><li>The product or quotient of two irrational numbers may be rational <b>or</b> irrational: √3 × √2 = √6 (irrational) but √8 × √2 = √16 = 4 (rational), and √8 ÷ √2 = √4 = 2.</li></ul><div class=\"keybox\"><b>Check before you decide:</b> simplify first. √125 ÷ √5 looks irrational, but √(125 ÷ 5) = √25 = 5 is rational.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s1\">Practise 5.1 →</button></div></section><section class=\"note\" id=\"n52\"><h2>5.2 Irrational numbers on the number line</h2><p class=\"lt\"><b>Objective:</b> Represent √2, √3, √5, … on the number line by a construction that uses Pythagoras theorem.</p><p>In a right-angled triangle ABC with ∠B = 90°, <b>AC<sup>2</sup> = AB<sup>2</sup> + BC<sup>2</sup></b> (Pythagoras theorem). If AB = BC = 1, then AC<sup>2</sup> = 1 + 1 = 2, so AC = √2.</p><ul><li>Put A at 0 and B at 1 on the number line; draw BC = 1 unit perpendicular to the line.</li><li>With the compass point at A and radius AC, draw an arc to cut the number line at D. D represents √2.</li><li>At C draw CE = 1 unit perpendicular to AC. Then AE<sup>2</sup> = 1<sup>2</sup> + (√2)<sup>2</sup> = 3, so an arc of radius AE cuts the line at √3 (Example 2).</li></ul><svg class=\"figsvg\" viewBox=\"0 0 320 190\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"7.0\" y1=\"160.0\" x2=\"304.6\" y2=\"160.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><line x1=\"38.0\" y1=\"153\" x2=\"38.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"38.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><line x1=\"100.0\" y1=\"153\" x2=\"100.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"100.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line x1=\"162.0\" y1=\"153\" x2=\"162.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"162.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><line x1=\"224.0\" y1=\"153\" x2=\"224.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"224.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><line x1=\"286.0\" y1=\"153\" x2=\"286.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"286.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><line class=\"ln\" x1=\"100.0\" y1=\"160.0\" x2=\"162.0\" y2=\"160.0\"/><line class=\"ln\" x1=\"162.0\" y1=\"160.0\" x2=\"162.0\" y2=\"98.0\"/><line class=\"ln\" x1=\"100.0\" y1=\"160.0\" x2=\"162.0\" y2=\"98.0\"/><line class=\"ln\" x1=\"162.0\" y1=\"98.0\" x2=\"118.2\" y2=\"54.2\"/><line class=\"ln\" x1=\"100.0\" y1=\"160.0\" x2=\"118.2\" y2=\"54.2\"/><path class=\"ra\" d=\"M162.0,151.0 L153.0,151.0 L153.0,160.0\"/><path class=\"hid\" style=\"stroke:var(--ink);stroke-width:1.2\" d=\"M162.0,98.0 A87.7,87.7 0 0 1 187.7,160\"/><path class=\"hid\" style=\"stroke:var(--ink);stroke-width:1.2\" d=\"M118.2,54.2 A107.4,107.4 0 0 1 207.4,160\"/><circle class=\"pt\" cx=\"100.0\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"90.0\" y=\"152.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">A</text><circle class=\"pt\" cx=\"162.0\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"170.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">B</text><circle class=\"pt\" cx=\"162.0\" cy=\"98.0\" r=\"2.8\"/><text class=\"lb\" x=\"171.0\" y=\"92.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">C</text><circle class=\"pt\" cx=\"118.2\" cy=\"54.2\" r=\"2.8\"/><text class=\"lb\" x=\"114.2\" y=\"44.2\" text-anchor=\"middle\" dominant-baseline=\"middle\">E</text><circle class=\"pt\" cx=\"187.7\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"193.7\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">D</text><circle class=\"pt\" cx=\"207.4\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"213.4\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">F</text><text class=\"al\" x=\"131.0\" y=\"152.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"al\" x=\"170.0\" y=\"129.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"al\" x=\"147.1\" y=\"72.1\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"al\" x=\"141.0\" y=\"135.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">√2</text></svg><p>Repeating this, √n can be located once √(n − 1) is located. Some roots are quicker with whole-number sides: for √5 use sides 2 and 1 (2<sup>2</sup> + 1<sup>2</sup> = 5); for √10 use 3 and 1.</p><div class=\"ex\"><div class=\"exh\">Worked example (Example 2)</div><div class=\"exl\">Represent √3: build EC = 1 perpendicular to AC = √2.<br>AE<sup>2</sup> = EC<sup>2</sup> + AC<sup>2</sup> = 1<sup>2</sup> + (√2)<sup>2</sup> = 1 + 2 = 3, so AE = √3.<br>The arc with centre A and radius AE meets the number line at F; F corresponds to <b>√3</b>.</div></div><div class=\"keybox\"><b>The compass keeps the length:</b> the arc turns the slanted length AC (or AE) into a distance measured along the number line from 0.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s2\">Practise 5.2 →</button></div></section><section class=\"note\" id=\"n53\"><h2>5.3 Adding and subtracting irrational numbers</h2><p class=\"lt\"><b>Objective:</b> Simplify square roots and add or subtract like irrational numbers.</p><p><b>Like irrational numbers</b> have the same radical: b√a and c√a (a not a perfect square). Only like irrational numbers can be added or subtracted — add the numbers in front:</p><p style=\"text-align:center\">2√3 + 5√3 = (2 + 5)√3 = 7√3</p><p>2√3 and 3√2 are <b>unlike</b>, so 2√3 + 3√2 cannot be written as one term.</p><h4>Simplify the roots first</h4><p>Take out square factors: √18 = √(3 × 3 × 2) = 3√2, √8 = √(2 × 2 × 2) = 2√2, √20 = 2√5, √45 = 3√5. Terms that looked unlike may then become like.</p><div class=\"ex\"><div class=\"exh\">Worked example (Example 3b)</div><div class=\"exl\">3√2 − √18 + 5√8 = 3√2 − 3√2 + 5 × 2√2<br>= 3√2 − 3√2 + 10√2 = (3 − 3 + 10)√2 = <b>10√2</b>.</div></div><div class=\"ex\"><div class=\"exh\">Worked example (Example 3c)</div><div class=\"exl\">6√5 + 4√20 − √45 = 6√5 + 4 × 2√5 − 3√5<br>= 6√5 + 8√5 − 3√5 = (6 + 8 − 3)√5 = <b>11√5</b>.</div></div><div class=\"keybox\"><b>Remember:</b> √5 + √2 ≠ √7, √5 − √2 ≠ √3 and √5 + √5 = 2√5, not √10.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s3\">Practise 5.3 →</button></div></section><section class=\"note\" id=\"n54\"><h2>5.4 Multiplying, dividing and rationalising factors</h2><p class=\"lt\"><b>Objective:</b> Use √a × √b = √ab and √a ÷ √b = √(a ÷ b), expand products and find rationalising factors.</p><p>For positive numbers a and b: <b>√a × √b = √(ab)</b> and <b>√a ÷ √b = √(a ÷ b)</b>. Multiply the numbers in front and the numbers under the roots separately, then simplify.</p><div class=\"ex\"><div class=\"exh\">Worked example (Example 4)</div><div class=\"exl\">√24 × √3 = √72 = √(2 × 2 × 2 × 3 × 3) = 2 × 3√2 = <b>6√2</b>.<br>6√24 ÷ 2√6 = 3 × √(24 ÷ 6) = 3 × √4 = 3 × 2 = <b>6</b>.</div></div><h4>Expanding brackets</h4><p>Multiply every term in the first bracket by every term in the second, then simplify each product.</p><div class=\"ex\"><div class=\"exh\">Worked example (Example 5)</div><div class=\"exl\">(√3 + √5)(2√6 + 2√5) = √3 × 2√6 + √3 × 2√5 + √5 × 2√6 + √5 × 2√5<br>= 2√18 + 2√15 + 2√30 + 2 × 5 = <b>6√2 + 2√15 + 2√30 + 10</b>.</div></div><h4>Rationalising factor</h4><p>If the product of two irrational numbers is rational, each is a <b>rationalising factor</b> of the other. √2 is a rationalising factor of √2 (√2 × √2 = 2); √3 is a rationalising factor of 5√3 (√3 × 5√3 = 15). For k√n the simplest rationalising factor is √n.</p><div class=\"keybox\"><b>√a × √a = a.</b> So √5 × √5 = 5 (not 25) and 3√3 × 3√3 = 9 × 3 = 27.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s4\">Practise 5.4 →</button></div></section><section class=\"note\" id=\"n55\"><h2>5.5 Real numbers and their properties</h2><p class=\"lt\"><b>Objective:</b> Describe the real number system and use the closure, commutative, associative, distributive, identity, inverse and cancellation properties.</p><p>All rational and irrational numbers together are the <b>real numbers</b>. They include natural numbers, whole numbers, integers, rational numbers and irrational numbers. Every point on the number line is a real number, and every real number is a point on the number line.</p><div class=\"tscroll\"><table class=\"ttab\"><tr><th>Property</th><th>Statement (a, b, c real)</th></tr><tr><td>Closure</td><td>a + b, a − b, a × b and a ÷ b (b ≠ 0) are real</td></tr><tr><td>Commutative</td><td>a + b = b + a; a × b = b × a</td></tr><tr><td>Associative</td><td>(a + b) + c = a + (b + c); (a × b) × c = a × (b × c)</td></tr><tr><td>Distributive</td><td>a × (b + c) = a × b + a × c</td></tr><tr><td>Identity</td><td>a + 0 = a; a × 1 = a</td></tr><tr><td>Inverse</td><td>a + (−a) = 0; a × {1/a} = 1 (a ≠ 0)</td></tr><tr><td>Cancellation</td><td>a + b = b + c ⇒ a = c; a × b = b × c ⇒ a = c (b ≠ 0)</td></tr></table></div><div class=\"ex\"><div class=\"exh\">Worked example (Try This)</div><div class=\"exl\">(5 + 3) + 7 = 8 + 7 = 15 and 5 + (3 + 7) = 5 + 10 = 15: the grouping does not change the sum.<br>√2 × 3 = 3√2 and 3 × √2 = 3√2: the order does not change the product.</div></div><div class=\"keybox\"><b>Inverses:</b> the additive inverse of 2√5 is −2√5, and the multiplicative inverse (reciprocal) of 1{2/5} = {7/5} is {5/7}.</div><div class=\"hub-btns\" style=\"margin-top:12px\"><button class=\"hub-btn primary\" data-go=\"s5\">Practise 5.5 →</button></div></section><section class=\"note\" id=\"nsum\"><h2>Chapter checklist</h2><ul><li>Tell rational and irrational numbers apart and use the properties of irrational numbers.</li><li>Represent √2, √3, √5, … on the number line by a construction that uses Pythagoras theorem.</li><li>Simplify square roots and add or subtract like irrational numbers.</li><li>Use √a × √b = √ab and √a ÷ √b = √(a ÷ b), expand products and find rationalising factors.</li><li>Describe the real number system and use the closure, commutative, associative, distributive, identity, inverse and cancellation properties.</li></ul><div class=\"hub-btns\" style=\"margin-top:10px\"><button class=\"hub-btn\" data-go=\"s6\">Assessment A</button><button class=\"hub-btn\" data-go=\"s7\">Assessment B</button><button class=\"hub-btn\" data-go=\"s8\">Assessment C</button><button class=\"hub-btn\" data-go=\"s9\">Assessment D</button><button class=\"hub-btn primary\" data-go=\"report\">📊 Report</button></div></section>";
var REPORT = [["s6", "A", "Knowing and understanding"], ["s7", "B", "Investigating patterns"], ["s8", "C", "Communicating"], ["s9", "D", "Applying mathematics in real-life contexts"]];
var SECTIONS = [{"id": "s1", "label": "5.1 Irrational", "sub": "Irrational numbers — identifying them and their properties", "slides": [{"kind": "blank", "p": "<b>Looking Back · Q1</b> · What is the additive inverse of {−12/25}?", "tag": "", "marks": "", "flat": [{"t": "Additive inverse = __B1__", "a": {"B1": "12/25"}, "expr": "fl"}], "sol": "a + (−a) = 0, so the additive inverse of {−12/25} is {12/25}."}, {"kind": "mcq", "text": "<b>Looking Back · Q2</b> · Which rational numbers are their own multiplicative inverses?", "opts": ["0, 1 and −1", "1 and −1", "only 1", "0 and 1"], "correct": 1, "tag": "", "sol": "1 × 1 = 1 and (−1) × (−1) = 1. 0 has no multiplicative inverse, since 0 × anything = 0."}, {"kind": "blank", "p": "<b>Looking Back · Q3, Q4</b> · Do as directed.", "tag": "", "marks": "", "flat": [{"t": "Q3) {2/9} × {7/11} = {7/11} × a:  a = __B1__", "a": {"B1": "2/9"}, "expr": "fl"}, {"t": "Q4) |{−11/20}| = __B1__", "a": {"B1": "11/20"}, "expr": "fl"}], "sol": "Multiplication is commutative: {2/9} × {7/11} = {7/11} × {2/9}, so a = {2/9}.\nThe absolute value is the distance from 0: {11/20}."}, {"kind": "mcq", "text": "<b>Looking Back · Q5</b> · Is the commutative law of division true for rational numbers?", "opts": ["Yes: division is the inverse of multiplication, so it is commutative", "No: {1/2} ÷ {1/3} = {3/2} but {1/3} ÷ {1/2} = {2/3}", "Yes: {1/2} ÷ {1/3} and {1/3} ÷ {1/2} both equal {3/2}", "No: division of rational numbers is never defined"], "correct": 1, "tag": "", "sol": "One counter-example is enough: {1/2} ÷ {1/3} = {1/2} × 3 = {3/2}, while {1/3} ÷ {1/2} = {1/3} × 2 = {2/3}. The results differ, so division is not commutative."}, {"kind": "blank", "p": "<b>Example 1</b> · Identify each number as rational or irrational.", "tag": "", "marks": "", "flat": [{"t": "a) 2 → __B1__", "a": {"B1": "rational"}, "expr": "words"}, {"t": "b) √3 → __B1__", "a": {"B1": "irrational"}, "expr": "words"}, {"t": "c) √64 → __B1__", "a": {"B1": "rational"}, "expr": "words"}, {"t": "d) 7.77777 → __B1__", "a": {"B1": "rational"}, "expr": "words"}], "sol": "2 = {2/1}: rational.\n√3 = 1.732… does not end or repeat: irrational.\n√64 = 8 = {8/1}: rational.\n7.77777 is a decimal that ends (and 7.777… = {70/9} if it recurs): rational."}, {"kind": "mcq", "text": "Using the properties of irrational numbers, which product is a rational number?", "opts": ["√8 × √2", "−1 × √6", "√3 × √2", "3 × √7"], "correct": 0, "tag": "", "sol": "√8 × √2 = √16 = 4, which is rational. √3 × √2 = √6, 3√7 and −√6 are irrational."}, {"kind": "blank", "p": "<b>Ex 5A · Q1(a)</b> · True or false: √125 ÷ √5 is an irrational number. Work it out first.", "tag": "", "marks": "", "flat": [{"t": "√125 ÷ √5 = √(125 ÷ 5) = √25 = __B1__", "a": {"B1": "5"}}, {"t": "So the statement is __B1__ (true / false)", "a": {"B1": "false"}, "expr": "words"}], "sol": "√(125 ÷ 5) = √25 = 5.\n5 = {5/1} is a rational number, so the statement is false."}, {"kind": "mcq", "text": "<b>Ex 5A · Q1(b)</b> · True or false: the square root of a rational number is always irrational.", "opts": ["True: taking a square root always gives a non-recurring decimal", "True: only whole numbers can have rational square roots", "False: √4 = 2 and √{9/16} = {3/4} are rational", "False: square roots of rational numbers are never irrational"], "correct": 2, "tag": "", "sol": "Square roots of perfect squares are rational (√4 = 2, √{9/16} = {3/4}); others such as √2 are irrational. So “always irrational” is false."}, {"kind": "mcq", "text": "<b>Ex 5A · Q1(c)</b> · True or false: irrational numbers can be identified by their repeating decimal representations.", "opts": ["True: a decimal that goes on for ever is always irrational", "True: every irrational number has a repeating block of digits", "False: irrational numbers always have terminating decimals", "False: repeating decimals are rational, e.g. 0.333… = {1/3}"], "correct": 3, "tag": "", "sol": "Repeating (recurring) decimals are rational, e.g. 0.333… = {1/3}. Irrational numbers have non-terminating, <b>non-recurring</b> decimals. So the statement is false."}, {"kind": "blank", "p": "<b>Ex 5A · Q1(d)</b> · True or false: the sums or products of rational and irrational numbers are always irrational. Test the product of the rational number 0 and √2.", "tag": "", "marks": "", "flat": [{"t": "0 × √2 = __B1__", "a": {"B1": "0"}}, {"t": "So the statement is __B1__ (true / false)", "a": {"B1": "false"}, "expr": "words"}], "sol": "0 × anything = 0.\n0 is rational, so “always irrational” is wrong: the statement is false. (A rational + an irrational number is irrational, and a <i>non-zero</i> rational × an irrational number is irrational.)"}, {"kind": "mcq", "text": "<b>Ex 5A · Q1(e)</b> · True or false: the mathematical constants π and e are irrational numbers.", "opts": ["False: π = 3.14 exactly, a terminating decimal", "True: but only π; e is a rational number", "True: π = 3.14159… and e = 2.71828… never end or repeat", "False: π = {22/7}, so π is rational"], "correct": 2, "tag": "", "sol": "π = 3.14159… and e = 2.71828… are non-terminating, non-recurring decimals, so both are irrational. {22/7} and 3.14 are only approximations of π. So the statement is true."}, {"kind": "blank", "p": "<b>Ex 5A · Q2(a–e)</b> · Identify as rational or irrational numbers.", "tag": "", "marks": "", "flat": [{"t": "a) −3 → __B1__", "a": {"B1": "rational"}, "expr": "words"}, {"t": "b) √64 → __B1__", "a": {"B1": "rational"}, "expr": "words"}, {"t": "c) {3/4} → __B1__", "a": {"B1": "rational"}, "expr": "words"}, {"t": "d) 2 + √3 → __B1__", "a": {"B1": "irrational"}, "expr": "words"}, {"t": "e) 7√3 → __B1__", "a": {"B1": "irrational"}, "expr": "words"}], "sol": "−3 = {−3/1}.\n√64 = 8.\nAlready in the form {p/q}.\nRational + irrational is irrational.\nNon-zero rational × irrational is irrational."}, {"kind": "blank", "p": "<b>Ex 5A · Q2(f–j)</b> · Identify as rational or irrational numbers.", "tag": "", "marks": "", "flat": [{"t": "f) √7.3 → __B1__", "a": {"B1": "irrational"}, "expr": "words"}, {"t": "g) {18/6} → __B1__", "a": {"B1": "rational"}, "expr": "words"}, {"t": "h) √81 ÷ √3 → __B1__", "a": {"B1": "irrational"}, "expr": "words"}, {"t": "i) −5.8̅ → __B1__", "a": {"B1": "rational"}, "expr": "words"}, {"t": "j) 3.45455455545555… → __B1__", "a": {"B1": "irrational"}, "expr": "words"}], "sol": "7.3 = {73/10} and 730 is not a perfect square (√7.3 = 2.70185…): irrational.\n{18/6} = 3.\n√81 ÷ √3 = 9 ÷ √3 = 3√3: irrational.\n−5.888… is a recurring decimal (= {−53/9}): rational.\nThe number of 5s keeps growing, so the decimal never repeats: irrational."}]}, {"id": "s2", "label": "5.2 Number line", "sub": "Representing irrational numbers on the number line by construction", "slides": [{"kind": "blank", "p": "<b>Example 2</b> · Represent √3 on a number line (Fig. 5.2). AB = BC = 1 unit and CE = 1 unit is drawn perpendicular to AC.", "tag": "", "marks": "", "flat": [{"t": "AC<sup>2</sup> = 1<sup>2</sup> + 1<sup>2</sup> = __B1__", "a": {"B1": "2"}}, {"t": "AE<sup>2</sup> = EC<sup>2</sup> + AC<sup>2</sup> = 1 + __B1__ = __B2__", "a": {"B1": "2", "B2": "3"}}], "sol": "Pythagoras theorem in △ABC: AC<sup>2</sup> = 1 + 1 = 2, so AC = √2.\nIn △ACE: AE<sup>2</sup> = 1<sup>2</sup> + (√2)<sup>2</sup> = 1 + 2 = 3, so AE = √3. The arc with centre A and radius AE meets the number line at F = √3.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 320 190\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"7.0\" y1=\"160.0\" x2=\"304.6\" y2=\"160.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><line x1=\"38.0\" y1=\"153\" x2=\"38.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"38.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><line x1=\"100.0\" y1=\"153\" x2=\"100.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"100.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line x1=\"162.0\" y1=\"153\" x2=\"162.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"162.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><line x1=\"224.0\" y1=\"153\" x2=\"224.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"224.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><line x1=\"286.0\" y1=\"153\" x2=\"286.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"286.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><line class=\"ln\" x1=\"100.0\" y1=\"160.0\" x2=\"162.0\" y2=\"160.0\"/><line class=\"ln\" x1=\"162.0\" y1=\"160.0\" x2=\"162.0\" y2=\"98.0\"/><line class=\"ln\" x1=\"100.0\" y1=\"160.0\" x2=\"162.0\" y2=\"98.0\"/><line class=\"ln\" x1=\"162.0\" y1=\"98.0\" x2=\"118.2\" y2=\"54.2\"/><line class=\"ln\" x1=\"100.0\" y1=\"160.0\" x2=\"118.2\" y2=\"54.2\"/><path class=\"ra\" d=\"M162.0,151.0 L153.0,151.0 L153.0,160.0\"/><path class=\"hid\" style=\"stroke:var(--ink);stroke-width:1.2\" d=\"M162.0,98.0 A87.7,87.7 0 0 1 187.7,160\"/><path class=\"hid\" style=\"stroke:var(--ink);stroke-width:1.2\" d=\"M118.2,54.2 A107.4,107.4 0 0 1 207.4,160\"/><circle class=\"pt\" cx=\"100.0\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"90.0\" y=\"152.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">A</text><circle class=\"pt\" cx=\"162.0\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"170.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">B</text><circle class=\"pt\" cx=\"162.0\" cy=\"98.0\" r=\"2.8\"/><text class=\"lb\" x=\"171.0\" y=\"92.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">C</text><circle class=\"pt\" cx=\"118.2\" cy=\"54.2\" r=\"2.8\"/><text class=\"lb\" x=\"114.2\" y=\"44.2\" text-anchor=\"middle\" dominant-baseline=\"middle\">E</text><circle class=\"pt\" cx=\"187.7\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"193.7\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">D</text><circle class=\"pt\" cx=\"207.4\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"213.4\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">F</text><text class=\"al\" x=\"131.0\" y=\"152.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"al\" x=\"170.0\" y=\"129.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"al\" x=\"147.1\" y=\"72.1\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text></svg>"}, {"kind": "mcq", "text": "<b>Example 2</b> · In Fig. 5.2, which point on the number line represents √3?", "opts": ["F, where the arc with centre A and radius AE meets the line", "B, the foot of the perpendicular BC drawn at 1", "D, where the arc with centre A and radius AC meets the line", "E, the end of the perpendicular CE drawn at C"], "correct": 0, "tag": "", "sol": "AE = √3, and the arc keeps this length along the line from A (= 0), so F represents √3. D represents √2.", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 320 190\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"7.0\" y1=\"160.0\" x2=\"304.6\" y2=\"160.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><line x1=\"38.0\" y1=\"153\" x2=\"38.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"38.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><line x1=\"100.0\" y1=\"153\" x2=\"100.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"100.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line x1=\"162.0\" y1=\"153\" x2=\"162.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"162.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><line x1=\"224.0\" y1=\"153\" x2=\"224.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"224.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><line x1=\"286.0\" y1=\"153\" x2=\"286.0\" y2=\"167\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"286.0\" y=\"178.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><line class=\"ln\" x1=\"100.0\" y1=\"160.0\" x2=\"162.0\" y2=\"160.0\"/><line class=\"ln\" x1=\"162.0\" y1=\"160.0\" x2=\"162.0\" y2=\"98.0\"/><line class=\"ln\" x1=\"100.0\" y1=\"160.0\" x2=\"162.0\" y2=\"98.0\"/><line class=\"ln\" x1=\"162.0\" y1=\"98.0\" x2=\"118.2\" y2=\"54.2\"/><line class=\"ln\" x1=\"100.0\" y1=\"160.0\" x2=\"118.2\" y2=\"54.2\"/><path class=\"ra\" d=\"M162.0,151.0 L153.0,151.0 L153.0,160.0\"/><path class=\"hid\" style=\"stroke:var(--ink);stroke-width:1.2\" d=\"M162.0,98.0 A87.7,87.7 0 0 1 187.7,160\"/><path class=\"hid\" style=\"stroke:var(--ink);stroke-width:1.2\" d=\"M118.2,54.2 A107.4,107.4 0 0 1 207.4,160\"/><circle class=\"pt\" cx=\"100.0\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"90.0\" y=\"152.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">A</text><circle class=\"pt\" cx=\"162.0\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"170.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">B</text><circle class=\"pt\" cx=\"162.0\" cy=\"98.0\" r=\"2.8\"/><text class=\"lb\" x=\"171.0\" y=\"92.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">C</text><circle class=\"pt\" cx=\"118.2\" cy=\"54.2\" r=\"2.8\"/><text class=\"lb\" x=\"114.2\" y=\"44.2\" text-anchor=\"middle\" dominant-baseline=\"middle\">E</text><circle class=\"pt\" cx=\"187.7\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"193.7\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">D</text><circle class=\"pt\" cx=\"207.4\" cy=\"160.0\" r=\"2.8\"/><text class=\"lb\" x=\"213.4\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">F</text><text class=\"al\" x=\"131.0\" y=\"152.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"al\" x=\"170.0\" y=\"129.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"al\" x=\"147.1\" y=\"72.1\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"al\" x=\"141.0\" y=\"135.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">√2</text></svg>"}, {"kind": "mcq", "text": "<b>Ex 5A · Q3</b> · To mark √5 on a number line by construction, which right-angled triangle should you draw on the line from O (= 0)?", "opts": ["OB = 5 units along the line, BC = 1 unit perpendicular", "OB = 2 units along the line, BC = 1 unit perpendicular", "OB = 2 units along the line, BC = 2 units perpendicular", "OB = 1 unit along the line, BC = 1 unit perpendicular"], "correct": 1, "tag": "", "sol": "OC<sup>2</sup> = 2<sup>2</sup> + 1<sup>2</sup> = 5, so OC = √5. The other triangles give √26, √8 and √2."}, {"kind": "blank", "p": "<b>Ex 5A · Q3</b> · In the figure OB = 2 units and BC = 1 unit is perpendicular to the number line. An arc with centre O and radius OC cuts the line at P.", "tag": "", "marks": "", "flat": [{"t": "OC<sup>2</sup> = 2<sup>2</sup> + 1<sup>2</sup> = __B1__", "a": {"B1": "5"}}, {"t": "So P represents √__B1__", "a": {"B1": "5"}}, {"t": "P lies between __B1__ and __B2__ (smaller first)", "a": {"B1": "2", "B2": "3"}}], "sol": "4 + 1 = 5.\nOC = √5 and OP = OC, so P represents √5.\n2<sup>2</sup> = 4 < 5 < 9 = 3<sup>2</sup>, so 2 < √5 < 3 (√5 ≈ 2.236).", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 158.0\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"12.0\" y1=\"98.0\" x2=\"318.0\" y2=\"98.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><line x1=\"20.0\" y1=\"91.0\" x2=\"20.0\" y2=\"105.0\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"20.0\" y=\"116.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><line x1=\"78.0\" y1=\"91.0\" x2=\"78.0\" y2=\"105.0\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"78.0\" y=\"116.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line x1=\"136.0\" y1=\"91.0\" x2=\"136.0\" y2=\"105.0\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"136.0\" y=\"116.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><line x1=\"194.0\" y1=\"91.0\" x2=\"194.0\" y2=\"105.0\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"194.0\" y=\"116.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><line x1=\"252.0\" y1=\"91.0\" x2=\"252.0\" y2=\"105.0\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"252.0\" y=\"116.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><line x1=\"310.0\" y1=\"91.0\" x2=\"310.0\" y2=\"105.0\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"310.0\" y=\"116.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><line class=\"arm\" x1=\"78.0\" y1=\"98.0\" x2=\"194.0\" y2=\"98.0\"/><line class=\"arm\" x1=\"194.0\" y1=\"98.0\" x2=\"194.0\" y2=\"40.0\"/><line class=\"ln\" x1=\"78.0\" y1=\"98.0\" x2=\"194.0\" y2=\"40.0\"/><path class=\"ra\" d=\"M194.0,90.0 L186.0,90.0 L186.0,98.0\"/><path class=\"hid\" style=\"stroke:var(--ink);stroke-width:1.2\" d=\"M194.0,40.0 A129.7,129.7 0 0 1 207.7,98.0\"/><circle class=\"pt\" cx=\"78.0\" cy=\"98.0\" r=\"2.8\"/><text class=\"lb\" x=\"69.0\" y=\"89.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">O</text><circle class=\"pt\" cx=\"194.0\" cy=\"98.0\" r=\"2.8\"/><text class=\"lb\" x=\"185.0\" y=\"89.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">B</text><circle class=\"pt\" cx=\"194.0\" cy=\"40.0\" r=\"2.8\"/><text class=\"lb\" x=\"202.0\" y=\"34.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">C</text><circle class=\"pt\" cx=\"207.7\" cy=\"98.0\" r=\"2.8\"/><text class=\"lb\" x=\"214.7\" y=\"89.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">P</text><text class=\"al\" x=\"136.0\" y=\"89.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><text class=\"al\" x=\"185.0\" y=\"69.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text></svg>"}, {"kind": "mcq", "text": "Continuing the “square-root spiral”, √6 is found as the hypotenuse of a right triangle whose two shorter sides are", "opts": ["√3 and √3 + 1", "√6 and 1", "√5 and 1", "5 and 1"], "correct": 2, "tag": "", "sol": "(√5)<sup>2</sup> + 1<sup>2</sup> = 5 + 1 = 6. In general √n comes from sides √(n − 1) and 1. (Sides √6 and 1 would give √7.)"}, {"kind": "blank", "p": "The figure uses OB = 3 units and BC = 1 unit.", "tag": "", "marks": "", "flat": [{"t": "OC<sup>2</sup> = __B1__", "a": {"B1": "10"}}, {"t": "P represents √__B1__", "a": {"B1": "10"}}, {"t": "P lies between the integers __B1__ and __B2__ (smaller first)", "a": {"B1": "3", "B2": "4"}}], "sol": "3<sup>2</sup> + 1<sup>2</sup> = 9 + 1 = 10.\nOC = √10.\n9 < 10 < 16, so 3 < √10 < 4 (√10 ≈ 3.162).", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 148.33333333333334\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"12.0\" y1=\"88.3\" x2=\"318.0\" y2=\"88.3\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><line x1=\"20.0\" y1=\"81.33333333333334\" x2=\"20.0\" y2=\"95.33333333333334\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"20.0\" y=\"106.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">−1</text><line x1=\"68.3\" y1=\"81.33333333333334\" x2=\"68.3\" y2=\"95.33333333333334\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"68.3\" y=\"106.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line x1=\"116.7\" y1=\"81.33333333333334\" x2=\"116.7\" y2=\"95.33333333333334\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"116.7\" y=\"106.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><line x1=\"165.0\" y1=\"81.33333333333334\" x2=\"165.0\" y2=\"95.33333333333334\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"165.0\" y=\"106.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><line x1=\"213.3\" y1=\"81.33333333333334\" x2=\"213.3\" y2=\"95.33333333333334\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"213.3\" y=\"106.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><line x1=\"261.7\" y1=\"81.33333333333334\" x2=\"261.7\" y2=\"95.33333333333334\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"261.7\" y=\"106.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><line x1=\"310.0\" y1=\"81.33333333333334\" x2=\"310.0\" y2=\"95.33333333333334\" style=\"stroke:var(--ink);stroke-width:1.5\"/><text class=\"lb\" x=\"310.0\" y=\"106.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><line class=\"arm\" x1=\"68.3\" y1=\"88.3\" x2=\"213.3\" y2=\"88.3\"/><line class=\"arm\" x1=\"213.3\" y1=\"88.3\" x2=\"213.3\" y2=\"40.0\"/><line class=\"ln\" x1=\"68.3\" y1=\"88.3\" x2=\"213.3\" y2=\"40.0\"/><path class=\"ra\" d=\"M213.3,80.3 L205.3,80.3 L205.3,88.3\"/><path class=\"hid\" style=\"stroke:var(--ink);stroke-width:1.2\" d=\"M213.3,40.0 A152.8,152.8 0 0 1 221.2,88.33333333333334\"/><circle class=\"pt\" cx=\"68.3\" cy=\"88.3\" r=\"2.8\"/><text class=\"lb\" x=\"59.3\" y=\"79.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">O</text><circle class=\"pt\" cx=\"213.3\" cy=\"88.3\" r=\"2.8\"/><text class=\"lb\" x=\"204.3\" y=\"79.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">B</text><circle class=\"pt\" cx=\"213.3\" cy=\"40.0\" r=\"2.8\"/><text class=\"lb\" x=\"221.3\" y=\"34.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">C</text><circle class=\"pt\" cx=\"221.2\" cy=\"88.3\" r=\"2.8\"/><text class=\"lb\" x=\"228.2\" y=\"79.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">P</text><text class=\"al\" x=\"140.8\" y=\"79.3\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><text class=\"al\" x=\"204.3\" y=\"64.2\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text></svg>"}, {"kind": "mcq", "text": "Which statement about the construction is correct?", "opts": ["The point P is always at a whole number", "The compass keeps the length OC, so OP = OC", "The arc must be centred at B, not at O", "The perpendicular BC must be longer than OB"], "correct": 1, "tag": "", "sol": "The arc is centred at O with radius OC, so the distance OP along the line equals OC."}]}, {"id": "s3", "label": "5.3 Add & subtract", "sub": "Adding and subtracting irrational numbers", "slides": [{"kind": "mcq", "text": "<b>Example 3(a)</b> · Simplify 7√3 + √7.", "opts": ["8√7, adding 7 and 1 in front of √7", "It cannot be combined: 7√3 and √7 are unlike", "4√7, treating 7√3 as 3√7", "8√10, adding the numbers and the roots"], "correct": 1, "tag": "", "sol": "√3 and √7 are different radicals, so 7√3 + √7 stays as it is. (The book’s worked answer (3 + 1)√7 = 4√7 is for 3√7 + √7.)"}, {"kind": "blank", "p": "<b>Example 3(b)</b> · Simplify 3√2 − √18 + 5√8.", "tag": "", "marks": "", "flat": [{"t": "√18 = __B1__√__B2__", "a": {"B1": "3", "B2": "2"}}, {"t": "5√8 = 5 × 2√2 = __B1__√__B2__", "a": {"B1": "10", "B2": "2"}}, {"t": "3√2 − √18 + 5√8 = __B1__√__B2__", "a": {"B1": "10", "B2": "2"}}], "sol": "√18 = √(3 × 3 × 2) = 3√2.\n√8 = √(2 × 2 × 2) = 2√2, so 5√8 = 10√2.\n3√2 − 3√2 + 10√2 = (3 − 3 + 10)√2 = 10√2."}, {"kind": "mcq", "text": "Which pair are like irrational numbers?", "opts": ["2√3 and 3√2", "√5 and 5", "2√3 and 5√3", "√2 and 2√7"], "correct": 2, "tag": "", "sol": "Like irrational numbers have the same radical: √3 in both 2√3 and 5√3."}, {"kind": "blank", "p": "<b>Example 3(c)</b> · Simplify 6√5 + 4√20 − √45.", "tag": "", "marks": "", "flat": [{"t": "4√20 = 4 × 2√5 = __B1__√__B2__", "a": {"B1": "8", "B2": "5"}}, {"t": "√45 = __B1__√__B2__", "a": {"B1": "3", "B2": "5"}}, {"t": "6√5 + 4√20 − √45 = __B1__√__B2__", "a": {"B1": "11", "B2": "5"}}], "sol": "√20 = √(2 × 2 × 5) = 2√5, so 4√20 = 8√5.\n√45 = √(3 × 3 × 5) = 3√5.\n(6 + 8 − 3)√5 = 11√5."}, {"kind": "mcq", "text": "<b>Try This · Q1(a)</b> · 2√8 + 3√2 =", "opts": ["5√10", "5√2", "7√10", "7√2"], "correct": 3, "tag": "", "sol": "2√8 = 2 × 2√2 = 4√2, so 4√2 + 3√2 = 7√2."}, {"kind": "blank", "p": "<b>Try This · Q1(b)</b> · Solve 8√5 − √125.", "tag": "", "marks": "", "flat": [{"t": "√125 = __B1__√__B2__", "a": {"B1": "5", "B2": "5"}}, {"t": "8√5 − √125 = __B1__√__B2__", "a": {"B1": "3", "B2": "5"}}], "sol": "√125 = √(5 × 5 × 5) = 5√5.\n8√5 − 5√5 = 3√5."}, {"kind": "mcq", "text": "<b>Ex 5A · Q4(a–d)</b> · Which of the following operations on irrational numbers is correct?", "opts": ["2√3 + 3√3 = 5√3", "2 + √5 = 2√5", "8√5 − 4√2 = 4√3", "√7 + √5 = √12"], "correct": 0, "tag": "", "sol": "Only like terms add: 2√3 + 3√3 = 5√3. The others add or subtract unlike numbers, which is not allowed (√7 + √5 ≈ 4.88 but √12 ≈ 3.46)."}, {"kind": "blank", "p": "Simplify √50 + √32 − √18.", "tag": "", "marks": "", "flat": [{"t": "√50 = __B1__√__B2__", "a": {"B1": "5", "B2": "2"}}, {"t": "√32 = __B1__√__B2__", "a": {"B1": "4", "B2": "2"}}, {"t": "√50 + √32 − √18 = __B1__√__B2__", "a": {"B1": "6", "B2": "2"}}], "sol": "√50 = √(5 × 5 × 2) = 5√2.\n√32 = √(4 × 4 × 2) = 4√2.\n5√2 + 4√2 − 3√2 = 6√2."}, {"kind": "mcq", "text": "√5 + √5 =", "opts": ["10", "5", "√10", "2√5"], "correct": 3, "tag": "", "sol": "Like terms: 1√5 + 1√5 = 2√5. Adding the numbers under the root (√10) is a common mistake."}]}, {"id": "s4", "label": "5.4 Multiply & divide", "sub": "Multiplying and dividing irrational numbers; rationalising factors", "slides": [{"kind": "blank", "p": "<b>Example 4(a–c)</b> · Simplify the following.", "tag": "", "marks": "", "flat": [{"t": "a) 5 × √5 = __B1__√__B2__", "a": {"B1": "5", "B2": "5"}}, {"t": "b) √3 × √7 = √__B1__", "a": {"B1": "21"}}, {"t": "c) √24 × √3 = __B1__√__B2__", "a": {"B1": "6", "B2": "2"}}], "sol": "5 × √5 = 5√5.\n√(3 × 7) = √21.\n√72 = √(2 × 2 × 2 × 3 × 3) = 2 × 3√2 = 6√2."}, {"kind": "mcq", "text": "<b>Example 4(d)</b> · Simplify √14 ÷ √7.", "opts": ["√2", "2", "√98", "√7"], "correct": 0, "tag": "", "sol": "√14 ÷ √7 = √(14 ÷ 7) = √2."}, {"kind": "blank", "p": "<b>Example 4(e)</b> · Simplify 6√24 ÷ 2√6.", "tag": "", "marks": "", "flat": [{"t": "6√24 ÷ 2√6 = 3 × √(24 ÷ 6) = 3 × √4 = __B1__", "a": {"B1": "6"}}], "sol": "{6/2} = 3 and √(24 ÷ 6) = √4 = 2, so 3 × 2 = 6."}, {"kind": "blank", "p": "<b>Example 5</b> · Simplify (√3 + √5)(2√6 + 2√5). Write the answer as a√2 + b√15 + c√30 + d.", "tag": "", "marks": "", "flat": [{"t": "= __B1__√2 + __B2__√15 + __B3__√30 + __B4__", "a": {"B1": "6", "B2": "2", "B3": "2", "B4": "10"}}], "sol": "√3 × 2√6 = 2√18 = 2 × 3√2 = 6√2; √3 × 2√5 = 2√15; √5 × 2√6 = 2√30; √5 × 2√5 = 2 × 5 = 10. So 6√2 + 2√15 + 2√30 + 10. (The book’s solution uses 3√5 instead of 2√5 in the second bracket and gets 6√2 + 3√15 + 2√30 + 15.)"}, {"kind": "mcq", "text": "√3 is a rationalising factor of 5√3 because", "opts": ["√3 × 5√3 = 15, which is rational", "√3 + 5√3 = 6√3, which is irrational", "5√3 ÷ √3 = √5, which is rational", "√3 × 5√3 = 5√9, which is irrational"], "correct": 0, "tag": "", "sol": "√3 × 5√3 = 5 × √3 × √3 = 5 × 3 = 15, a rational number."}, {"kind": "blank", "p": "<b>Try This · Q1(c, d)</b> · Solve.", "tag": "", "marks": "", "flat": [{"t": "c) √12 × √27 = __B1__", "a": {"B1": "18"}}, {"t": "d) 4√81 ÷ 2√9 = __B1__", "a": {"B1": "6"}}], "sol": "√(12 × 27) = √324 = 18 (or 2√3 × 3√3 = 6 × 3 = 18).\n4 × 9 = 36 and 2 × 3 = 6: 36 ÷ 6 = 6."}, {"kind": "mcq", "text": "<b>Try This · Q2</b> · A rationalising factor of 11√6 is", "opts": ["√11", "6√11", "√6", "11"], "correct": 2, "tag": "", "sol": "√6 × 11√6 = 11 × 6 = 66, which is rational. √11 × 11√6 = 11√66, 11 × 11√6 = 121√6 and 6√11 × 11√6 = 66√66 are irrational."}, {"kind": "mcq", "text": "<b>Ex 5A · Q4(e–j)</b> · Which of the following operations is NOT correct?", "opts": ["√5 × √5 = 25", "2√3 ÷ 3√6 = 2 ÷ (3√2)", "√7 × √7 = 7", "3√3 × 3√3 = 27"], "correct": 0, "tag": "", "sol": "√5 × √5 = 5, not 25. The others are correct: 9 × 3 = 27; 7; {2/3} × √(3 ÷ 6) = {2/3} × √{1/2} = 2 ÷ (3√2). (Also correct: 2√8 × 3√2 = 24 and 3√20 ÷ 3√5 = 2.)"}, {"kind": "blank", "p": "<b>Ex 5A · Q4(e–h, j)</b> · Work out the correct values.", "tag": "", "marks": "", "flat": [{"t": "e) 3√3 × 3√3 = __B1__", "a": {"B1": "27"}}, {"t": "f) √7 × √7 = __B1__", "a": {"B1": "7"}}, {"t": "g) √5 × √5 = __B1__", "a": {"B1": "5"}}, {"t": "h) 2√8 × 3√2 = __B1__", "a": {"B1": "24"}}, {"t": "j) 3√20 ÷ 3√5 = __B1__", "a": {"B1": "2"}}], "sol": "(3 × 3) × (√3 × √3) = 9 × 3 = 27: correct.\n√7 × √7 = 7: correct.\n√5 × √5 = 5, so “= 25” is wrong.\n6 × √16 = 6 × 4 = 24: correct.\n√(20 ÷ 5) = √4 = 2: correct. So the correct statements in Q4 are b, e, f, h, i and j."}, {"kind": "blank", "p": "<b>Ex 5A · Q5</b> · Find the simplest rationalising factor √n of each irrational number.", "tag": "", "marks": "", "flat": [{"t": "a) √10 → √__B1__", "a": {"B1": "10"}}, {"t": "b) √7 → √__B1__", "a": {"B1": "7"}}, {"t": "c) 2√11 → √__B1__", "a": {"B1": "11"}}, {"t": "d) −2√5 → √__B1__", "a": {"B1": "5"}}, {"t": "e) 10√3 → √__B1__", "a": {"B1": "3"}}], "sol": "√10 × √10 = 10.\n√7 × √7 = 7.\n2√11 × √11 = 22.\n−2√5 × √5 = −10.\n10√3 × √3 = 30."}]}, {"id": "s5", "label": "5.5 Real numbers", "sub": "Real numbers and the properties of operations on them", "slides": [{"kind": "mcq", "text": "<b>Try This · Q1</b> · Which example demonstrates the commutative property of multiplication for real numbers?", "opts": ["√2 + 3 = 3 + √2 = 3√2", "√2 × 3 = 3 × √2 = 3√2", "(√2 × 3) × 2 = √2 × (3 × 2) = 6√2", "√2 × (3 + 2) = 3√2 + 2√2 = 5√2"], "correct": 1, "tag": "", "sol": "Commutative property of multiplication: a × b = b × a. Changing the order of √2 and 3 does not change the product 3√2. (The second option is wrong as well as being about addition: √2 + 3 ≠ 3√2.)"}, {"kind": "blank", "p": "<b>Try This · Q2</b> · Solve (5 + 3) + 7 using the associative property of addition.", "tag": "", "marks": "", "flat": [{"t": "(5 + 3) + 7 = 5 + (3 + 7) = 5 + __B1__", "a": {"B1": "10"}}, {"t": "= __B1__", "a": {"B1": "15"}}], "sol": "Regroup: 3 + 7 = 10.\n5 + 10 = 15, the same as 8 + 7 = 15."}, {"kind": "blank", "p": "<b>Ex 5B · Q1(a, c, f, j)</b> · Fill in the boxes with the correct real numbers.", "tag": "", "marks": "", "flat": [{"t": "a) √11 + 2√11 = 2√11 + √__B1__", "a": {"B1": "11"}}, {"t": "c) 2√5 + (3√3 + 5) = (2√5 + __B1__√__B2__) + 5", "a": {"B1": "3", "B2": "3"}}, {"t": "f) 5√5(√7 + 2√3) = (5√5 × √7) + (__B1__√__B2__ × 2√3)", "a": {"B1": "5", "B2": "5"}}, {"t": "j) 2√5 + (__B1__√__B2__) = 0", "a": {"B1": "-2", "B2": "5"}}], "sol": "Commutative: √11 + 2√11 = 2√11 + √11.\nAssociative property of addition.\nDistributive property: 5√5 multiplies each term.\nAdditive inverse of 2√5 is −2√5."}, {"kind": "mcq", "text": "<b>Ex 5B · Q1(b)</b> · 4.5̅ + 3.56 = 3.56 + □. The box holds", "opts": ["3.56", "0", "8.11̅", "4.5̅"], "correct": 3, "tag": "", "sol": "Commutative property of addition: a + b = b + a, so the box holds 4.5̅ (= 4.555…)."}, {"kind": "mcq", "text": "<b>Ex 5B · Q1(d)</b> · 3.8̅ + (6.94 + 4.05) = (□ + 6.94) + 4.05. The box holds", "opts": ["6.94", "4.05", "10.99", "3.8̅"], "correct": 3, "tag": "", "sol": "Associative property of addition: a + (b + c) = (a + b) + c, so the box holds 3.8̅."}, {"kind": "blank", "p": "<b>Ex 5B · Q1(e, g, h, i)</b> · Fill in the boxes (type fractions like 1/2 or mixed numbers like 11 2/5).", "tag": "", "marks": "", "flat": [{"t": "e) {3/4} + ({2/5} + □) = ({3/4} + {2/5}) + {1/2}:  □ = __B1__", "a": {"B1": "1/2"}, "expr": "fl"}, {"t": "g) {1 2/5}({10 3/7} + □) = ({1 2/5} × {10 3/7}) + ({1 2/5} × {11 2/5}):  □ = __B1__", "a": {"B1": "57/5"}, "expr": "fl"}, {"t": "h) −{10 3/7} + □ = 0:  □ = __B1__", "a": {"B1": "73/7"}, "expr": "fl"}, {"t": "i) {1 2/5} × □ = 1:  □ = __B1__", "a": {"B1": "5/7"}, "expr": "fl"}], "sol": "Associative property of addition.\nDistributive property: the box is {11 2/5} = {57/5}.\nAdditive inverse of −{10 3/7} is {10 3/7} = {73/7}.\n{1 2/5} = {7/5}; its multiplicative inverse is {5/7}."}, {"kind": "mcq", "text": "<b>Ex 5B · Q2</b> · Is the sum of two real numbers always a real number?", "opts": ["Yes, but only when both numbers are rational", "No: √2 + √3 is not a real number because it cannot be simplified", "No: the sum of two irrational numbers is never real", "Yes: e.g. √2 + 3 and 2√3 + 5√3 = 7√3 are real (closure)"], "correct": 3, "tag": "", "sol": "Closure under addition: every sum of real numbers is a point on the number line, e.g. √2 + 3 ≈ 4.414 and √2 + √3 ≈ 3.146 are real even though they cannot be written as a single root."}, {"kind": "blank", "p": "<b>Ex 5B · Q3</b> · Does the order of multiplication matter for real numbers? Verify with a = √3 and b = √12.", "tag": "", "marks": "", "flat": [{"t": "a × b = √3 × √12 = __B1__", "a": {"B1": "6"}}, {"t": "b × a = √12 × √3 = __B1__", "a": {"B1": "6"}}, {"t": "Does the order matter? __B1__ (yes / no)", "a": {"B1": "no"}, "expr": "words"}], "sol": "√36 = 6.\n√36 = 6.\nBoth orders give 6: multiplication of real numbers is commutative, so the order does not matter."}, {"kind": "mcq", "text": "<b>Ex 5B · Q4</b> · Does the grouping of real numbers affect the result of addition or multiplication?", "opts": ["Yes for multiplication, but not for addition", "No: (√2 + 3) + 5 = √2 + (3 + 5) and (2 × √3) × 3 = 2 × (√3 × 3)", "No, but only for rational numbers, not for irrational numbers", "Yes: (√2 + 3) + 5 is different from √2 + (3 + 5)"], "correct": 1, "tag": "", "sol": "Associative property: both groupings give √2 + 8 for the sum and 6√3 for the product. This is true for all real numbers."}, {"kind": "blank", "p": "<b>Ex 5B · Q5</b> · Illustrate whether the closure property applies on subtraction of real numbers using {2 1/7} and −{3 2/5}.", "tag": "", "marks": "", "flat": [{"t": "{2 1/7} − (−{3 2/5}) = {15/7} + {17/5} = __B1__", "a": {"B1": "194/35"}, "expr": "fl"}, {"t": "Is the result a real number? __B1__ (yes / no)", "a": {"B1": "yes"}, "expr": "words"}], "sol": "{75/35} + {119/35} = {194/35} = {5 19/35}.\n{194/35} is rational, hence real: subtraction of real numbers is closed."}]}, {"id": "s6", "label": "Assessment A", "sub": "Knowing and understanding", "slides": [{"kind": "mcq", "text": "<b>Check-up · MCQ 1</b> · The square root of every positive non-perfect square number is a/an ______. (Choose the option that names the <i>type</i> of number: rational or irrational.)", "opts": ["irrational number", "zero", "positive number", "negative number"], "correct": 0, "tag": "", "sol": "√2, √3, √5, … never end or repeat, so they are irrational. (They are also positive, but “irrational” is the property that describes every such root and is the expected answer.)"}, {"kind": "blank", "p": "<b>Check-up · Q4(a–c)</b> · Simplify.", "tag": "", "marks": "", "flat": [{"t": "a) 2√5 + 4√5 = __B1__√__B2__", "a": {"B1": "6", "B2": "5"}}, {"t": "b) 10√3 − 3√3 = __B1__√__B2__", "a": {"B1": "7", "B2": "3"}}, {"t": "c) √11 × √7 = √__B1__", "a": {"B1": "77"}}], "sol": "(2 + 4)√5 = 6√5.\n(10 − 3)√3 = 7√3.\n√(11 × 7) = √77."}, {"kind": "mcq", "text": "<b>Check-up · MCQ 2</b> · Which of the following is an irrational number?", "opts": ["1.555…", "√49", "0.45̅", "√10"], "correct": 3, "tag": "", "sol": "√49 = 7; 1.555… and 0.45̅ are recurring decimals (rational). 10 is not a perfect square, so √10 is irrational."}, {"kind": "blank", "p": "<b>Check-up · Q4(d, e)</b> · Simplify.", "tag": "", "marks": "", "flat": [{"t": "d) 2√3 × 5√2 = __B1__√__B2__", "a": {"B1": "10", "B2": "6"}}, {"t": "e) 7√21 ÷ √7 = __B1__√__B2__", "a": {"B1": "7", "B2": "3"}}], "sol": "(2 × 5)√(3 × 2) = 10√6.\n7√(21 ÷ 7) = 7√3."}, {"kind": "mcq", "text": "<b>Check-up · MCQ 3</b> · What is the decimal representation of the irrational number π (pi) up to three decimal places?", "opts": ["1.732", "1.414", "2.718", "3.142"], "correct": 3, "tag": "", "sol": "π = 3.14159… ≈ 3.142. (2.718 ≈ e, 1.414 ≈ √2, 1.732 ≈ √3.)"}, {"kind": "blank", "p": "<b>Check-up · Q6</b> · Find the simplest rationalising factor √n of each irrational number.", "tag": "", "marks": "", "flat": [{"t": "a) −2√8 → √__B1__", "a": {"B1": "2"}, "accept": ["8"]}, {"t": "b) √17 → √__B1__", "a": {"B1": "17"}}, {"t": "c) 3√15 → √__B1__", "a": {"B1": "15"}}, {"t": "d) 4√5 → √__B1__", "a": {"B1": "5"}}, {"t": "e) 7√3 → √__B1__", "a": {"B1": "3"}}], "sol": "−2√8 = −4√2, and −4√2 × √2 = −8 (√8 also works: −2√8 × √8 = −16).\n√17 × √17 = 17.\n3√15 × √15 = 45.\n4√5 × √5 = 20.\n7√3 × √3 = 21."}, {"kind": "blank", "p": "<b>Check-up · Q8</b> · a = 2 + √5, b = 2 − √5, x = a + b, y = a − b. Find whether x and y are rational or irrational.", "tag": "", "marks": "", "flat": [{"t": "x = a + b = __B1__", "a": {"B1": "4"}}, {"t": "x is __B1__", "a": {"B1": "rational"}, "expr": "words"}, {"t": "y = a − b = __B1__√__B2__", "a": {"B1": "2", "B2": "5"}}, {"t": "y is __B1__", "a": {"B1": "irrational"}, "expr": "words"}], "sol": "(2 + √5) + (2 − √5) = 4.\n4 = {4/1}: rational.\n(2 + √5) − (2 − √5) = 2√5.\nNon-zero rational × irrational: irrational."}, {"kind": "mcq", "text": "Which number is rational?", "opts": ["√8 ÷ √2", "√3 × √2", "√8 + √2", "π + 1"], "correct": 0, "tag": "", "sol": "√8 ÷ √2 = √4 = 2. The others are 3√2, √6 and π + 1, all irrational."}]}, {"id": "s7", "label": "Assessment B", "sub": "Investigating patterns", "slides": [{"kind": "blank", "p": "<b>Check-up · Q7</b> · Plot these irrational numbers on the number line: 2 + √5, −3√2, −8.1134…, π + 3, √2 + 6. Between which two consecutive integers does each lie?", "tag": "", "marks": "", "flat": [{"t": "2 + √5 lies between __B1__ and __B2__ (smaller first)", "a": {"B1": "4", "B2": "5"}}, {"t": "−3√2 lies between __B1__ and __B2__ (smaller first)", "a": {"B1": "-5", "B2": "-4"}}, {"t": "−8.1134… lies between __B1__ and __B2__ (smaller first)", "a": {"B1": "-9", "B2": "-8"}}, {"t": "π + 3 lies between __B1__ and __B2__ (smaller first)", "a": {"B1": "6", "B2": "7"}}, {"t": "√2 + 6 lies between __B1__ and __B2__ (smaller first)", "a": {"B1": "7", "B2": "8"}}], "sol": "√5 ≈ 2.236, so 2 + √5 ≈ 4.236.\n−3√2 = −√18 and 16 < 18 < 25, so −3√2 ≈ −4.243.\n−8.1134… is just left of −8.\nπ ≈ 3.142, so π + 3 ≈ 6.142.\n√2 ≈ 1.414, so √2 + 6 ≈ 7.414."}, {"kind": "mcq", "text": "<b>Check-up · Q7</b> · The five numbers are marked P, Q, R, S and T on the number line. Which point is π + 3?", "opts": ["R", "T", "S", "Q"], "correct": 2, "tag": "", "sol": "In order from left to right: −8.1134… (P), −3√2 ≈ −4.24 (Q), 2 + √5 ≈ 4.24 (R), π + 3 ≈ 6.14 (S), √2 + 6 ≈ 7.41 (T).", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 360 80\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><line class=\"ln\" x1=\"8.0\" y1=\"38.0\" x2=\"352.0\" y2=\"38.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><line x1=\"16.0\" y1=\"33\" x2=\"16.0\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"35.3\" y1=\"33\" x2=\"35.3\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"54.6\" y1=\"33\" x2=\"54.6\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"73.9\" y1=\"33\" x2=\"73.9\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"93.2\" y1=\"30\" x2=\"93.2\" y2=\"46\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text class=\"lb\" x=\"93.2\" y=\"58.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">−5</text><line x1=\"112.5\" y1=\"33\" x2=\"112.5\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"131.8\" y1=\"33\" x2=\"131.8\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"151.1\" y1=\"33\" x2=\"151.1\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"170.4\" y1=\"33\" x2=\"170.4\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"189.6\" y1=\"30\" x2=\"189.6\" y2=\"46\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text class=\"lb\" x=\"189.6\" y=\"58.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><line x1=\"208.9\" y1=\"33\" x2=\"208.9\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"228.2\" y1=\"33\" x2=\"228.2\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"247.5\" y1=\"33\" x2=\"247.5\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"266.8\" y1=\"33\" x2=\"266.8\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"286.1\" y1=\"30\" x2=\"286.1\" y2=\"46\" style=\"stroke:var(--ink);stroke-width:1.6\"/><text class=\"lb\" x=\"286.1\" y=\"58.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><line x1=\"305.4\" y1=\"33\" x2=\"305.4\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"324.7\" y1=\"33\" x2=\"324.7\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><line x1=\"344.0\" y1=\"33\" x2=\"344.0\" y2=\"43\" style=\"stroke:var(--ink);stroke-width:1\"/><circle cx=\"33.1\" cy=\"38\" r=\"4.5\" style=\"fill:var(--danger)\"/><text class=\"al\" x=\"33.1\" y=\"23.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">P</text><circle cx=\"107.8\" cy=\"38\" r=\"4.5\" style=\"fill:var(--danger)\"/><text class=\"al\" x=\"107.8\" y=\"23.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Q</text><circle cx=\"271.4\" cy=\"38\" r=\"4.5\" style=\"fill:var(--danger)\"/><text class=\"al\" x=\"271.4\" y=\"23.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">R</text><circle cx=\"308.1\" cy=\"38\" r=\"4.5\" style=\"fill:var(--danger)\"/><text class=\"al\" x=\"308.1\" y=\"23.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">S</text><circle cx=\"332.7\" cy=\"38\" r=\"4.5\" style=\"fill:var(--danger)\"/><text class=\"al\" x=\"332.7\" y=\"23.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">T</text></svg>"}, {"kind": "blank", "p": "<b>Check-up · Brain Teaser</b> · Observe the figure. What integers should replace A and B? (Hint: look at the two sector numbers next to each outer circle, e.g. next to 2 are 7 and √16, and compare with the circle opposite.)", "tag": "", "marks": "", "flat": [{"t": "B = __B1__", "a": {"B1": "8"}}, {"t": "A = __B1__", "a": {"B1": "17"}}], "sol": "Next to 11 are −6 and B; the opposite circle is 2: −6 + B = 2, so B = 8.\nNext to 5 are B = 8 and 9; the opposite circle is A: A = 8 + 9 = 17. (Check: next to A are √16 = 4 and 1, sum 5, the opposite circle.)", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 320 300\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><circle cx=\"160\" cy=\"150\" r=\"78\" style=\"fill:none;stroke:var(--ink);stroke-width:1.4\"/><line class=\"ln\" x1=\"160.0\" y1=\"150.0\" x2=\"160.0\" y2=\"49.0\"/><circle cx=\"160.0\" cy=\"32.0\" r=\"17\" style=\"fill:none;stroke:var(--ink);stroke-width:1.4\"/><text class=\"lb\" x=\"160.0\" y=\"32.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><line class=\"ln\" x1=\"160.0\" y1=\"150.0\" x2=\"231.4\" y2=\"78.6\"/><circle cx=\"243.4\" cy=\"66.6\" r=\"17\" style=\"fill:none;stroke:var(--ink);stroke-width:1.4\"/><text class=\"lb\" x=\"243.4\" y=\"66.6\" text-anchor=\"middle\" dominant-baseline=\"middle\">A</text><line class=\"ln\" x1=\"160.0\" y1=\"150.0\" x2=\"261.0\" y2=\"150.0\"/><circle cx=\"278.0\" cy=\"150.0\" r=\"17\" style=\"fill:none;stroke:var(--ink);stroke-width:1.4\"/><text class=\"lb\" x=\"278.0\" y=\"150.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">16</text><line class=\"ln\" x1=\"160.0\" y1=\"150.0\" x2=\"231.4\" y2=\"221.4\"/><circle cx=\"243.4\" cy=\"233.4\" r=\"17\" style=\"fill:none;stroke:var(--ink);stroke-width:1.4\"/><text class=\"lb\" x=\"243.4\" y=\"233.4\" text-anchor=\"middle\" dominant-baseline=\"middle\">14</text><line class=\"ln\" x1=\"160.0\" y1=\"150.0\" x2=\"160.0\" y2=\"251.0\"/><circle cx=\"160.0\" cy=\"268.0\" r=\"17\" style=\"fill:none;stroke:var(--ink);stroke-width:1.4\"/><text class=\"lb\" x=\"160.0\" y=\"268.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">11</text><line class=\"ln\" x1=\"160.0\" y1=\"150.0\" x2=\"88.6\" y2=\"221.4\"/><circle cx=\"76.6\" cy=\"233.4\" r=\"17\" style=\"fill:none;stroke:var(--ink);stroke-width:1.4\"/><text class=\"lb\" x=\"76.6\" y=\"233.4\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><line class=\"ln\" x1=\"160.0\" y1=\"150.0\" x2=\"59.0\" y2=\"150.0\"/><circle cx=\"42.0\" cy=\"150.0\" r=\"17\" style=\"fill:none;stroke:var(--ink);stroke-width:1.4\"/><text class=\"lb\" x=\"42.0\" y=\"150.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">8</text><line class=\"ln\" x1=\"160.0\" y1=\"150.0\" x2=\"88.6\" y2=\"78.6\"/><circle cx=\"76.6\" cy=\"66.6\" r=\"17\" style=\"fill:none;stroke:var(--ink);stroke-width:1.4\"/><text class=\"lb\" x=\"76.6\" y=\"66.6\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"lb\" x=\"179.1\" y=\"103.8\" text-anchor=\"middle\" dominant-baseline=\"middle\">√16</text><text class=\"lb\" x=\"206.2\" y=\"130.9\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><text class=\"lb\" x=\"206.2\" y=\"169.1\" text-anchor=\"middle\" dominant-baseline=\"middle\">7</text><text class=\"lb\" x=\"179.1\" y=\"196.2\" text-anchor=\"middle\" dominant-baseline=\"middle\">−6</text><text class=\"lb\" x=\"140.9\" y=\"196.2\" text-anchor=\"middle\" dominant-baseline=\"middle\">B</text><text class=\"lb\" x=\"113.8\" y=\"169.1\" text-anchor=\"middle\" dominant-baseline=\"middle\">9</text><text class=\"lb\" x=\"113.8\" y=\"130.9\" text-anchor=\"middle\" dominant-baseline=\"middle\">7</text><text class=\"lb\" x=\"140.9\" y=\"103.8\" text-anchor=\"middle\" dominant-baseline=\"middle\">7</text></svg>"}, {"kind": "mcq", "text": "Look at √1, √2, √3, …, √20. How many of them are rational?", "opts": ["10", "2", "4", "5"], "correct": 2, "tag": "", "sol": "Only perfect squares have rational roots: √1 = 1, √4 = 2, √9 = 3, √16 = 4. That is 4 numbers."}, {"kind": "blank", "p": "Look for a pattern in these products.", "tag": "", "marks": "", "flat": [{"t": "√2 × √8 = __B1__", "a": {"B1": "4"}}, {"t": "√3 × √12 = __B1__", "a": {"B1": "6"}}, {"t": "√5 × √20 = __B1__", "a": {"B1": "10"}}, {"t": "√n × √(4n) = __B1__ × n", "a": {"B1": "2"}}], "sol": "√16 = 4.\n√36 = 6.\n√100 = 10.\n√(4n<sup>2</sup>) = 2n: the product of two irrational numbers can be rational."}, {"kind": "mcq", "text": "The decimal 0.101001000100001… (one more 0 each time) is", "opts": ["irrational, because it never ends and never repeats", "rational, because it only uses the digits 0 and 1", "irrational, because it is less than 1", "rational, because the pattern is predictable"], "correct": 0, "tag": "", "sol": "A pattern is not the same as a repeating block. No block of digits repeats, so the number is irrational."}, {"kind": "blank", "p": "In the square-root spiral each new triangle has one side of length 1 and the other side equal to the previous hypotenuse.", "tag": "", "marks": "", "flat": [{"t": "The hypotenuse after √7 is √__B1__", "a": {"B1": "8"}}, {"t": "Simplified, this is __B1__√__B2__", "a": {"B1": "2", "B2": "2"}}, {"t": "The first hypotenuse in the spiral that is a whole number is √__B1__", "a": {"B1": "4"}}], "sol": "(√7)<sup>2</sup> + 1<sup>2</sup> = 8, so the next hypotenuse is √8.\n√8 = √(2 × 2 × 2) = 2√2.\nStarting from √2, the hypotenuses are √2, √3, √4 = 2, … so √4 is the first whole number."}]}, {"id": "s8", "label": "Assessment C", "sub": "Communicating", "slides": [{"kind": "mcq", "text": "<b>Check-up · Q5</b> · To mark √7 on a number line by geometrical construction, after locating √6 at point P you should", "opts": ["draw PQ = 1 unit perpendicular to OP at P, then an arc with centre O and radius OQ", "draw PQ = 1 unit along the number line, then an arc with centre Q", "draw an arc with centre O and radius 7 units", "draw PQ = 7 units perpendicular to OP, then an arc with centre P"], "correct": 0, "tag": "", "sol": "OQ<sup>2</sup> = OP<sup>2</sup> + PQ<sup>2</sup> = (√6)<sup>2</sup> + 1<sup>2</sup> = 7, so OQ = √7. The arc centred at O carries this length onto the number line."}, {"kind": "blank", "p": "<b>Check-up · Q5</b> · Complete the working for the construction of √7.", "tag": "", "marks": "", "flat": [{"t": "(√6)<sup>2</sup> + 1<sup>2</sup> = __B1__", "a": {"B1": "7"}}, {"t": "√7 lies between __B1__ and __B2__ (smaller first)", "a": {"B1": "2", "B2": "3"}}], "sol": "6 + 1 = 7, so the hypotenuse is √7.\n4 < 7 < 9, so 2 < √7 < 3 (√7 ≈ 2.646)."}, {"kind": "mcq", "text": "Rohit writes √5 + √2 = √7. Which reply is correct?", "opts": ["No: √5 and √2 are unlike, so their sum cannot be written as one root", "No: the numbers in front add, so the answer is 2√7", "Yes: when adding square roots, add the numbers under the roots", "Yes: by closure, any sum of roots can be written as one root"], "correct": 0, "tag": "", "sol": "Only like irrational numbers can be added. Checking with decimals: √5 + √2 ≈ 2.236 + 1.414 = 3.650, while √7 ≈ 2.646, so √5 + √2 ≠ √7."}, {"kind": "blank", "p": "<b>Check-up · Q9</b> · Illustrate the closure property of addition of real numbers using √7 and 2√7.", "tag": "", "marks": "", "flat": [{"t": "√7 + 2√7 = __B1__√__B2__", "a": {"B1": "3", "B2": "7"}}, {"t": "Is 3√7 a real number? __B1__ (yes / no)", "a": {"B1": "yes"}, "expr": "words"}], "sol": "(1 + 2)√7 = 3√7.\n3√7 ≈ 7.94 is a point on the number line, so it is a real number: addition of real numbers is closed."}, {"kind": "mcq", "text": "<b>Check-up · Q10</b> · Is addition of real numbers commutative? Which answer explains it correctly?", "opts": ["Yes: √2 + 5 = 5 + √2, and in general a + b = b + a for real a, b", "Yes, but only when both numbers are rational", "No: changing the order of an irrational sum changes its value", "No: √2 + 5 = 5√2 but 5 + √2 = √7"], "correct": 0, "tag": "", "sol": "Changing the order of two addends never changes the sum; √2 + 5 ≈ 6.414 either way."}, {"kind": "blank", "p": "Complete the statements.", "tag": "", "marks": "", "flat": [{"t": "Numbers whose decimals never end and never repeat are called __B1__ numbers.", "a": {"B1": "irrational"}, "expr": "words"}, {"t": "Rational and irrational numbers together form the __B1__ numbers.", "a": {"B1": "real"}, "expr": "words"}, {"t": "If the product of two irrational numbers is rational, each is a __B1__ factor of the other.", "a": {"B1": "rationalising"}, "expr": "words", "accept": ["rationalizing"]}], "sol": "Definition of irrational numbers.\nReal numbers = rational ∪ irrational.\nDefinition of rationalising factor."}, {"kind": "mcq", "text": "Which statement is written correctly?", "opts": ["√5 × √5 = 25, because 5 × 5 = 25", "√18 = 9√2, because 18 = 9 × 2", "2√3 + 3√2 = 5√5, because 2 + 3 = 5", "3√3 × 3√3 = 27, because 3 × 3 = 9 and √3 × √3 = 3"], "correct": 3, "tag": "", "sol": "9 × 3 = 27. The others should be √5 × √5 = 5, 2√3 + 3√2 cannot be simplified, and √18 = 3√2."}]}, {"id": "s9", "label": "Assessment D", "sub": "Applying mathematics in real-life contexts", "slides": [{"kind": "mcq", "text": "<b>Check-up · Case study Q11(a)</b> · Somya has a square piece of cardboard with an area of 36 sq. cm and wants the length of each side. Which measurement of the square does she use to find the length of each side?", "opts": ["Volume", "Area", "Diagonal", "Perimeter"], "correct": 1, "tag": "", "sol": "Area of a square = side × side, so side = √area = √36 = 6 cm. The area is the measurement she uses."}, {"kind": "mcq", "text": "<b>Check-up · Case study Q11(b)</b> · Somya calculates that each side is 6 cm long. What is the square root of the area of the cardboard?", "opts": ["√36", "√12", "√6", "√72"], "correct": 0, "tag": "", "sol": "The area is 36 sq. cm, so its square root is √36 = 6."}, {"kind": "blank", "p": "<b>Check-up · Everyday Maths Q12</b> · Sumit installs a circular flowerbed of radius 7 m. Calculate the area using A = πr<sup>2</sup> with π ≈ 3.14159. Give the answer to three decimal places.", "tag": "", "marks": "", "flat": [{"t": "A ≈ 3.14159 × 49 = __B1__ m<sup>2</sup>", "a": {"B1": "153.938"}, "expr": "dec"}], "sol": "r<sup>2</sup> = 49; 3.14159 × 49 = 153.93791 ≈ 153.938 m<sup>2</sup>."}, {"kind": "mcq", "text": "<b>Check-up · Case study Q11(c)</b> · Is the square root of the area of the given cardboard a rational or irrational number?", "opts": ["It depends on the size of the square", "Cannot be determined", "Irrational", "Rational"], "correct": 3, "tag": "", "sol": "√36 = 6 = {6/1}, which is rational."}, {"kind": "mcq", "text": "<b>Check-up · Everyday Maths Q12</b> · Is the area of Sumit’s flowerbed a rational or irrational number?", "opts": ["Irrational: every area measured in square metres is irrational", "Rational: 153.93791 is a decimal with an end", "Rational: the radius 7 m and 49 are whole numbers", "Irrational: the exact area 49π m² is a rational number times π"], "correct": 3, "tag": "", "sol": "49 × π is (non-zero rational) × irrational, so the exact area is irrational. Using π ≈ 3.14159 gives a terminating decimal, which is only an approximation."}, {"kind": "blank", "p": "<b>Check-up · Everyday Maths Q13</b> · Raghav’s ramp is a right triangle with legs 3 m and 4 m. Use c<sup>2</sup> = a<sup>2</sup> + b<sup>2</sup>.", "tag": "", "marks": "", "flat": [{"t": "c<sup>2</sup> = __B1__", "a": {"B1": "25"}}, {"t": "Hypotenuse c = __B1__ m", "a": {"B1": "5"}}, {"t": "The length is __B1__", "a": {"B1": "rational"}, "expr": "words"}], "sol": "3<sup>2</sup> + 4<sup>2</sup> = 9 + 16 = 25.\nc = √25 = 5 m.\n5 = {5/1} is rational."}, {"kind": "blank", "p": "<b>Check-up · Cross-Curricular (a, b)</b> · Priya’s personal record for the javelin throw is 2√576 m and her goal is exactly 50 m.", "tag": "", "marks": "", "flat": [{"t": "a) 2√576 = __B1__ m", "a": {"B1": "48"}}, {"t": "a) Additional distance needed = __B1__ m", "a": {"B1": "2"}}, {"t": "a) This distance is __B1__ (rational / irrational)", "a": {"B1": "rational"}, "expr": "words"}, {"t": "b) A practice throw reaches 49.8 m. Difference from the goal = __B1__ m", "a": {"B1": "0.2"}, "expr": "dec"}, {"t": "b) The difference is __B1__ (rational / irrational)", "a": {"B1": "rational"}, "expr": "words"}], "sol": "√576 = 24, so 2 × 24 = 48 m.\n50 − 48 = 2 m.\n2 = {2/1} is rational.\n50 − 49.8 = 0.2 m.\n0.2 = {1/5} is a terminating decimal: rational."}, {"kind": "mcq", "text": "<b>Check-up · Being Indian (a)</b> · The Statue of Unity is 182 m tall. Is this height a rational or irrational number?", "opts": ["Rational: 182 is an even number", "Rational: 182 = {182/1}", "Irrational: 182 is not a perfect square", "Irrational: heights are measured, not counted"], "correct": 1, "tag": "", "sol": "Every integer n can be written as {n/1}, so 182 is rational. Being a perfect square matters only for square roots."}, {"kind": "blank", "p": "<b>Check-up · Being Indian (b)</b> · Calculate the square root of the height of the Statue of Unity (182) to three decimal places.", "tag": "", "marks": "", "flat": [{"t": "√182 ≈ __B1__", "a": {"B1": "13.491"}, "expr": "dec"}, {"t": "√182 is __B1__", "a": {"B1": "irrational"}, "expr": "words"}], "sol": "13<sup>2</sup> = 169 and 14<sup>2</sup> = 196; √182 = 13.4907… ≈ 13.491.\n182 is not a perfect square, so √182 is irrational."}]}];
/* ================= build slide lists ================= */
var SLIDES = {}; SECTIONS.forEach(function(sec){ SLIDES[sec.id]=sec.slides; });
var TAB_DEFS = SECTIONS.map(function(sec){ return {id:sec.id, label:sec.label, sub:sec.sub}; });

/* ================= state ================= */
function blankItem(slide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    return {status:'unanswered', attempts:0, choice:undefined};
  }
  return {status:'unanswered', curStep:0, stepStates: slide.flat.map(function(){ return {status:'unanswered', attempts:0, inputs:{}}; })};
}
function defaultState(){
  var s={tabs:{}};
  TAB_DEFS.forEach(function(td){
    s.tabs[td.id] = { idx:0, maxReached:0, items: SLIDES[td.id].map(function(sl){ return blankItem(sl); }) };
  });
  return s;
}
var appState = {mode:null, learning:null, quiz:null};
var state = null;      // alias for appState[appState.mode]
var MODE = null;
var activeTab=TAB_DEFS[0].id;

function setMode(m){
  appState.mode = m;
  if(!appState[m]) appState[m] = defaultState();
  state = appState[m];
  MODE = m;
}
/* ================= student accounts (saved on this device) ================= */
var SHEET_KEY='sopaan-c8-ch5';
var ACC_KEY='sopaan-students-v1';
var storageOK=true;
var MEM={};
function lsGet(k){ var r=null; try{ r=localStorage.getItem(k); }catch(e){ storageOK=false; }
  if(r===null||r===undefined) r=MEM[k]||null; try{ return r?JSON.parse(r):null; }catch(e){ return null; } }
function lsSet(k,v){ var j=JSON.stringify(v); MEM[k]=j; try{ localStorage.setItem(k,j); return true; }catch(e){ storageOK=false; return false; } }
try{ localStorage.setItem('sopaan-probe','1'); localStorage.removeItem('sopaan-probe'); }catch(e){ storageOK=false; }
function hashPin(pin,salt){ var h=2166136261, str=salt+'|'+pin; for(var i=0;i<str.length;i++){ h^=str.charCodeAt(i); h=Math.imul(h,16777619)>>>0; } return h.toString(36); }
function accKey(name,roll){ return (name.trim().toLowerCase().replace(/\s+/g,' ')+'#'+roll.trim().toLowerCase()); }
function accounts(){ return lsGet(ACC_KEY)||{students:{}}; }
var student=null; // {key,name,roll}
var records=[];   // finished-tab history for this student on this sheet
function progKey(){ return SHEET_KEY+'::'+student.key; }

function loadState(){
  appState = {mode:null, learning:null, quiz:null}; records=[]; activeTab=TAB_DEFS[0].id;
  var saved=lsGet(progKey());
  if(!saved) return;
  try{
    ['learning','quiz'].forEach(function(m){
      if(saved[m] && saved[m].tabs){
        var fresh = defaultState();
        TAB_DEFS.forEach(function(td){
          if(saved[m].tabs[td.id] && saved[m].tabs[td.id].items && saved[m].tabs[td.id].items.length===SLIDES[td.id].length){
            fresh.tabs[td.id] = saved[m].tabs[td.id];
          }
        });
        appState[m] = fresh;
      }
    });
    if(saved.mode==='learning' || saved.mode==='quiz') appState.mode = saved.mode;
    if(saved.activeTab && TAB_DEFS.some(function(t){ return t.id===saved.activeTab; })) activeTab = saved.activeTab;
    if(Array.isArray(saved.records)) records = saved.records;
  }catch(e){}
}
function saveState(){
  if(!student) return;
  lsSet(progKey(), {mode:appState.mode, learning:appState.learning, quiz:appState.quiz, activeTab:activeTab, records:records, updated:Date.now()});
  var acc=accounts(); if(acc.students[student.key]){ acc.students[student.key].last=Date.now(); lsSet(ACC_KEY,acc); }
}
function addRecord(mode, tabId, correct, revealed, skipped, total){
  records.unshift({at:Date.now(), mode:mode, tab:tabId, correct:correct, revealed:revealed, skipped:skipped, total:total});
  if(records.length>60) records.length=60;
  saveState();
}
function fmtDate(ms){ try{ return new Date(ms).toLocaleString(undefined,{day:'numeric',month:'short',hour:'2-digit',minute:'2-digit'}); }catch(e){ return ''; } }

function renderWho(){
  var el=document.getElementById('whoBar');
  if(!student){ el.hidden=true; el.innerHTML=''; return; }
  el.hidden=false;
  el.innerHTML='Signed in as <b>'+esc(student.name)+'</b> · Roll '+esc(student.roll)+
    ' <button id="btnRecord">My record</button> <button id="btnSignOut">Sign out</button>';
  document.getElementById('btnRecord').addEventListener('click', renderRecord);
  document.getElementById('btnSignOut').addEventListener('click', signOut);
}
function signOut(){
  saveState(); student=null; state=null; MODE=null;
  var acc=accounts(); delete acc.current; lsSet(ACC_KEY,acc);
  document.getElementById('modePill').hidden=true;
  renderWho(); renderLogin();
}
function signIn(key){
  var acc=accounts(); var st=acc.students[key]; if(!st) return;
  student={key:key, name:st.name, roll:st.roll};
  acc.current=key; st.last=Date.now(); lsSet(ACC_KEY,acc);
  loadState(); renderWho();
  if(appState.mode==='learning' || appState.mode==='quiz'){
    setMode(appState.mode); document.getElementById('modePill').hidden=false; updateModePill();
    showChrome(true); buildTabbar(); renderSlide();
    showToast('Welcome back, '+st.name.split(' ')[0]+'. Picking up where you left off.');
  } else {
    renderModePicker();
  }
}
function renderLogin(msg){
  showChrome(false);
  var acc=accounts(); var keys=Object.keys(acc.students).sort(function(a,b){ return (acc.students[b].last||0)-(acc.students[a].last||0); });
  var h='<div class="login-card"><h2>Student sign-in</h2>'+
    '<p class="lead">Sign in to save your answers, see your record and continue where you left off next time.</p>';
  if(!storageOK) h+='<div class="login-err">This browser is blocking saved data (for example, a private window). You can still practise, but progress will not be kept after you close the page.</div>';
  if(msg) h+='<div class="login-err">'+esc(msg)+'</div>';
  if(keys.length){
    h+='<div class="known"><span class="known-label">Continue as</span>';
    keys.slice(0,6).forEach(function(k){ var st=acc.students[k];
      h+='<button class="known-btn" data-k="'+esc(k)+'"><span>'+esc(st.name)+' <small>· Roll '+esc(st.roll)+'</small></span><small>'+(st.last?'Last active '+fmtDate(st.last):'')+'</small></button>'; });
    h+='</div>';
  }
  h+='<form id="loginForm" novalidate>'+
    '<div class="fld"><label for="lgName">Full name</label><input id="lgName" autocomplete="name" required></div>'+
    '<div class="fld-row"><div class="fld"><label for="lgRoll">Roll no.</label><input id="lgRoll" required></div>'+
    '<div class="fld"><label for="lgPin">4-digit PIN</label><input id="lgPin" type="password" inputmode="numeric" maxlength="4" autocomplete="off" required></div></div>'+
    '<button class="btn btn-primary" type="submit" style="width:100%;">Sign in</button>'+
    '<p class="login-note">New here? Enter your name, roll no. and a PIN you will remember, and your profile is created. Progress is saved on this device, so use the same device and browser to continue.</p>'+
    '</form></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  wrap.querySelectorAll('.known-btn').forEach(function(b){
    b.addEventListener('click', function(){
      var st=accounts().students[b.dataset.k];
      document.getElementById('lgName').value=st.name; document.getElementById('lgRoll').value=st.roll;
      document.getElementById('lgPin').focus();
    });
  });
  document.getElementById('loginForm').addEventListener('submit', function(e){
    e.preventDefault();
    var name=document.getElementById('lgName').value.trim(), roll=document.getElementById('lgRoll').value.trim(), pin=document.getElementById('lgPin').value.trim();
    if(!name||!roll){ renderLoginErr('Enter your name and roll no.'); return; }
    if(!/^\d{4}$/.test(pin)){ renderLoginErr('Your PIN must be exactly 4 digits.'); return; }
    var k=accKey(name,roll); var acc=accounts();
    if(acc.students[k]){
      if(acc.students[k].pin!==hashPin(pin,k)){ renderLoginErr('That PIN does not match this name and roll no. Try again.'); return; }
    } else {
      acc.students[k]={name:name.replace(/\s+/g,' '), roll:roll, pin:hashPin(pin,k), created:Date.now()};
      lsSet(ACC_KEY,acc);
    }
    signIn(k);
  });
}
function renderLoginErr(m){
  var n=document.getElementById('lgName').value, r=document.getElementById('lgRoll').value;
  renderLogin(m); document.getElementById('lgName').value=n; document.getElementById('lgRoll').value=r; document.getElementById('lgPin').focus();
}
function tabSummary(m){
  var st=appState[m]; if(!st) return null;
  return TAB_DEFS.map(function(td){
    var items=st.tabs[td.id].items, n=items.length;
    var c=items.filter(function(i){return i.status==='correct';}).length;
    var done=items.filter(function(i){return i.status!=='unanswered';}).length;
    return {label:td.label, n:n, done:done, correct:c};
  });
}
function renderRecord(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+' · Real Numbers</p>';
  ['learning','quiz'].forEach(function(m){
    var sum=tabSummary(m);
    h+='<h3>'+(m==='learning'?'📘 Learning Sheet':'📝 Quiz Mode')+'</h3>';
    if(!sum){ h+='<p class="rec-empty">Not started yet.</p>'; return; }
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>Section</th><th>Progress</th><th>Correct first time</th></tr></thead><tbody>';
    sum.forEach(function(r){ var pct=Math.round(r.done/r.n*100);
      h+='<tr><td>'+r.label+'</td><td><span class="rec-bar"><i style="width:'+pct+'%"></i></span>'+r.done+' / '+r.n+'</td><td>'+(m==='quiz'?'—':r.correct+' / '+r.n)+'</td></tr>'; });
    h+='</tbody></table></div>';
  });
  h+='</div><div class="rec-card"><h3>Finished sections</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sections finished yet. Each time you finish a tab, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>When</th><th>Mode</th><th>Section</th><th>Score</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+(r.mode==='learning'?' <span class="rec-empty">('+r.revealed+' revealed, '+r.skipped+' skipped)</span>':'')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){
    if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker();
  });
  window.scrollTo({top:0});
}

/* ================= tab bar ================= */
function buildTabbar(){
  var el=document.getElementById('tabbar');
  el.innerHTML = '<button class="tab-btn'+(activeTab==='theory'?' active':'')+'" data-tab="theory">Theory<span class="tab-count">notes</span></button>' + TAB_DEFS.map(function(t){
    return '<button class="tab-btn'+(t.id===activeTab?' active':'')+'" data-tab="'+t.id+'">'+t.label+'<span class="tab-count">'+SLIDES[t.id].length+'</span></button>';
  }).join('') + '<button class="tab-btn'+(activeTab==='report'?' active':'')+'" data-tab="report">📊 Report<span class="tab-count">pie</span></button>';
  el.querySelectorAll('.tab-btn').forEach(function(btn){
    btn.addEventListener('click', function(){ activeTab=btn.dataset.tab; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  });
}

/* ================= rendering ================= */
function canProceed(item){ return item.status==='correct'||item.status==='revealed'||item.status==='skipped'; }

function renderSlide(){
  if(!state.tabs[activeTab]){ activeTab=TAB_DEFS[0].id; }
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  if(ts.idx>=slides.length||ts.idx<0) ts.idx=0;
  var idx = ts.idx;
  var slide = slides[idx];
  var item = ts.items[idx];

  var tdef=TAB_DEFS.find(function(t){return t.id===activeTab;});
  document.getElementById('spLabel').textContent = tdef.label+' · Question '+(idx+1)+' of '+slides.length;
  document.getElementById('secSub').textContent = tdef.label+' — '+tdef.sub;
  document.getElementById('spFill').style.width = Math.round(((idx)/(Math.max(slides.length-1,1)))*100)+'%';

  var h='<div class="qcard">';
  if(slide.kind==='mcq' || slide.kind==='ar'){
    h += renderChoiceBody(slide, item, idx);
  } else {
    h += renderBlankBody(slide, item, idx);
  }
  h += '<div class="feedback" id="feedbackBox"></div>';
  if(MODE==='learning' && (item.status==='correct'||item.status==='revealed')) h += solutionHTML(slide);
  h += '</div>';

  document.getElementById('wrap').innerHTML = h;
  wireSlideEvents(slide, item, idx);
  restoreFeedback(item);
  renderNavbar(item);
  updateFab();
  saveState();
}

function solutionHTML(slide){
  if(!slide.sol) return '';
  return '<div class="solution"><div class="sol-h">Solution</div>'+slide.sol.split('\n').map(function(l){ return '<div class="sol-line">'+fr(esc(l))+'</div>'; }).join('')+'</div>';
}
var LETTERS=['a','b','c','d','e','f'];
function chosenHTML(slide,item){
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(item.choice===undefined) return '';
  var ok=item.choice===slide.correct;
  var h='<div class="chosen '+(ok?'ok':'bad')+'"><b>Your answer:</b> ('+LETTERS[item.choice]+') '+fr(esc(opts[item.choice]))+(ok?' ✓':' ✗')+'</div>';
  if(!ok) h+='<div class="chosen ok"><b>Correct answer:</b> ('+LETTERS[slide.correct]+') '+fr(esc(opts[slide.correct]))+'</div>';
  return h;
}
function renderChoiceBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div>';
  if(slide.kind==='mcq'){
    h += '<div class="qtext">'+fr(esc(slide.text))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  } else {
    h += '<div class="qtext"><span class="qtag" style="margin-left:0;margin-right:6px;">A / R</span>Assertion (A): '+fr(esc(slide.a))+'<br>Reason (R): '+fr(esc(slide.r))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  }
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(MODE==='quiz') h += '<div class="quiz-hint">Quiz mode — pick an option. The correct answer is revealed once you finish this tab.</div>';
  var locked = MODE==='learning' && (item.status==='correct' || item.status==='revealed');
  h += '<div class="options">';
  opts.forEach(function(opt,i){
    var cls='opt';
    if(locked){
      if(i===slide.correct) cls+=' is-correct';
      else if(item.choice===i) cls+=' is-wrong';
      cls+=' locked';
    }
    if(item.choice===i) cls+=' is-chosen';
    h += '<label class="'+cls+'"><input type="radio" name="choice" value="'+i+'" '+(item.choice===i?'checked':'')+' '+(locked?'disabled':'')+'> <span class="opt-l">('+LETTERS[i]+')</span> <span class="opt-t">'+fr(esc(opt))+'</span>'+(item.choice===i?'<span class="opt-tag">'+(locked?(i===slide.correct?'Your answer ✓':'Your answer ✗'):'Selected')+'</span>':'')+'</label>';
  });
  h += '</div>';
  if(locked) h += chosenHTML(slide,item);
  return h;
}

function renderBlankBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div><div class="qtext">';
  if(slide.kind==='case'){ h += '<b>'+esc(slide.title)+'.</b> '+esc(slide.body); }
  else { var pp=fr(esc(slide.p)).split('\n'); h += pp[0]+pp.slice(1).map(function(x){return '<span class="datline">'+x+'</span>';}).join(''); }
  h += (slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  if(slide.marks) h += '<div class="marks-pill">'+slide.marks+'</div>';
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';

  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  var blankCount=0; slide.flat.forEach(function(s){ blankCount+=Object.keys(s.a).length; });

  if(MODE==='quiz'){
    h += '<div class="step-badge">'+blankCount+' blank'+(blankCount===1?'':'s')+' in this question</div>';
    h += '<div class="quiz-hint">Quiz mode — fill in what you can. Correct answers are revealed once you finish this tab.</div>';
    if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
    if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
    h += '<div class="steps">';
    for(var qi=0; qi<total; qi++){
      var qstep = slide.flat[qi];
      var qss = item.stepStates[qi];
      if(qstep.partLabel) h += '<div class="subpart-label">'+esc(qstep.partLabel)+'</div>';
      if(qstep.orDivider) h += '<div class="or-divider">OR</div>';
      var qline = fr(qstep.t);
      Object.keys(qstep.a).forEach(function(bkey){
        var val = qss.inputs[bkey]||'';
        var inp='<input class="blank-input'+(['fv','fe','fl','fm','fi','dec'].indexOf(qstep.expr)>=0?' fr':(qstep.expr==='flist'||qstep.expr==='dlist'||qstep.expr==='glist')?' wide':qstep.expr===true?' expr':(qstep.expr==='words'||qstep.expr==='list'||qstep.expr==='expanded'||qstep.expr==='set'||qstep.expr==='primes'||qstep.expr==='trans'||qstep.expr==='rot'?' wide':''))+'" data-step="'+qi+'" data-bkey="'+bkey+'" value="'+esc(val)+'">';
        qline = qline.replace('__'+bkey+'__', inp);
      });
      if(qstep.fig) h += '<div class="fig">'+qstep.fig+'</div>';
      h += '<div class="step-line">'+qline+'</div>';
    }
    h += '</div>';
    return h;
  }

  if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
  if(hasExpr) h += '<div class="quiz-hint">Type answers like <b>2x-5</b>, <b>x^2-4</b> or <b>3+2i</b>. Use ^ for powers, | | for absolute value and pi for π. Any equivalent form is accepted.</div>';
  var locked = item.status==='correct' || item.status==='revealed';
  var upto = locked ? total-1 : item.curStep;
  h += '<div class="step-badge">Step '+(Math.min(item.curStep,total-1)+1)+' of '+total+'</div>';
  h += '<div class="steps">';
  for(var i=0;i<=upto;i++){
    var step = slide.flat[i];
    var ss = item.stepStates[i];
    if(step.partLabel) h += '<div class="subpart-label">'+esc(step.partLabel)+'</div>';
    if(step.orDivider) h += '<div class="or-divider">OR</div>';
    var resolved = ss.status==='correct' || ss.status==='revealed';
    var line = fr(step.t);
    Object.keys(step.a).forEach(function(bkey){
      var fs = ss.inputs['fs_'+bkey];
      var cls = fs==='correct'?'is-correct':(fs==='wrong'?'is-wrong':'');
      var val = ss.inputs[bkey]||'';
      var dis = resolved ? 'disabled':'';
      var inp='<input class="blank-input '+cls+(['fv','fe','fl','fm','fi','dec'].indexOf(step.expr)>=0?' fr':(step.expr==='flist'||step.expr==='dlist'||step.expr==='glist')?' wide':step.expr===true?' expr':(step.expr==='words'||step.expr==='list'||step.expr==='expanded'||step.expr==='set'||step.expr==='primes'||step.expr==='trans'||step.expr==='rot'?' wide':''))+'" data-step="'+i+'" data-bkey="'+bkey+'" value="'+esc(val)+'" '+dis+'>';
      line = line.replace('__'+bkey+'__', inp);
    });
    if(step.fig) h += '<div class="fig">'+step.fig+'</div>';
    h += '<div class="step-line'+(resolved?' resolved':'')+'">'+line+'</div>';
    if(ss.status==='revealed'){
      var reveals=[];
      Object.keys(step.a).forEach(function(bkey){ reveals.push(bkey+' = '+esc(step.a[bkey])); });
      h += '<div class="reveal-note">correct: '+reveals.join(', ')+'</div>';
    }
  }
  h += '</div>';
  return h;
}

var __flash=null;
function restoreFeedback(item){
  var fb=document.getElementById('feedbackBox'); if(!fb) return;
  if(__flash){ fb.className='feedback show '+__flash.c; fb.innerHTML=__flash.h; __flash=null; return; }
  if(MODE==='quiz'){ fb.className='feedback'; fb.innerHTML=''; return; }
  if(item.status==='correct'){ fb.className='feedback show ok'; fb.innerHTML='<b>All done — correct!</b>'; }
  else if(item.status==='revealed'){ fb.className='feedback show reveal'; fb.innerHTML='<b>Answer revealed above.</b> Move on whenever you’re ready.'; }
  else if(item.status==='skipped'){ fb.className='feedback show retry'; fb.innerHTML='Skipped — you can answer it now and press <b>Check</b>, or come back later from the Question Palette.'; }
  else { fb.className='feedback'; fb.innerHTML=''; }
}

function slideIsAnswered(slide,item){
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return item.stepStates.some(function(ss){ return Object.keys(ss.inputs).some(function(k){ return k.indexOf('fs_')!==0 && ss.inputs[k] && String(ss.inputs[k]).trim()!==''; }); });
}
function renderNavbar(item){
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  var slide = slides[ts.idx];
  var isLast = ts.idx === slides.length-1;
  var h='';
  h += '<button class="btn" id="btnPrev" '+(ts.idx===0?'disabled':'')+'>&larr; Previous</button>';

  if(MODE==='quiz'){
    h += '<button class="btn" id="btnSkip">Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnNext">'+(isLast?'Finish':'Next →')+'</button>';
  } else {
    h += '<button class="btn" id="btnSkip" '+(item.status!=='unanswered'?'disabled':'')+'>Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnCheck" '+((item.status!=='unanswered'&&item.status!=='skipped')?'disabled':'')+'>Check</button>';
    h += '<button class="btn btn-primary" id="btnNext" '+(canProceed(item)?'':'disabled')+'>'+(isLast?'Finish':'Next →')+'</button>';
  }
  document.getElementById('navbarInner').innerHTML = h;

  document.getElementById('btnPrev').addEventListener('click', function(){ if(ts.idx>0){ ts.idx--; renderSlide(); } });

  if(MODE==='quiz'){
    document.getElementById('btnSkip').addEventListener('click', function(){
      item.status='skipped';
      advanceQuiz(ts, slides);
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      item.status = slideIsAnswered(slide,item) ? 'answered' : 'unanswered';
      advanceQuiz(ts, slides);
    });
  } else {
    document.getElementById('btnSkip').addEventListener('click', function(){
      if(item.status==='unanswered'){ item.status='skipped'; renderSlide(); }
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      if(!canProceed(item)) return;
      if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
      else { renderFinished(); }
    });
    document.getElementById('btnCheck').addEventListener('click', function(){ handleCheck(); });
  }
}
function advanceQuiz(ts, slides){
  if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
  else { renderFinished(); }
}

function wireSlideEvents(slide, item, idx){
  document.querySelectorAll('input[type="radio"][name="choice"]').forEach(function(r){
    r.addEventListener('change', function(){ item.choice=parseInt(r.value,10); saveState();
      document.querySelectorAll('.opt').forEach(function(l){ l.classList.remove('is-chosen'); var t=l.querySelector('.opt-tag'); if(t) t.remove(); });
      var lab=r.closest('.opt'); lab.classList.add('is-chosen'); var tg=document.createElement('span'); tg.className='opt-tag'; tg.textContent='Selected'; lab.appendChild(tg); });
  });
  document.querySelectorAll('.blank-input').forEach(function(inp){
    inp.addEventListener('input', function(){
      var si=parseInt(inp.dataset.step,10), bk=inp.dataset.bkey;
      item.stepStates[si].inputs[bk]=inp.value;
      saveState();
    });
  });
}

function handleCheck(){
  var ts = state.tabs[activeTab];
  var slide = SLIDES[activeTab][ts.idx];
  var item = ts.items[ts.idx];
  if(item.status==='skipped') item.status='unanswered';
  var fb = document.getElementById('feedbackBox');

  if(slide.kind==='mcq' || slide.kind==='ar'){
    if(item.choice===undefined){ fb.className='feedback show err'; fb.innerHTML='Please choose an option first.'; return; }
    var ok = item.choice===slide.correct;
    if(ok){
      item.status='correct'; playSuccess();
      fb.className='feedback show ok'; fb.innerHTML='<b>Correct!</b>';
    } else {
      item.attempts=(item.attempts||0)+1;
      if(item.attempts>=2){ item.status='revealed'; playReveal(); }
      else { playWrong(); fb.className='feedback show retry'; fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'}; }
    }
    renderSlide();
    return;
  }

  // blank / case
  var step = slide.flat[item.curStep];
  var ss = item.stepStates[item.curStep];
  var blanks = Object.keys(step.a);
  var missing = blanks.some(function(k){ return !ss.inputs[k] || String(ss.inputs[k]).trim()===''; });
  if(missing){ fb.className='feedback show err'; fb.innerHTML='Fill in every blank in this step before checking.'; return; }

  var allGood=true;
  blanks.forEach(function(k){
    var good=answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr);
    ss.inputs['fs_'+k]=good?'correct':'wrong';
    if(!good) allGood=false;
  });

  if(allGood){
    ss.status='correct'; playSuccess();
    advanceStepOrFinish(item, slide);
  } else {
    ss.attempts=(ss.attempts||0)+1;
    if(ss.attempts>=2){
      ss.status='revealed'; playReveal();
      advanceStepOrFinish(item, slide);
    } else {
      playWrong();
      fb.className='feedback show retry';
      fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'};
      renderSlide();
      return;
    }
  }
  renderSlide();
}

function advanceStepOrFinish(item, slide){
  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  if(item.curStep < total-1){
    item.curStep++;
  } else {
    var anyRevealed = item.stepStates.some(function(ss){ return ss.status==='revealed'; });
    item.status = anyRevealed ? 'revealed' : 'correct';
  }
}

/* ================= palette ================= */
var overlay=document.getElementById('overlay');
function statusOf(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  return ts.items[i].status==='unanswered' ? 'locked' : ts.items[i].status;
}
function buildPalette(){
  var slides=SLIDES[activeTab];
  document.getElementById('paletteTitle').textContent = TAB_DEFS.find(function(t){return t.id===activeTab;}).label+' · Question palette';
  var body=document.getElementById('paletteBody');
  var html='';
  for(var i=0;i<slides.length;i++){
    html += '<div class="chip" data-status="'+statusOf(activeTab,i)+'" data-idx="'+i+'">'+(i+1)+'</div>';
  }
  body.innerHTML = html;
  body.querySelectorAll('.chip').forEach(function(chip){
    chip.addEventListener('click', function(){
      var i=parseInt(chip.dataset.idx,10);
      var ts=state.tabs[activeTab];
      if(i>ts.maxReached){ showToast('Finish the earlier questions to unlock this one.'); return; }
      ts.idx=i; closePalette(); renderSlide();
    });
  });
}
function openPalette(){ buildPalette(); overlay.classList.add('show'); }
function closePalette(){ overlay.classList.remove('show'); }
var toastTimer;
function showToast(msg){
  var t=document.getElementById('toast'); t.textContent=msg; t.classList.add('show');
  clearTimeout(toastTimer); toastTimer=setTimeout(function(){ t.classList.remove('show'); },2200);
}
document.getElementById('paletteFab').addEventListener('click', openPalette);
document.getElementById('paletteClose').addEventListener('click', closePalette);
overlay.addEventListener('click', function(e){ if(e.target===overlay) closePalette(); });

function updateFab(){
  var slides=SLIDES[activeTab];
  var done=state.tabs[activeTab].items.filter(function(it){ return it.status==='correct'||it.status==='revealed'||it.status==='skipped'; }).length;
  document.getElementById('fabBadge').textContent = done+'/'+slides.length;
}

/* ================= overall progress + finish ================= */
function updateChapterProgress(){
  var total=0, done=0;
  TAB_DEFS.forEach(function(td){
    state.tabs[td.id].items.forEach(function(it){
      total++;
      if(it.status==='correct'||it.status==='revealed'||it.status==='skipped') done++;
    });
  });
  var pct = total>0 ? Math.round((done/total)*100) : 0;
  document.getElementById('cpFill').style.width=pct+'%';
  document.getElementById('cpLabel').textContent=pct+'% complete';
}
function isSlideCorrect(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice===slide.correct;
  return slide.flat.every(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).every(function(k){ return answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr); });
  });
}
function isSlideAttempted(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return slide.flat.some(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).some(function(k){ return ss.inputs[k] && String(ss.inputs[k]).trim()!==''; });
  });
}
function slideLabel(slide){
  var t = slide.kind==='case' ? slide.title : (slide.kind==='ar' ? slide.a : (slide.p||slide.text||''));
  t = String(t);
  return t.length>90 ? t.slice(0,90)+'…' : t;
}
function slideAnswerText(slide, item, correctSide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
    if(correctSide) return '('+LETTERS[slide.correct]+') '+opts[slide.correct];
    return item.choice!==undefined ? '('+LETTERS[item.choice]+') '+opts[item.choice] : '— not attempted —';
  }
  return slide.flat.map(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).map(function(k){
      return correctSide ? step.a[k] : (ss.inputs[k] || '—');
    }).join(', ');
  }).join('  |  ');
}

function renderFinished(){
  if(MODE==='quiz'){ renderQuizResults(); return; }
  var ts=state.tabs[activeTab];
  var correct=ts.items.filter(function(i){return i.status==='correct';}).length;
  var revealed=ts.items.filter(function(i){return i.status==='revealed';}).length;
  var skipped=ts.items.filter(function(i){return i.status==='skipped';}).length;
  var h='<div class="qcard done-card"><div class="big">✨</div><h2>Tab complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">You worked through all '+ts.items.length+' questions in this tab.</p>';
  if(!ts.recorded){ ts.recorded=true; addRecord('learning', activeTab, correct, revealed, skipped, ts.items.length); }
  h+='<div class="score-pills">'+
     '<span class="score-pill" style="background:var(--success-soft);color:var(--success);">'+correct+' correct</span>'+
     '<span class="score-pill" style="background:var(--danger-soft);color:var(--danger);">'+revealed+' revealed</span>'+
     '<span class="score-pill" style="background:var(--gold-soft);color:var(--retry-text);">'+skipped+' skipped</span></div>'+
     '<button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; ts.recorded=false; renderSlide(); });
  updateChapterProgress(); saveState();
}

function renderQuizResults(){
  var ts=state.tabs[activeTab];
  var slides=SLIDES[activeTab];
  var correctCount=0, attemptedCount=0;
  var rowsHtml = slides.map(function(slide,i){
    var item=ts.items[i];
    var ok=isSlideCorrect(activeTab,i);
    var att=isSlideAttempted(activeTab,i);
    if(ok) correctCount++;
    if(att) attemptedCount++;
    var tagCls = ok?'ok':(att?'bad':'na');
    var tagText = ok?'Correct':(att?'Incorrect':'Not attempted');
    var row='<div class="review-row">';
    row+='<span class="review-tag '+tagCls+'">Q'+(i+1)+' · '+tagText+'</span>';
    row+='<div class="review-q">'+fr(esc(slideLabel(slide)))+'</div>';
    row+='<div class="review-ans"><b>Your answer:</b> '+fr(esc(slideAnswerText(slide,item,false)))+'</div>';
    if(!ok) row+='<div class="review-ans" style="color:var(--success);"><b>Correct answer:</b> '+fr(esc(slideAnswerText(slide,item,true)))+'</div>';
    if(slide.sol) row+='<details class="rev-sol"><summary>Show solution</summary>'+solutionHTML(slide)+'</details>';
    row+='</div>';
    return row;
  }).join('');

  addRecord('quiz', activeTab, correctCount, 0, 0, slides.length);
  var h='<div class="qcard done-card" style="text-align:left;">';
  h+='<div style="text-align:center;"><div class="big">🏁</div><h2>Quiz complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">'+correctCount+' / '+slides.length+' correct · '+attemptedCount+' attempted</p></div>';
  h+='<div style="margin-top:16px;">'+rowsHtml+'</div>';
  h+='<div style="text-align:center;margin-top:6px;"><button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  h+='</div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; renderSlide(); });
  playSuccess();
  updateChapterProgress(); saveState();
}

/* ================= mode picker ================= */
function updateModePill(){
  var btn=document.getElementById('modePill');
  if(!btn) return;
  btn.textContent = MODE==='quiz' ? '📝 Quiz Mode · switch' : '📘 Learning Sheet · switch';
}
function showChrome(show){
  document.querySelector('.tabbar').style.display = show?'':'none';
  document.querySelector('.slide-progress').style.display = show?'':'none';
  document.querySelector('.navbar').style.display = show?'':'none';
  document.getElementById('paletteFab').style.display = show?'':'none';
}
function renderModePicker(){
  showChrome(false);
  var wrap=document.getElementById('wrap');
  wrap.innerHTML =
    '<div class="mode-pick">'+
      '<div class="mode-card" data-pick="learning"><div class="mode-icon">📘</div><h3>Learning Sheet</h3>'+
      '<p>Work through each question step by step with instant feedback — two tries, then the correct value is revealed right there so you can keep moving.</p></div>'+
      '<div class="mode-card" data-pick="quiz"><div class="mode-icon">📝</div><h3>Quiz Mode</h3>'+
      '<p>Attempt every question with no hints along the way. Your score and the full answer key are shown together once you finish the tab — just like the real exam.</p></div>'+
    '</div>';
  wrap.querySelectorAll('[data-pick]').forEach(function(card){
    card.addEventListener('click', function(){
      setMode(card.dataset.pick); activeTab='theory';
      document.getElementById('modePill').hidden=false;
      updateModePill();
      showChrome(true);
      buildTabbar();
      renderSlide();
    });
  });
}
document.getElementById('modePill').addEventListener('click', function(){
  if(!appState.mode){ return; }
  setMode(appState.mode==='quiz' ? 'learning' : 'quiz');
  updateModePill();
  showChrome(true);
  buildTabbar();
  renderSlide();
});

/* ================= boot ================= */
var _origRenderSlide = renderSlide;
renderSlide = function(){ _origRenderSlide(); updateChapterProgress(); updateModePill(); };


/* ================= theory tab ================= */
function renderTheory(){
  var wrap=document.getElementById('wrap');
  wrap.innerHTML='<div class="theory">'+fr(THEORY)+'</div>';
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Theory — notes, key ideas and worked examples';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
  wrap.querySelectorAll('[data-jump]').forEach(function(b){ b.addEventListener('click',function(){ var t=document.getElementById(b.dataset.jump); if(t) t.scrollIntoView({behavior:'smooth',block:'start'}); }); });
}
var _rsTheory = renderSlide;
renderSlide = function(){
  if(activeTab==='theory'){ renderTheory(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  document.querySelector('.slide-progress').style.display='';
  document.querySelector('.navbar').style.display='';
  document.getElementById('paletteFab').style.display='';
  _rsTheory();
};


/* ================= MYP criterion report ================= */
var CRIT_COL={A:'var(--accent-text)',B:'var(--gold)',C:'#8A6FC4',D:'#2F9AA0'};
function critStats(){
  return REPORT.map(function(r){
    var tabId=r[0], slides=SLIDES[tabId], ts=state&&state.tabs[tabId];
    var c=0,w=0,n=0;
    slides.forEach(function(sl,i){
      if(!ts||!ts.items[i]){ n++; return; }
      var it=ts.items[i];
      if(MODE==='learning'){
        if(it.status==='correct') c++; else if(it.status==='revealed') w++; else n++;
      } else {
        if(isSlideCorrect(tabId,i)) c++; else if(isSlideAttempted(tabId,i)) w++; else n++;
      }
    });
    var tot=slides.length, pct=tot?Math.round(c/tot*100):0;
    var lvl=Math.round(c/Math.max(tot,1)*8);
    return {tab:tabId,letter:r[1],name:r[2],c:c,w:w,n:n,tot:tot,pct:pct,lvl:lvl};
  });
}
function arcPath(cx,cy,r,a0,a1){
  if(a1-a0>=Math.PI*2-1e-6){ return 'M'+(cx-r)+','+cy+' a'+r+','+r+' 0 1,0 '+(2*r)+',0 a'+r+','+r+' 0 1,0 '+(-2*r)+',0 Z'; }
  var x0=cx+r*Math.sin(a0), y0=cy-r*Math.cos(a0), x1=cx+r*Math.sin(a1), y1=cy-r*Math.cos(a1);
  return 'M'+cx+','+cy+' L'+x0.toFixed(2)+','+y0.toFixed(2)+' A'+r+','+r+' 0 '+((a1-a0)>Math.PI?1:0)+',1 '+x1.toFixed(2)+','+y1.toFixed(2)+' Z';
}
function pieSVG(parts,size,hole,center,sub){
  var tot=parts.reduce(function(s,p){return s+p.v;},0), cx=size/2, cy=size/2, r=size/2-4, a=0, h='';
  if(!tot){ h+='<circle cx="'+cx+'" cy="'+cy+'" r="'+r+'" style="fill:var(--paper-2);stroke:var(--rule)"/>'; }
  parts.forEach(function(p){ if(!p.v) return; var b=a+p.v/tot*Math.PI*2; h+='<path d="'+arcPath(cx,cy,r,a,b)+'" style="fill:'+p.col+';stroke:var(--card);stroke-width:2"><title>'+esc(p.label)+': '+p.v+'</title></path>'; a=b; });
  if(hole) h+='<circle cx="'+cx+'" cy="'+cy+'" r="'+(r*hole)+'" style="fill:var(--card)"/>';
  if(center) h+='<text x="'+cx+'" y="'+(cy-(sub?4:0))+'" text-anchor="middle" dominant-baseline="middle" style="fill:var(--ink);font:700 '+(size>150?22:15)+'px Fraunces,serif">'+center+'</text>';
  if(sub) h+='<text x="'+cx+'" y="'+(cy+16)+'" text-anchor="middle" style="fill:var(--ink-soft);font:600 11px \'Source Sans 3\',sans-serif">'+sub+'</text>';
  return '<svg viewBox="0 0 '+size+' '+size+'" width="'+size+'" height="'+size+'" role="img">'+h+'</svg>';
}
function band(l){ return l===0?'0':(l<=2?'1–2':(l<=4?'3–4':(l<=6?'5–6':'7–8'))); }
function renderReport(){
  var st=critStats(), totC=0, totQ=0;
  st.forEach(function(s){ totC+=s.c; totQ+=s.tot; });
  var h='<div class="theory">';
  h+='<section class="note"><h2>Chapter test report</h2><p class="lt">'+(MODE==='quiz'?'<b>Quiz mode</b> results: answers are marked when you finish each test tab.':'<b>Learning mode</b> results: a question counts as correct only if you got it without the answer being revealed. Switch to Quiz mode for an exam-style score.')+'</p>';
  h+='<div class="rep-top"><div class="rep-pie">'+pieSVG(st.map(function(s){return {v:s.c,col:CRIT_COL[s.letter],label:'Criterion '+s.letter};}),200,0.55,totC+'/'+totQ,'correct')+'</div>';
  h+='<div class="rep-legend"><div class="rep-cap">Marks earned, by criterion</div>'+st.map(function(s){ return '<div class="rep-li"><span class="sw" style="background:'+CRIT_COL[s.letter]+'"></span><b>'+s.letter+'</b>&nbsp;'+esc(s.name)+'<span class="rep-n">'+s.c+' / '+s.tot+'</span></div>'; }).join('')+'</div></div></section>';
  h+='<div class="rep-grid">'+st.map(function(s){
    return '<div class="rep-card"><div class="rep-h"><span class="crit" style="background:'+CRIT_COL[s.letter]+'">'+s.letter+'</span>'+esc(s.name)+'</div>'+
      '<div class="rep-row">'+pieSVG([{v:s.c,col:'var(--success)',label:'Correct'},{v:s.w,col:'var(--danger)',label:'Incorrect'},{v:s.n,col:'var(--locked)',label:'Not attempted'}],120,0.5,s.pct+'%')+
      '<div class="rep-stats"><div><span class="sw" style="background:var(--success)"></span>Correct <b>'+s.c+'</b></div><div><span class="sw" style="background:var(--danger)"></span>Incorrect <b>'+s.w+'</b></div><div><span class="sw" style="background:var(--locked)"></span>Not attempted <b>'+s.n+'</b></div>'+
      '<div class="rep-lvl">Indicative level <b>'+s.lvl+'</b> / 8 <span>(band '+band(s.lvl)+')</span></div></div></div>'+
      '<button class="hub-btn" data-go="'+s.tab+'">Open Test '+s.letter+' →</button></div>';
  }).join('')+'</div>';
  h+='<p class="rep-note">Indicative level = fraction of questions correct × 8, rounded. It is a practice guide only; your teacher awards the real MYP criterion levels.</p></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  document.querySelector('.slide-progress').style.display='none';
  document.querySelector('.navbar').style.display='none';
  document.getElementById('paletteFab').style.display='none';
  document.getElementById('secSub').textContent='Report — chapter test results by MYP criterion';
  wrap.querySelectorAll('[data-go]').forEach(function(b){ b.addEventListener('click',function(){ activeTab=b.dataset.go; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); });
}
var _rsReport = renderSlide;
renderSlide = function(){
  if(activeTab==='report'){ renderReport(); buildTabbar(); updateChapterProgress(); updateModePill(); saveState(); return; }
  _rsReport();
};


/* ================= skipped-question return ================= */
function firstSkippedIdx(ts){
  for(var i=0;i<ts.items.length;i++){
    var it=ts.items[i];
    if(MODE==='quiz'){ if(!isSlideAttempted(activeTab,i)) return i; }
    else if(it.status==='skipped'||it.status==='unanswered') return i;
  }
  return -1;
}
function skippedList(ts){
  var out=[]; for(var i=0;i<ts.items.length;i++){ var it=ts.items[i];
    if(MODE==='quiz' ? !isSlideAttempted(activeTab,i) : (it.status==='skipped'||it.status==='unanswered')) out.push(i); }
  return out;
}
function renderSkipGate(ts){
  var list=skippedList(ts);
  var h='<div class="qcard done-card"><div class="big">⏭️</div><h2>You skipped '+list.length+' question'+(list.length>1?'s':'')+'</h2>'+
    '<p style="color:var(--ink-soft);font-size:14px;">Answer them now, or submit the tab as it is. Answers are marked only when you submit.</p>'+
    '<div class="skip-chips">'+list.map(function(i){ return '<button class="chip skip-go" data-i="'+i+'">Q'+(i+1)+'</button>'; }).join('')+'</div>'+
    '<div class="skip-btns"><button class="btn btn-primary" id="btnGoSkipped">Answer skipped questions</button><button class="btn" id="btnSubmitAnyway">Submit anyway</button></div></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  var go=function(i){ ts.idx=i; ts.maxReached=Math.max(ts.maxReached,i); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); };
  document.getElementById('btnGoSkipped').addEventListener('click',function(){ go(list[0]); });
  document.querySelectorAll('.skip-go').forEach(function(b){ b.addEventListener('click',function(){ go(parseInt(b.dataset.i,10)); }); });
  document.getElementById('btnSubmitAnyway').addEventListener('click',function(){ ts.submitOK=true; renderFinished(); ts.submitOK=false; });
  saveState();
}
var _rfSkip = renderFinished;
renderFinished = function(){
  var ts=state.tabs[activeTab];
  if(MODE==='quiz' && !ts.submitOK && skippedList(ts).length){ renderSkipGate(ts); return; }
  _rfSkip();
  if(MODE==='learning'){
    var list=skippedList(ts);
    if(list.length){
      var card=document.querySelector('.done-card');
      if(card){ var d=document.createElement('div'); d.className='skip-btns';
        d.innerHTML='<button class="btn btn-primary" id="btnGoSkipped">Attempt skipped questions ('+list.length+')</button>';
        card.appendChild(d);
        document.getElementById('btnGoSkipped').addEventListener('click',function(){ ts.idx=list[0]; ts.recorded=false; renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); }); }
    }
  }
};


/* ================= approx answers (physics: within 1%) ================= */
var _amTools = answerMatches;
answerMatches = function(input,answer,accept,expr){
  if(expr==='approx'){
    var n1=parseNum(input); if(n1===null) return false;
    return [answer].concat(accept||[]).some(function(a){ var n2=parseNum(a); if(n2===null) return false; return Math.abs(n1-n2) <= Math.max(0.011*Math.abs(n2), 1e-9); });
  }
  return _amTools(input,answer,accept,expr);
};

/* ================= palette: every question already reached can be opened ================= */
statusOf = function(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  var s=ts.items[i].status;
  if(s==='unanswered') return 'skipped';
  return s;
};

/* ================= on-screen keyboard ================= */
var KB={on:true, page:'num', target:null};
try{ var kbp=localStorage.getItem('sopaan-kb-pref'); if(kbp==='off') KB.on=false; }catch(e){}
function kbSave(){ try{ localStorage.setItem('sopaan-kb-pref', KB.on?'on':'off'); }catch(e){} }
var KEYS_NUM=[['7','8','9','(',')'],['4','5','6','−','/'],['1','2','3','.',','],['0',':','%','°','⌫'],['abc','←','→','Clear','Done']];
var KEYS_FRAC=[['7','8','9','/'],['4','5','6','−'],['1','2','3','space'],['0',',','⌫','Clear'],['abc','←','→','Done']];
var KEYS_ALG=[['7','8','9','x','y','n'],['4','5','6','+','−','a'],['1','2','3','×','÷','b'],['0','.','(',')','^','²'],['/','π','|','t','⌫','Clear'],['abc','←','→','Done']];
function kbLayoutFor(inp){ try{ var ts=state.tabs[activeTab], sl=SLIDES[activeTab][ts.idx], stp=sl.flat[parseInt(inp.dataset.step,10)]; var m=stp.expr, key=String(stp.a[inp.dataset.bkey]||'');
  if(m==='words'||m==='glist'||m==='angle') return 'abc'; if(m===true||m==='pow'||m==='primes') return 'alg';
  if(['fv','fe','fl','fm','fi','flist'].indexOf(m)>=0) return 'frac'; if(m==='dec'||m==='approx'||m==='dlist'||m==='set'||m==='coord'||m==='list'||m==='time') return 'num';
  if(/^[\-−]?\d+ \d+\/\d+$/.test(key)||/^[\-−]?\d+\/\d+$/.test(key)) return 'frac'; if(/[a-df-z]/i.test(key.replace(/pi/gi,''))) return /\d/.test(key)?'alg':'abc'; return 'num'; }catch(e){ return 'num'; } }
var KEYS_ABC=[['q','w','e','r','t','y','u','i','o','p'],['a','s','d','f','g','h','j','k','l','-'],['z','x','c','v','b','n','m',',',':','/'],['123','space','←','→','⌫','Done']];
function kbBuild(){
  var el=document.getElementById('vkb'); if(!el){ el=document.createElement('div'); el.id='vkb'; el.className='vkb'; document.body.appendChild(el);
    el.addEventListener('pointerdown',function(e){ var b=e.target.closest('button[data-k]'); e.preventDefault(); if(b) kbPress(b.dataset.k); });
    el.addEventListener('mousedown',function(e){ e.preventDefault(); }); }
  var rows={num:KEYS_NUM,frac:KEYS_FRAC,alg:KEYS_ALG,abc:KEYS_ABC}[KB.page]||KEYS_NUM;
  el.innerHTML='<div class="vkb-top"><span>⌨️ Keyboard</span><button data-k="device" class="vkb-link">Use device keyboard</button></div>'+
    rows.map(function(r){ return '<div class="vkb-row">'+r.map(function(k){
      var cls='vkb-k'+(/^(abc|123|Done|Clear|⌫|←|→|space)$/.test(k)?' fn':'')+(k==='Done'?' done':'');
      return '<button type="button" class="'+cls+'" data-k="'+k+'">'+(k==='space'?'space':k)+'</button>'; }).join('')+'</div>'; }).join('');
  return el;
}
function kbShow(inp){ KB.target=inp; KB.home=kbLayoutFor(inp); KB.page=KB.home; if(!KB.on) return; var cp=document.getElementById('calcPanel'); if(cp&&cp.classList.contains('show')) return; var el=kbBuild(); var nb=document.querySelector('.navbar'); el.style.bottom=(nb?nb.getBoundingClientRect().height:0)+'px'; el.classList.add('show'); document.body.classList.add('kb-open'); setTimeout(function(){ var r=inp.getBoundingClientRect(), top=el.getBoundingClientRect().top; if(r.bottom>top-12) window.scrollBy({top:r.bottom-top+60,behavior:'smooth'}); else if(r.top<60) window.scrollBy({top:r.top-80,behavior:'smooth'}); },30); }
function kbHide(){ var el=document.getElementById('vkb'); if(el) el.classList.remove('show'); document.body.classList.remove('kb-open'); }
function kbInsert(s){
  var t=KB.target; if(!t||t.disabled) return;
  var a=t.selectionStart==null?t.value.length:t.selectionStart, b=t.selectionEnd==null?a:t.selectionEnd;
  t.value=t.value.slice(0,a)+s+t.value.slice(b); var p=a+s.length; try{ t.setSelectionRange(p,p); }catch(e){}
  t.dispatchEvent(new Event('input',{bubbles:true}));
}
function kbPress(k){
  var t=KB.target; if(k==='device'){ KB.on=false; kbSave(); kbHide(); document.querySelectorAll('.blank-input').forEach(function(i){ i.removeAttribute('inputmode'); }); if(t){ t.blur(); setTimeout(function(){ t.focus(); },50); } showToast('Device keyboard on. Tap ⌨️ on any blank to bring the on-screen keyboard back.'); return; }
  if(k==='Done'){ kbHide(); if(t) t.blur(); return; }
  if(k==='abc'||k==='123'){ KB.page=(k==='abc')?'abc':(KB.home&&KB.home!=='abc'?KB.home:'num'); kbBuild(); return; }
  if(!t) return;
  if(k==='⌫'){ var a=t.selectionStart, b=t.selectionEnd; if(a===b&&a>0){ t.value=t.value.slice(0,a-1)+t.value.slice(b); try{t.setSelectionRange(a-1,a-1);}catch(e){} } else { t.value=t.value.slice(0,a)+t.value.slice(b); try{t.setSelectionRange(a,a);}catch(e){} } t.dispatchEvent(new Event('input',{bubbles:true})); return; }
  if(k==='Clear'){ t.value=''; t.dispatchEvent(new Event('input',{bubbles:true})); return; }
  if(k==='←'||k==='→'){ var p=(t.selectionStart||0)+(k==='←'?-1:1); p=Math.max(0,Math.min(t.value.length,p)); try{t.setSelectionRange(p,p);}catch(e){} return; }
  var map={'−':'-','space':' '}; kbInsert(map[k]!==undefined?map[k]:k);
}
function kbWire(){
  document.querySelectorAll('.blank-input').forEach(function(inp){
    if(inp.dataset.kb) return; inp.dataset.kb='1';
    if(KB.on) inp.setAttribute('inputmode','none');
    inp.addEventListener('focus',function(){ kbShow(inp); });
    var btn=document.createElement('button'); btn.type='button'; btn.className='kb-toggle'; btn.title='On-screen keyboard'; btn.textContent='⌨️'; btn.tabIndex=-1;
    btn.addEventListener('mousedown',function(e){ e.preventDefault(); });
    btn.addEventListener('click',function(){ KB.on=true; kbSave(); document.querySelectorAll('.blank-input').forEach(function(i){ i.setAttribute('inputmode','none'); }); inp.focus(); kbShow(inp); });
    if(!inp.disabled) inp.insertAdjacentElement('afterend',btn);
  });
}
document.addEventListener('focusout',function(e){ setTimeout(function(){ var a=document.activeElement; if(!a||!a.classList||!a.classList.contains('blank-input')){ if(!document.querySelector('#vkb:hover')) kbHide(); } },120); });

/* ================= calculator ================= */
var CALC={expr:'', ans:0};
function calcEval(src){
  var s=String(src).replace(/×/g,'*').replace(/÷/g,'/').replace(/−/g,'-').replace(/π/g,'(PI)').replace(/Ans/g,'('+CALC.ans+')').replace(/\^/g,'**').replace(/√\(/g,'sqrt(').replace(/²/g,'**2').replace(/E/g,'*10**');
  s=s.replace(/(^|[(*\/+\-,])-/g,'$1(-1)*');
  if(/[^0-9+\-*/().,a-z A-Z]/.test(s)) throw 0;
  var ok=s.replace(/sin|cos|tan|asin|acos|atan|sqrt|log|ln|PI|abs/g,''); if(/[a-zA-Z]/.test(ok)) throw 0;
  var f=new Function('sin','cos','tan','asin','acos','atan','sqrt','log','ln','PI','abs','return ('+s+');');
  var d=Math.PI/180;
  var v=f(function(x){return Math.sin(x*d);},function(x){return Math.cos(x*d);},function(x){return Math.tan(x*d);},
    function(x){return Math.asin(x)/d;},function(x){return Math.acos(x)/d;},function(x){return Math.atan(x)/d;},Math.sqrt,Math.log10,Math.log,Math.PI,Math.abs);
  if(typeof v!=='number'||!isFinite(v)) throw 0; return v;
}
function fmtNum(v){ if(Math.abs(v)>=1e10||(Math.abs(v)<1e-6&&v!==0)) return v.toExponential(6).replace(/\.?0+e/,'e'); return String(parseFloat(v.toPrecision(10))); }
var CKEYS=[['sin(','cos(','tan(','√(','^','²'],['asin(','acos(','atan(','(',')','π'],['7','8','9','÷','⌫','AC'],['4','5','6','×','E','Ans'],['1','2','3','−','(−)','Insert'],['0','.','=','+']];
function openCalc(){
  var p=document.getElementById('calcPanel');
  if(!p){ p=document.createElement('div'); p.id='calcPanel'; p.className='tool-panel calc';
    p.innerHTML='<div class="tp-head"><b>🧮 Calculator</b><span class="tp-note">degrees · tap a blank, then Insert</span><button class="tp-x" data-c="close">✕</button></div>'+
      '<div class="calc-disp"><div class="calc-expr" id="calcExpr"></div><div class="calc-res" id="calcRes">0</div></div>'+
      '<div class="calc-keys">'+CKEYS.map(function(r){ return r.map(function(k){ return '<button type="button" data-c="'+k+'" class="'+(k==='='?'eq':(/^(AC|⌫|Insert)$/.test(k)?'fn':''))+'">'+({'sin(':'sin','cos(':'cos','tan(':'tan','asin(':'sin⁻¹','acos(':'cos⁻¹','atan(':'tan⁻¹','√(':'√'}[k]||k)+'</button>'; }).join(''); }).join('')+'</div>';
    document.body.appendChild(p);
    p.addEventListener('mousedown',function(e){ if(e.target.closest('button')) e.preventDefault(); });
    p.addEventListener('click',function(e){ var b=e.target.closest('button[data-c]'); if(!b) return; calcKey(b.dataset.c); });
  }
  kbHide(); var nb=document.querySelector('.navbar'); p.style.bottom=((nb?nb.getBoundingClientRect().height:0)+8)+'px'; p.classList.add('show'); document.body.classList.add('calc-open'); calcShow();
}
function calcShow(res){ document.getElementById('calcExpr').textContent=CALC.expr||' '; if(res!==undefined) document.getElementById('calcRes').textContent=res; }
function calcKey(k){
  if(k==='close'){ document.getElementById('calcPanel').classList.remove('show'); document.body.classList.remove('calc-open'); return; }
  if(k==='AC'){ CALC.expr=''; calcShow('0'); return; }
  if(k==='⌫'){ CALC.expr=CALC.expr.replace(/(asin\(|acos\(|atan\(|sin\(|cos\(|tan\(|√\(|Ans|.)$/,''); calcShow(); return; }
  if(k==='='){ try{ var v=calcEval(CALC.expr); CALC.ans=v; calcShow(fmtNum(v)); }catch(e){ calcShow('Error'); } return; }
  if(k==='(−)'){ CALC.expr+='−'; calcShow(); return; }
  if(k==='Insert'){ var r=document.getElementById('calcRes').textContent; if(KB.target && !KB.target.disabled && r!=='Error'){ KB.target.value=r; KB.target.dispatchEvent(new Event('input',{bubbles:true})); showToast('Inserted '+r+' into the blank.'); } else showToast('Tap a blank first, then press Insert.'); return; }
  CALC.expr+=k; calcShow();
}

/* ================= Desmos ================= */
var DESMOS_KEY='dcb31709b452b1cf9dc26972add0fda6', desmosCalc=null, desmosLoading=false;
function openDesmos(exprs){
  var p=document.getElementById('desmosPanel');
  if(!p){ p=document.createElement('div'); p.id='desmosPanel'; p.className='tool-panel desmos';
    p.innerHTML='<div class="tp-head"><b>📈 Desmos graphing calculator</b><button class="tp-x" id="desmosReset">Reset graph</button><button class="tp-x" id="desmosClose">✕</button></div><div id="desmosBox"><div class="desmos-msg">Loading Desmos…</div></div>';
    document.body.appendChild(p);
    document.getElementById('desmosClose').addEventListener('click',function(){ p.classList.remove('show'); });
    document.getElementById('desmosReset').addEventListener('click',function(){ if(desmosCalc) desmosSet(p._exprs||[]); });
  }
  p._exprs=exprs||[]; p.classList.add('show');
  if(window.Desmos){ desmosInit(); desmosSet(p._exprs); return; }
  if(desmosLoading) return; desmosLoading=true;
  var sc=document.createElement('script'); sc.src='https://www.desmos.com/api/v1.9/calculator.js?apiKey='+DESMOS_KEY;
  sc.onload=function(){ desmosInit(); desmosSet(p._exprs); };
  sc.onerror=function(){ desmosLoading=false; document.getElementById('desmosBox').innerHTML='<div class="desmos-msg">Desmos needs an internet connection. <a href="https://www.desmos.com/calculator" target="_blank" rel="noopener">Open Desmos in a new tab</a>.</div>'; };
  document.head.appendChild(sc);
}
function desmosInit(){ if(desmosCalc) return; var box=document.getElementById('desmosBox'); box.innerHTML=''; desmosCalc=Desmos.GraphingCalculator(box,{expressionsCollapsed:false,settingsMenu:false,border:false,degreeMode:true}); }
function desmosSet(exprs){ if(!desmosCalc) return; desmosCalc.setBlank(); (exprs||[]).forEach(function(e,i){ if(typeof e==='string') desmosCalc.setExpression({id:'e'+i,latex:e}); else desmosCalc.setExpression(Object.assign({id:'e'+i},e)); }); }

/* ================= toolbar on each question ================= */
var _rsTools = renderSlide;
renderSlide = function(){
  _rsTools();
  kbHide();
  if(activeTab==='theory'||activeTab==='report') return;
  var ts=state.tabs[activeTab]; if(!ts) return;
  var slide=SLIDES[activeTab][ts.idx], card=document.querySelector('#wrap .qcard');
  if(card && slide && slide.tools && slide.tools.length && !card.querySelector('.tool-bar')){
    var bar=document.createElement('div'); bar.className='tool-bar';
    bar.innerHTML=(slide.tools.indexOf('calc')>=0?'<button type="button" class="tool-btn" data-t="calc">🧮 Calculator</button>':'')+
                  (slide.tools.indexOf('desmos')>=0?'<button type="button" class="tool-btn" data-t="desmos">📈 Desmos graph</button>':'');
    card.insertBefore(bar, card.firstChild);
    bar.addEventListener('click',function(e){ var b=e.target.closest('[data-t]'); if(!b) return; if(b.dataset.t==='calc') openCalc(); else openDesmos(slide.desmos||[]); });
  }
  kbWire();
};



/* ================= signed fractions in text: {−3/4}, {3/−4}, {−2 1/3}, {p/q} ================= */
fr = function(s){ return String(s).replace(/&lt;(\/?)(b|sup|sub|i)>/g,'<$1$2>')
  .replace(/\{([−-]?\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>')
  .replace(/\{([−-]?[A-Za-z0-9]+)\/([−-]?[A-Za-z0-9]+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); };
/* ================= BMA badge → main page of this sheet (theory hub) ================= */
(function(){
  var c=document.querySelector('.brand .crest'); if(!c) return;
  var a=document.createElement('button'); a.type='button'; a.className='crest crest-home'; a.title='Back to the main page (theory notes)'; a.setAttribute('aria-label','Main page');
  a.innerHTML='BM<span class="crest-h">⌂</span>'; c.parentNode.replaceChild(a,c);
  a.addEventListener('click',function(){
    if(!student||!MODE){ window.scrollTo({top:0,behavior:'smooth'}); return; }
    if(typeof kbHide==='function') kbHide(); if(typeof SP!=='undefined'&&SP.on) spToggle(false);
    var cp=document.getElementById('calcPanel'); if(cp) cp.classList.remove('show'); document.body.classList.remove('calc-open');
    activeTab = (typeof THEORY!=='undefined') ? 'theory' : TAB_DEFS[0].id;
    buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'});
  });
})();

/* ================= session clock: starts at sign-in and keeps running ================= */
var CLK={t0:null};
(function(){
  var row=document.querySelector('.brand .brand-row'); if(!row) return;
  var d=document.createElement('div'); d.className='bmasw off'; d.id='swBox'; d.title='Time since you signed in';
  d.innerHTML='<span class="bmasw-ic">⏱</span><span class="bmasw-t" id="swT">00:00</span>';
  row.appendChild(d); setInterval(swTick,1000);
})();
function swFmt(s){ s=Math.floor(s||0); var h=Math.floor(s/3600), m=Math.floor(s%3600/60), x=s%60; return (h?h+':'+String(m).padStart(2,'0'):String(m).padStart(2,'0'))+':'+String(x).padStart(2,'0'); }
function swTick(){
  var box=document.getElementById('swBox'); if(!box) return;
  if(student && !CLK.t0) CLK.t0=Date.now();
  if(!student) CLK.t0=null;
  box.classList.toggle('off',!CLK.t0);
  document.getElementById('swT').textContent = CLK.t0 ? swFmt((Date.now()-CLK.t0)/1000) : '00:00';
}
function swTab(){ try{ if(!state||!state.tabs||activeTab==='theory'||activeTab==='report') return null; return state.tabs[activeTab]||null; }catch(e){ return null; } }
var _rsSW = renderSlide;
renderSlide = function(){ _rsSW(); swTick(); };
var _rfSW = renderFinished;
renderFinished = function(){ _rfSW(); var done=document.querySelector('#wrap .done-card'); if(CLK.t0 && done && !done.querySelector('.bmasw-done')){ var p=document.createElement('p'); p.className='bmasw-done'; p.textContent='⏱ Time since sign-in: '+swFmt((Date.now()-CLK.t0)/1000); var h2=done.querySelector('h2'); if(h2) h2.insertAdjacentElement('afterend',p); else done.appendChild(p); } };

/* ================= scratchpad (Khan-style, 4 pens) ================= */
var SP={on:false, draw:true, color:'ink', size:3, erase:false, store:{}, key:null, cv:null, ctx:null, down:false, last:null};
var SP_COL={ink:null, blue:'#2563EB', red:'#DC2626', green:'#16A34A'};
function spInk(){ return getComputedStyle(document.documentElement).getPropertyValue('--ink').trim()||'#211E1A'; }
function spKey(){ var ts=swTab(); return ts ? (MODE+'|'+activeTab+'|'+ts.idx) : null; }
function spBuild(){
  if(SP.cv) return;
  var cv=document.createElement('canvas'); cv.id='spCanvas'; cv.className='sp-canvas'; document.body.appendChild(cv);
  var bar=document.createElement('div'); bar.id='spBar'; bar.className='sp-bar';
  bar.innerHTML='<span class="sp-lbl">✏️ Scratchpad</span>'+
    ['ink','blue','red','green'].map(function(c){ return '<button type="button" class="sp-pen" data-c="'+c+'" title="'+(c==='ink'?'black':c)+' pen"><i style="background:'+(c==='ink'?'var(--ink)':SP_COL[c])+'"></i></button>'; }).join('')+
    '<button type="button" class="sp-tool" data-t="erase" title="Eraser">🧽</button><button type="button" class="sp-tool" data-t="size" title="Pen size">●</button><button type="button" class="sp-tool" data-t="scroll" title="Pause drawing to scroll or answer">✋</button>'+
    '<button type="button" class="sp-tool" data-t="clear" title="Clear page">🗑</button><button type="button" class="sp-tool" data-t="close" title="Close scratchpad">✕</button>';
  document.body.appendChild(bar);
  bar.addEventListener('click',function(e){ var b=e.target.closest('button'); if(!b) return;
    if(b.dataset.c){ SP.color=b.dataset.c; SP.erase=false; SP.draw=true; }
    else if(b.dataset.t==='erase'){ SP.erase=true; SP.draw=true; }
    else if(b.dataset.t==='size'){ SP.size = SP.size===3?6:(SP.size===6?1.5:3); b.textContent = SP.size===6?'⬤':(SP.size===1.5?'·':'●'); }
    else if(b.dataset.t==='scroll'){ SP.draw=!SP.draw; }
    else if(b.dataset.t==='clear'){ spClear(); }
    else if(b.dataset.t==='close'){ spToggle(false); return; }
    spUI(); });
  SP.cv=cv; SP.ctx=cv.getContext('2d');
  cv.addEventListener('pointerdown',function(e){ if(!SP.draw) return; e.preventDefault(); cv.setPointerCapture(e.pointerId); SP.down=true; SP.last=spPt(e); spDot(SP.last); });
  cv.addEventListener('pointermove',function(e){ if(!SP.down) return; e.preventDefault(); var p=spPt(e); spLine(SP.last,p); SP.last=p; });
  var up=function(){ if(SP.down){ SP.down=false; spSave(); } };
  cv.addEventListener('pointerup',up); cv.addEventListener('pointercancel',up); cv.addEventListener('pointerleave',up);
  window.addEventListener('resize',function(){ if(SP.on) spFit(true); });
}
function spPt(e){ var r=SP.cv.getBoundingClientRect(); return {x:e.clientX-r.left, y:e.clientY-r.top}; }
function spStyle(){ var c=SP.ctx; c.lineCap='round'; c.lineJoin='round'; c.globalCompositeOperation=SP.erase?'destination-out':'source-over'; c.strokeStyle=c.fillStyle=(SP.color==='ink'?spInk():SP_COL[SP.color]); c.lineWidth=SP.erase?22:SP.size; }
function spDot(p){ spStyle(); var c=SP.ctx; c.beginPath(); c.arc(p.x,p.y,(SP.erase?11:SP.size/2),0,Math.PI*2); c.fill(); }
function spLine(a,b){ spStyle(); var c=SP.ctx; c.beginPath(); c.moveTo(a.x,a.y); c.lineTo(b.x,b.y); c.stroke(); }
function spSave(){ if(SP.key&&SP.cv){ try{ SP.store[SP.key]=SP.cv.toDataURL(); }catch(e){} } }
function spClear(){ if(!SP.ctx) return; SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.clearRect(0,0,SP.cv.width,SP.cv.height); SP.ctx.restore(); if(SP.key) delete SP.store[SP.key]; }
function spFit(keep){
  var wrap=document.getElementById('wrap'); if(!wrap||!SP.cv) return;
  var r=wrap.getBoundingClientRect(), top=r.top+window.scrollY, h=Math.max(wrap.scrollHeight, window.innerHeight-r.top)+40, w=document.documentElement.clientWidth;
  var old=keep&&SP.key?SP.store[SP.key]:null, dpr=window.devicePixelRatio||1;
  SP.cv.style.top=top+'px'; SP.cv.style.left='0px'; SP.cv.style.width=w+'px'; SP.cv.style.height=h+'px';
  SP.cv.width=Math.round(w*dpr); SP.cv.height=Math.round(h*dpr); SP.ctx.setTransform(dpr,0,0,dpr,0,0);
  if(old){ var im=new Image(); im.onload=function(){ SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.drawImage(im,0,0); SP.ctx.restore(); }; im.src=old; }
}
function spLoad(){ spSave(); SP.key=spKey(); spFit(false); var d=SP.key&&SP.store[SP.key]; if(d){ var im=new Image(); im.onload=function(){ SP.ctx.save(); SP.ctx.setTransform(1,0,0,1,0,0); SP.ctx.drawImage(im,0,0); SP.ctx.restore(); }; im.src=d; } }
function spUI(){
  var bar=document.getElementById('spBar'); if(!bar) return;
  bar.querySelectorAll('.sp-pen').forEach(function(b){ b.classList.toggle('on', !SP.erase && SP.draw && b.dataset.c===SP.color); });
  bar.querySelector('[data-t=erase]').classList.toggle('on', SP.erase && SP.draw);
  bar.querySelector('[data-t=scroll]').classList.toggle('on', !SP.draw);
  SP.cv.classList.toggle('passive', !SP.draw);
  var fb=document.getElementById('spFab'); if(fb) fb.classList.toggle('on',SP.on);
}
function spToggle(on){
  spBuild(); SP.on=(on===undefined)?!SP.on:on;
  document.body.classList.toggle('sp-open',SP.on); SP.cv.style.display=SP.on?'block':'none'; document.getElementById('spBar').style.display=SP.on?'flex':'none';
  if(SP.on){ SP.draw=true; SP.erase=false; spLoad(); if(typeof kbHide==='function') kbHide(); } else { spSave(); }
  spUI();
}
(function(){ var f=document.createElement('button'); f.type='button'; f.id='spFab'; f.className='sp-fab'; f.innerHTML='✏️ <span>Scratchpad</span>'; f.title='Open a scratchpad to write your working'; f.addEventListener('click',function(){ spToggle(); }); document.body.appendChild(f); })();
var _rsSP = renderSlide;
renderSlide = function(){ _rsSP(); var fab=document.getElementById('spFab'); var q=!!swTab(); if(fab) fab.style.display=q?'':'none'; if(!q && SP.on) spToggle(false); if(SP.on) setTimeout(spLoad,30); };

renderLogin();
})();
</script>
</body>
</html>
