---
layout: sn
category: "module"
title: "Database Views"
---

<h3 id="requirements">
  Exemple
</h3>

<p>Configuring View Table form : Left join</p>

<pre>
  <code>
    Service Offering [service_offering] (so)
    Service Availability [service_availability] (sa) where_clause so_sys_id = sa_service_offering Left join true
  </code>
</pre>
