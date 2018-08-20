---
layout: default
---

{% capture intro %}
# Join our Community

The Tendrl project is a community of developers who aim to solve the central management problems for software defined storage. Shirshendu Mukherjee is the architect. Nishanth Thomas lead the development. There are also contributors from the [Gluster](http://www.gluster.org) communities and the aim is to leverage existing successful open source projects that have solved key aspects of the problems we aim to address.
{% endcapture %}

{% capture the-rest %}

## Find Out More

To get involved, please join the discussion on either IRC (internet relay chat) or on the mailing list.

  * Find us on irc.freenode.net #tendrl-devel and [Gitter](https://gitter.im/Tendrl/tendrl-devel)
  * Subscribe to the [tendrl-devel mailing list](https://www.redhat.com/mailman/listinfo/tendrl-devel)
  * Follow our development on [our GitHub](https://github.com/Tendrl) and the issue tracker of each
  * module.
  * Participate in development planning on [our GitHub](https://github.com/Tendrl) within each module

{% endcapture %}

<div class="frontpage">
  <div class="mission mission-text intro">{{ intro | markdownify }}</div>
  <div>{{ the-rest | markdownify }}</div>
</div>

