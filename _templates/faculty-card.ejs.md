<% for (const item of items) { %>
<div class="member-card">
  <img src="<%= item.image %>" alt="<%= item.name %>" />
  <div>
    <h3><%= item.name %></h3>
    <p class="role"><%= item.role %></p>
    <ul>
    <% for (const bullet of item.bio) { %>
      <li><%= bullet %></li>
    <% } %>
    </ul>
    <a href="<%= item.url %>" target="_blank" rel="noopener noreferrer">
      Learn more about <%= item.name %> →
    </a>
  </div>
</div>
<% } %>
