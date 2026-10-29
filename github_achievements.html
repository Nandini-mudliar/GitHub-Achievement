<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GitHub Achievements</title>
<style>
  :root {
    --bg: #0d1117;
    --panel: #161b22;
    --panel-alt: #0d1117;
    --border: #30363d;
    --text: #f0f6fc;
    --muted: #c9d1d9;
    --link: #58a6ff;
    --accent: #f78166;
  }
  * { box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  body {
    margin: 0;
    background: var(--bg);
    color: var(--text);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Arial, sans-serif;
    font-size: 14px;
    line-height: 1.55;
  }
  .top-line { height: 2px; background: linear-gradient(90deg, var(--accent) 0 102px, var(--border) 102px); }
  main { max-width: 1120px; margin: 0 auto; padding: 22px 24px 56px; }
  h1, h2 { line-height: 1.25; border-bottom: 1px solid var(--border); padding-bottom: 10px; margin: 0 0 22px; }
  h1 { font-size: clamp(25px, 3vw, 34px); }
  h2 { font-size: clamp(21px, 2.4vw, 27px); margin-top: 42px; }
  h1 .emoji, h2 .emoji { margin-right: 8px; }
  p { margin: 8px 0; }
  a { color: var(--link); }
  .intro { font-size: 13px; font-weight: 600; margin-bottom: 24px; }
  .table-wrap { width: 100%; overflow-x: auto; margin: 18px 0 28px; border: 1px solid var(--border); }
  table { border-collapse: collapse; width: 100%; min-width: 690px; }
  th, td { border: 1px solid var(--border); padding: 8px 10px; text-align: center; vertical-align: middle; }
  th { font-weight: 750; background: #0d1117; }
  tbody tr:nth-child(even) { background: var(--panel); }
  .badge-img { width: 92px; height: 92px; object-fit: contain; display: block; margin: 0 auto; }
  .badge-img.small { width: 58px; height: 58px; }
  .name { min-width: 125px; }
  .how { min-width: 190px; max-width: 270px; }
  .needed { min-width: 390px; }
  .tiers { display: grid; grid-template-columns: repeat(4, minmax(65px, 1fr)); border: 1px solid var(--border); }
  .tiers.one { display: inline-grid; grid-template-columns: minmax(95px, 1fr); min-width: 100px; }
  .tier { display: flex; flex-direction: column; align-items: center; justify-content: center; min-width: 0; }
  .tier:not(:last-child) { border-right: 1px solid var(--border); }
  .tier-label { width: 100%; border-bottom: 1px solid var(--border); padding: 6px 2px; font-weight: 800; }
  .tier-art { padding: 5px 0; }
  .tier-count { width: 100%; border-top: 1px solid var(--border); padding: 7px 2px; }
  .tier-art img { width: 58px; height: 58px; object-fit: contain; }
  .placeholder { color: var(--muted); }
  .skin-table { min-width: 520px; }
  .skin-table .badge-img { width: 48px; height: 48px; }
  .skin-table .skin-cell { padding: 3px; }
  .skin-table .skin-cell img { width: 44px; height: 44px; object-fit: contain; }
  .skin-emojis { display: flex; justify-content: space-around; gap: 8px; }
  .skin-emojis span { min-width: 24px; }
  .highlights table { min-width: 550px; }
  .highlights td:first-child { width: 52px; }
  .old-badges .badge-img { width: 100px; height: 100px; }
  .old-badges .needed { min-width: 100px; }
  .old-badges .tiers { grid-template-columns: minmax(85px, 1fr); }
  .old-badges .tier-art img { width: 52px; height: 52px; }
  @media (max-width: 650px) {
    main { padding: 18px 12px 40px; }
    .badge-img { width: 72px; height: 72px; }
    h1 { font-size: 25px; }
    h2 { font-size: 21px; }
  }
</style>
</head>
<body>
<div class="top-line"></div>
<main>
  <h1><span class="emoji">📜</span>Achievement List <span class="emoji">📜</span></h1>
  <div class="table-wrap">
    <table>
      <thead><tr><th>Badge</th><th>Name</th><th>How to get</th><th>Needed amount</th></tr></thead>
      <tbody id="achievements"></tbody>
    </table>
  </div>

  <section>
    <h2>👋 Achievement Skin Tone 👋</h2>
    <div class="intro">
      <p>Some achievements’ appearance depends on your Emoji Skin Tone Preference.</p>
      <p>You can change your preferred Skin Tone by going to <a href="https://github.com/settings/appearance" target="_blank" rel="noreferrer">appearance settings</a>.</p>
    </div>
    <div class="table-wrap">
      <table class="skin-table">
        <thead><tr><th>Badge</th><th>Name</th><th>Skin Tone Versions</th></tr></thead>
        <tbody id="skin-tones"></tbody>
      </table>
    </div>
  </section>

  <section class="highlights">
    <h2>✨ Highlights Badges ✨</h2>
    <div class="table-wrap">
      <table>
        <thead><tr><th>Badge</th><th>Name</th><th>How to get</th></tr></thead>
        <tbody id="highlights"></tbody>
      </table>
    </div>
  </section>

  <section class="old-badges">
    <h2>❌ Badges no longer earnable ❌</h2>
    <div class="table-wrap">
      <table>
        <thead><tr><th>Badge</th><th>Name</th><th>How to get</th><th>Needed amount</th></tr></thead>
        <tbody id="old-badges"></tbody>
      </table>
    </div>
  </section>
</main>
<script>
/*
  Badge art: these are emoji-based illustrations so the page works as a
  standalone HTML file. Replace any badge's `art` with a direct image URL
  to use the original artwork.
*/
const badgeArt = {
  heart: "💗", wizard: "🧙", starstruck: "🤩", quickdraw: "🤠",
  pair: "🫛", shark: "🦈", brain: "🧠", yolo: "🎉",
  sponsor: "💟", mars: "🚀", arctic: "🏔️"
};

function artData(emoji, background = "linear-gradient(135deg,#f6a5cf,#6b8cff)") {
  const svg = `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100">
    <defs><linearGradient id="g" x1="0" y1="0" x2="1" y2="1"><stop stop-color="#ffffff"/><stop offset="1" stop-color="#c6d3ff"/></linearGradient></defs>
    <circle cx="50" cy="50" r="47" fill="${background}" stroke="#f0f6fc" stroke-width="5"/>
    <circle cx="50" cy="50" r="38" fill="url(#g)" opacity=".2"/>
    <text x="50" y="65" font-size="49" text-anchor="middle" font-family="Arial, sans-serif">${emoji}</text>
  </svg>`;
  return "data:image/svg+xml;charset=UTF-8," + encodeURIComponent(svg);
}
function badgeImage(emoji, bg, small = false, alt = "") {
  return `<img class="badge-img ${small ? "small" : ""}" src="${artData(emoji,bg)}" alt="${alt || emoji}">`;
}
const tierInfo = [
  { name: "DEFAULT", color: "linear-gradient(135deg,#efb6d6,#b9a0ff)" },
  { name: "BRONZE", color: "linear-gradient(135deg,#f7d6b0,#b77b4b)" },
  { name: "SILVER", color: "linear-gradient(135deg,#f4f7f8,#8c959f)" },
  { name: "GOLD", color: "linear-gradient(135deg,#fff3a3,#d5b526)" }
];
const achievements = [
  { name:"Heart On Your Sleeve", art:badgeArt.heart, bg:"#e78fbc", how:"(???)", counts:["(?)","(?)","(?)","(?)"], tiers:true },
  { name:"Open Sourcerer", art:badgeArt.wizard, bg:"#a88bff", how:"(???)", counts:["(?)","(?)","(?)","(?)"], tiers:true },
  { name:"Starstruck", art:badgeArt.starstruck, bg:"#f0a36c", how:"Created a repository that has many stars", counts:["16","128","512","4096"], tiers:true },
  { name:"Quickdraw", art:badgeArt.quickdraw, bg:"#ed9b56", how:"Gitty up!<br>(closed an issue / pull request within 5 minutes of opening)", counts:["1"], tiers:false },
  { name:"Pair Extraordinaire", art:badgeArt.pair, bg:"#9cdb82", how:'<a href="https://docs.github.com/en/pull-requests/collaborating-with-pull-requests">Coauthored commits</a> on merged pull request', counts:["1","10","24","48"], tiers:true },
  { name:"Pull Shark", art:badgeArt.shark, bg:"#2865d8", how:"Opened a pull request that has been merged", counts:["2","16","128","1024"], tiers:true },
  { name:"Galaxy Brain", art:badgeArt.brain, bg:"#7452c9", how:"Answered a discussion (got an accepted answer)", counts:["2","8","16","32"], tiers:true },
  { name:"YOLO", art:badgeArt.yolo, bg:"#f1a7c7", how:"Merged a pull request without a review", counts:["1"], tiers:false },
  { name:"Public Sponsor", art:badgeArt.sponsor, bg:"#f3d9a0", how:'Sponsored an open source contributor through <a href="https://github.com/sponsors">GitHub Sponsors</a>', counts:["1"], tiers:false }
];
const oldBadges = [
  { name:"Mars 2020 Contributor", art:badgeArt.mars, bg:"#563078", how:'Contributed code to a repository used in the <a href="https://mars.nasa.gov/mars2020/">Mars 2020 Helicopter Mission</a>', count:"1" },
  { name:"Arctic Code Vault Contributor", art:badgeArt.arctic, bg:"#2e6a9d", how:'Contributed code to a repository in the <a href="https://archiveprogram.github.com/">2020 GitHub Archive Program</a>', count:"1" }
];
const highlights = [
  ["☆","Pro",'Use <a href="https://github.com/features">GitHub Pro</a>'],
  ["⚙","Developer Program Member",'Be a registered member of the <a href="https://developer.github.com/program/">GitHub Developer Program</a>'],
  ["♙","Security Bug Bounty Hunter",'Helped out hunting down security vulnerabilities at <a href="https://bounty.github.com/">GitHub Security</a>'],
  ["⚑","GitHub Campus Expert",'Participate in the <a href="https://education.github.com/experts">GitHub Campus Program</a>'],
  ["⛨","Security advisory credit",'Have your security advisory submitted to the <a href="https://github.com/advisories">GitHub Advisory Database</a> accepted']
];

function tierMarkup(emoji, bg, counts) {
  const items = counts.map((count, i) => {
    const tier = tierInfo[i];
    return `<div class="tier">
      <div class="tier-label">${tier ? tier.name : "DEFAULT"}</div>
      <div class="tier-art">${badgeImage(emoji, tier ? tier.color : bg, true)}</div>
      <div class="tier-count">${count}</div>
    </div>`;
  }).join("");
  return `<div class="tiers ${counts.length === 1 ? "one" : ""}">${items}</div>`;
}
function renderAchievements() {
  document.getElementById("achievements").innerHTML = achievements.map(item => `
    <tr>
      <td>${badgeImage(item.art,item.bg,false,item.name)}</td>
      <td class="name">${item.name}</td>
      <td class="how">${item.how}</td>
      <td class="needed">${tierMarkup(item.art,item.bg,item.counts)}</td>
    </tr>`).join("");
}
function renderSkinTones() {
  const skin = [
    { name:"Starstruck", art:badgeArt.starstruck, bg:"#f0a36c" },
    { name:"Quickdraw", art:badgeArt.quickdraw, bg:"#ed9b56" }
  ];
  const tones = ["👋","👋🏻","👋🏼","👋🏽","👋🏾","👋🏿"];
  document.getElementById("skin-tones").innerHTML = skin.map(item => `
    <tr>
      <td>${badgeImage(item.art,item.bg)}</td>
      <td>${item.name}</td>
      <td>
        <div class="skin-emojis">${tones.map(t => `<span>${t}</span>`).join("")}</div>
        <div class="skin-emojis">${tones.map((t,i) => `<span class="skin-cell">${badgeImage(item.art,item.bg,true,item.name + " skin tone " + (i+1))}</span>`).join("")}</div>
        <div class="skin-emojis">${tones.map(t => `<span>${t}</span>`).join("")}</div>
      </td>
    </tr>`).join("");
}
function renderHighlights() {
  document.getElementById("highlights").innerHTML = highlights.map(([icon,name,how]) =>
    `<tr><td>${icon}</td><td>${name}</td><td>${how}</td></tr>`).join("");
}
function renderOldBadges() {
  document.getElementById("old-badges").innerHTML = oldBadges.map(item => `
    <tr>
      <td>${badgeImage(item.art,item.bg)}</td><td>${item.name}</td><td>${item.how}</td>
      <td class="needed">${tierMarkup(item.art,item.bg,[item.count])}</td>
    </tr>`).join("");
}
renderAchievements();
renderSkinTones();
renderHighlights();
renderOldBadges();
</script>
</body>
</html>
