# README
First test repo on Complete Ruby on Rails Developer by Jayashree Banachhode


<h1>Showing article details</h1>

<p><strong>Title: </strong><%= @article.title %></p>
<p><strong>Discription: </strong><%= @article.discription %></p>

<%= link_to 'Edit', edit_article_path(@article) %> 
<%= link_to 'Delete', article_path(@article), method: :delete, data: { confirm: "Are you sure?" }%>
<%= link_to 'Return to articles listing', articles_path %>