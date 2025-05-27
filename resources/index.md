---
layout: page
title: Resources
permalink: /resources/
nav:
  order: 6
  tooltip: Useful links and tools
---

<!-- section break -->

<div class="content">

<style>
/* Make the intro text larger and cleaner */
.resource-intro {
  font-size: 1.25rem;
  font-weight: 500;
  line-height: 1.7;
  margin-top: 1.5rem;
  margin-bottom: 2rem;
  color: #333;
  text-align: center;
  max-width: 900px;
  margin-left: auto;
  margin-right: auto;
}

/* Full-width responsive layout */
.resource-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
  padding: 0 1.5rem;
  max-width: 1200px;
  margin: 0 auto;
}

@media (min-width: 768px) {
  .resource-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

.resource-card {
  border: 1px solid #ddd;
  border-radius: 16px;
  padding: 1.75rem 2rem;
  background-color: #fdfdfd;
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.06);
  transition: box-shadow 0.3s ease;
}

.resource-card:hover {
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.1);
}

.resource-title {
  font-size: 1.6rem;
  font-weight: 700;
  margin-bottom: 0.6rem;
  display: flex;
  align-items: center;
}

.resource-title span {
  font-size: 1.8rem;
  margin-right: 0.6rem;
}

.resource-desc {
  margin-bottom: 1.2rem;
  font-size: 1rem;
  line-height: 1.6;
  color: #444;
}

.resource-link a {
  font-weight: 600;
  color: #007acc;
  text-decoration: none;
}

.resource-link a:hover {
  text-decoration: underline;
}
</style>

<div class="resource-intro">
  Welcome to the Resources section. Below you’ll find curated materials and internal tools for our lab’s academic and technical needs.
</div>

<div class="resource-grid">

  <div class="resource-card">
    <div class="resource-title"><span>📚</span>Readings</div>
    <div class="resource-desc">
      Explore foundational and recent publications related to HCI, social computing, and health informatics.<br>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse viverra mauris eget tortor imperdiet, in placerat magna ultricies.
    </div>
    <div class="resource-link"><a href="readings">Go to Readings →</a></div>
  </div>

  <div class="resource-card">
    <div class="resource-title"><span>🧠</span>Programming LLMs</div>
    <div class="resource-desc">
      Hands-on guides, starter templates, and recommended APIs for working with large language models in health-related research.<br>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. Praesent libero. Sed cursus ante dapibus diam.
    </div>
    <div class="resource-link"><a href="programming-llms">Go to Programming LLMs →</a></div>
  </div>

  <div class="resource-card">
    <div class="resource-title"><span>📝</span>IRB</div>
    <div class="resource-desc">
      Information about Institutional Review Board (IRB) procedures, templates, and documentation used within the lab.<br>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam nec tellus a odio tincidunt auctor a ornare odio.
    </div>
    <div class="resource-link"><a href="irb">Go to IRB →</a></div>
  </div>

</div>

</div>
