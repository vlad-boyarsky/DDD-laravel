<h1>DDD-laravel</h1>
<a href="https://en.wikipedia.org/wiki/Domain-driven_design" target="_blank">DDD (Domain-Driven Design)</a> for Laravel project &amp; Onion Architecture

<p>Just remember DDD, this is just a recommendation.</p>
</hr>
<h2>1.Domain Experts</h2>
<ul>
<li>They may miss the most obvious details.</li>
<li>Know how a domain and its business services work.</li>
<li>They are often not technical specialists.</li>
</ul>
</hr>
<h2>2.Our Tasks</h2>
<ul>
<li>We must get only main info for our tasks. And closing the eyes for not important information from business.</li>
<li>We must get main info and knowledge about domain.</li>
<li>We must learn to explain all technical moments to domain-business.(So we must learn to explain all the technical part on their language).</li>
</ul>
</hr>
<h2>IMPORTANT</h2>
<ul>
<li>In your team you must have general terminology.</li>
<li>Ask many questions to domain-business for more understanding of a plan.</li>
</ul>
<pre>
<p><i>At first of all describe objects and their interaction.</i></p>
<p><i>After that go to the controllers and models etc.</i></p>
</pre>
<hr>
<h2>🧅 Onion Principle 🧅</h2>
<h3>1. Domain Layer</h3>
<ul>
<li>General understanding of the subject area (domain).</li>
</ul>
-
<h3>AGGREGATIONS</h3>
<b>[</b>
<h3>Entity</h3>
<ul>
<li>Describes individually existing domain elements.</li>
</ul>
<h3>VO (Value Object)</h3>
<ul>
<li>Carries a collection sense. (<i>example: Products quantity</i>).</li>
</ul>
<b>]</b>
<hr>
<h3>2. Repository Interface </h3>
<ul>
<li>Realisation work with database.</li>
</ul>
<hr>
<h3>3. Domain Service Interface </h3>
<ul>
<li>Interfaces for operation with domain model.</li>
</ul>
<hr>
<h3>4. Infrastructure layer </h3>
<ul>
<li>Realisation of our repositories and services.</li>
</ul>
<hr>
<h3>DTO (Data Transfer Object)</h3>
<ul>
<li>NO Logic.</li>
<li>Required to transfer data between layers in application.</li>
</ul>