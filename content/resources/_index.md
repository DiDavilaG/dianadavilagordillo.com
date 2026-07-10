---
title: "Resources"
date: 2026-07-10
type: page
---

<style>
.resources-intro {
  max-width: 850px;
  margin: 0 auto 2.5rem;
  padding: 1.5rem 1.75rem;
  text-align: center;
  background: linear-gradient(
    135deg,
    rgba(176, 79, 122, 0.09),
    rgba(109, 154, 144, 0.09)
  );
  border-radius: 18px;
}

.resources-intro p {
  margin: 0;
  font-size: 1.08rem;
  line-height: 1.75;
}

.resources-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.5rem;
  margin: 2rem 0 3rem;
}

.resource-card {
  --resource-accent: #b04f7a;
  position: relative;
  padding: 1.75rem 1.75rem 1.75rem 2rem;
  background: #ffffff;
  border: 1px solid rgba(90, 60, 80, 0.13);
  border-radius: 18px;
  box-shadow: 0 8px 24px rgba(70, 45, 60, 0.08);
  overflow: hidden;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.resource-card::before {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  width: 7px;
  background: var(--resource-accent);
}

.resource-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 14px 32px rgba(70, 45, 60, 0.14);
}

.resource-card:nth-child(1) {
  --resource-accent: #b04f7a;
}

.resource-card:nth-child(2) {
  --resource-accent: #d17d63;
}

.resource-card:nth-child(3) {
  --resource-accent: #6d9a90;
}

.resource-card:nth-child(4) {
  --resource-accent: #8b74b4;
}

.resource-card h3 {
  margin-top: 0;
  margin-bottom: 0.85rem;
  font-size: 1.35rem;
}

.resource-card p {
  line-height: 1.7;
}

.resource-card ul {
  margin-bottom: 0;
  padding-left: 1.25rem;
}

.resource-card li {
  margin-bottom: 0.9rem;
  line-height: 1.65;
}

.resource-card a {
  color: var(--resource-accent);
  font-weight: 600;
  text-decoration: none;
}

.resource-card a:hover {
  text-decoration: underline;
}

@media screen and (max-width: 760px) {
  .resources-grid {
    grid-template-columns: 1fr;
  }
}

@media (prefers-color-scheme: dark) {
  .resource-card {
    background: rgba(255, 255, 255, 0.05);
    border-color: rgba(255, 255, 255, 0.12);
  }
}
</style>

<div class="resources-intro">

This page brings together supplementary materials related to my research, including dissertation appendices, datasets, replication materials, research instruments, and teaching resources.

</div>

<div class="resources-grid">

<div class="resource-card">

### Dissertation supplementary materials

The following online appendices accompany my doctoral dissertation.

- Chapter 4 appendix: [ecological inference estimations](https://surfdrive.surf.nl/files/index.php/s/T9Td9tZhzQPTb03)

- Chapter 5 appendix: [Pachakutik's appeals data and chronology of events](https://surfdrive.surf.nl/files/index.php/s/UOWVmFCeqybS4GS)

- Chapter 6 appendix: [Pachakutik at the legislature in 2002 and comparison with Izquierda Democratica](https://surfdrive.surf.nl/files/index.php/s/Gsty5wPOly58sLG), and [Izquierda Democratica and Pachakutik comparison](https://surfdrive.surf.nl/files/index.php/s/wGTY3HcnFwNXEf3)

</div>

<div class="resource-card">

### Datasets and Replication Materials

Additional datasets and replication materials will be added here as they become publicly available.

</div>

<div class="resource-card">

### Research Instruments

Survey instruments, interview protocols, coding manuals, and other research materials will be made available here when appropriate.

</div>

<div class="resource-card">

### Teaching Resources

Selected teaching materials and course resources may also be shared here. If you would like access to any of my syllabi, just send me an email!

</div>

</div>
