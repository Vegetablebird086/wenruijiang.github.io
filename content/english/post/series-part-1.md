---
author: Jiang Wenrui
title: Beijing Beijiufang railway tech co.ltd.
date: 2025-05-17
description: A brief guide to how to setup series part 1
series:
  - series-setup
---

Software developer ---- Internship


<!--more-->

1:xxx

2:xxx

```toml
[taxonomies]
    category = "categories"
    series = "series"
    tag = "tags"
```

Now we have the series enabled, the next thing we need to do is add the series name in the FrontMatter.
For our example we'll use this post and the next part.

As you can see we've set the series to `series-setup`. We also do the same in the next parts of the series.  
This end results should be a Front Matter that looks similar to this:

```md
---
author: Hugo Authors
title: Series Part 1
date: 2021-08-14
description: A brief guide to how to setup series part 1
series:
  - series-setup
---
```

Each individual post will now also show the other posts in the series under the `Posts in this Series` heading.
