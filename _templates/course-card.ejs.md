<% for (const item of items) { %>
<div class="course-block">
  <h3><%= item.name %></h3>
  <p><%= item.description %></p>
  <p class="objective"><strong>Objective:</strong> <%= item.objective %></p>
</div>
<% } %>
