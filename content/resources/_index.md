---
title: "Resources"
date: 2026-07-10
type: page
---

<style>
.resources-intro{
  max-width:820px;
  margin:0 auto 2.5rem auto;
  text-align:center;
}

.resources-intro p{
  font-size:1.08rem;
  line-height:1.75;
  color:var(--text-muted,#666);
}

.resources-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
  gap:1.5rem;
  margin-top:2rem;
}

.resource-card{
  background:var(--card-bg,#fff);
  border:1px solid rgba(150,120,140,.15);
  border-radius:18px;
  padding:1.7rem;
  box-shadow:0 10px 28px rgba(60,40,55,.08);
  transition:.25s ease;
  position:relative;
}

.resource-card:hover{
  transform:translateY(-5px);
  box-shadow:0 16px 34px rgba(60,40,55,.14);
}

.resource-card::before{
  content:"";
  position:absolute;
  left:0;
  top:0;
  width:6px;
  height:100%;
  border-radius:18px 0 0 18px;
  background:var(--accent);
}

.resource-card h2{
  margin-top:0;
  margin-bottom:.8rem;
  font-size:1.35rem;
}

.resource-card p{
  line-height:1.7;
  margin-bottom:1rem;
}

.resource-card ul{
  padding-left:1.2rem;
  margin-bottom:0;
}

.resource-card li{
  margin-bottom:.8rem;
}

.resource-card:nth-child(1){--accent:#b04f7a;}
.resource-card:nth-child(2){--accent:#d17d63;}
.resource-card:nth-child(3){--accent:#6d9a90;}
.resource-card:nth-child(4){--accent:#8b74b4;}

@media (prefers-color-scheme:dark){
  .resource-card{
    background:rgba(255,255,255,.04);
    border-color:rgba(255,255,255,.1);
  }

  .resources-intro p{
    color:rgba(255,255,255,.72);
  }
}
</style>

<div class="resources-intro">

This page brings together supplementary materials related to my research, including dissertation appendices, datasets, replication materials, research instruments, and teaching resources.

</div>

<div class="resources-grid">

<div class="resource-card">

## Dissertation Supplementary Materials

The following online appendices accompany my doctoral dissertation.

- Chapter 4 appendix: [Ecological inference estimations](https://surfdrive.surf.nl/files/index.php/s/T9Td9tZhzQPTb03)

- Chapter 5 appendix: [Pachakutik's appeals data and chronology of events](https://surfdrive.surf.nl/files/index.php/s/UOWVmFCeqybS4GS)

- Chapter 6 appendix: [Pachakutik at the legislature in 2002 and comparison with Izquierda Democrática](https://surfdrive.surf.nl/files/index.php/s/Gsty5wPOly58sLG), and [Izquierda Democrática and Pachakutik comparison](https://surfdrive.surf.nl/files/index.php/s/wGTY3HcnFwNXEf3)

</div>

<div class="resource-card">

## Datasets & Replication Materials

Additional datasets and replication materials will be added here as they become publicly available.

</div>

<div class="resource-card">

## Research Instruments

Survey instruments, interview protocols, coding manuals, and other research materials will be made available here when appropriate.

</div>

<div class="resource-card">

## Teaching Resources

Selected teaching materials and course resources may also be shared here.

If you would like access to any of my syllabi, just send me an email.

</div>

</div>
