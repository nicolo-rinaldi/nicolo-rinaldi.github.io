---
layout: default
---
<div class="about">
  <img class="avatar" src="{{ '/imgs/profile.jpg' | relative_url }}" alt="{{ site.author }}">
  <h1>{{ site.author }}</h1>
  <p><em>{{ site.tagline }}</em></p>
  <p class="social">
    {% for s in site.social %}<a href="{{ s.url }}" aria-label="{{ s.name }}" target="_blank" rel="noopener"><i class="{{ s.icon }}"></i></a>{% endfor %}
  </p>
</div>

I am a Software Engineer and Data Scientist at [Sease](https://sease.io), where I work on search: Apache Solr, Opensearch/Elasticsearch, Vespa.ai, vector search, embedding models and neural reranking.

I earned my Bachelor's degree in Mathematics from the University of Bologna and a Master's degree in Data Science from the University of Padua. For my Master's thesis I built a semantic search system for the Italian language, which is where I first got into Information Retrieval.

My interest in mathematics and programming goes back to high school. Today I focus on bringing AI into retrieval systems, with a particular interest in Natural Language Processing and semantic search. I also work on taking these search engines to production, in particular OpenSearch and Apache Solr.
