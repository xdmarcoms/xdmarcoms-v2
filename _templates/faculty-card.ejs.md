<% for (var i = 0; i < items.length; i++) { var item = items[i]; %><div class="member-card">
<img src="<%= item.image %>" alt="<%= item.name %>">
<div class="member-info">
<h3><%= item.name %></h3>
<p class="role"><%= item.role %></p>
<ul><% for (var j = 0; j < item.bio.length; j++) { %><li><%= item.bio[j] %></li><% } %></ul>
<a href="<%= item.url %>" target="_blank" rel="noopener noreferrer">Learn more →</a>
</div>
</div>
<% } %>
