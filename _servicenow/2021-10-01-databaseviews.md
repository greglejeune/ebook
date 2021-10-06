---
layout: sn
category: "module"
title: "Database Views"
---

<h3 id="requirements">
  Exemple
</h3>

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
