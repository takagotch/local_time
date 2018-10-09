### local_time
---

https://github.com/basecamp/local_time

```coffee
//= require local-time
import LocalTime from "local-time"
LocalTime.start()

> comment.created_at

<%= local_time(comment.created_at) %>
<time data-format="%B %e, %Y %l:%M%P"
      data-local="time"
      datetime="2018-10-17T23:32:22Z">November 27, 2018-11:32pm</time>
<time data-format="%B %e, %Y %l:%M%P"
      data-local="time"
      datetime="2018-10-17T23:32:22Z"
      title="November 17, 2018 6:32pm EDT"
      data-localized="true">November 27, 2018 6:32pm</time>

<%= local_time(time) %>
<%= local_time(time, '%B %e, %Y %l:%M%P') %>
<%= local_date(time, '%B %e, %Y') %>
<%= local_time(time, format: '%B %e, %Y %l:%M%P', class: 'my-time') %>
<%= local_time(date, :long) %>

<%= local_time_ago(time) %>
<%=  %>
<%=  %>

```

