# Slideshow

## Example of code slide

```html
<pre>
<code>
<% File.readlines("../step-1/app.rb", chomp: true).each.with_index(1) do |line, line_no| %>
<span class="line_no"><%= line_no %></span> <%= line.chomp %>
<% end %>
</code>
</pre>
```
