---
title: "Content Placeholder"
---

{{< gather dest="foo" >}}

(1) This is some content.

{{< /gather >}}

{{< gather dest="foo" >}}

(2) This is some more content.

{{< /gather >}}

<p style="border-style: solid; border-width: 1px">

{{< dump source="foo" >}}

</p>
