---
name: Home
assetId: 5344d2f8-a0da-4007-977b-9cea0f1c12fb
type: page
---

{% table
    data="demo_daily_orders"
%}

{% dimension
    value="category"
    link="concat('/category-detail?category_filter=\"', category,'\"')"
/%}

{% /table %}


[New Link](/aa/category-detail)