---
layout: page
title: Resources
permalink: /resources/
nav:
  order: 6
  tooltip: Useful links and tools
---

<style>
.resource-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
  margin-top: 2rem;
}

@media (min-width: 768px) {
  .resource-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

.resource-card {
  border: 1px solid #ddd;
  border-radius: 16px;
  padding: 1.5rem 2rem;
  background-color: #fdfdfd;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
  transition: box-shadow 0.3s ease;
}

.resource-card:hover {
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.1);
}

.resource-title {
  font-size: 1.4rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
  display: flex;
  align-items: center;
}

.resource-title span {
  font-size: 1.6rem;
  margin-right: 0.6rem;
}

.resource-desc {
  margin-bottom: 1rem;
  font-size: 0.95rem;
  line-height: 1.6;
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

Welcome to the Resources section. Below you'll find curated materials and internal tools for our lab's academic and technical needs.

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
