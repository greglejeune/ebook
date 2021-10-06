---
layout: sn
category: "module"
title: "Database Views"
---

<h2>
  Exemple
</h2>

<p>Database View with Service Offering & Service Availability</p>

<p><strong>Configure > Form Layout</strong> : Configuring View Table form on View Table : Left join</p>

<p><strong>Configure > Security Rules</strong> : Add Access Control on read operation on Service Availability</p>

<pre>
  <code>
    Service Offering [service_offering] (so)
    
    Service Availability [service_availability] (sa) 
    where_clause so_sys_id = sa_service_offering Left join true
  </code>
</pre>

<h3>
  Filter on specific date
</h3>

<pre>
  <code>
    &&  sa_start >= '2021-09-30 22:00:00'
  </code>
</pre>
