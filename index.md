---
layout: home
---

{% if site.data.responses.active %}
{% assign num_responses = site.data.responses.active | size %}
{% if num_responses > 1 %}
Click on an active response below to be taken to that response site.

Each site can tell you about ways to get help in a disaster emergency, like a hurricane or flood. They can tell you:

* Where shelters are
* Where to get food and water
{% else %}
Click on the active response below to be taken to that response site.

It can tell you about ways to get help in a disaster emergency, like a hurricane or flood:

* Where shelters are
* Where to get food and water
{% endif %}

If you'd like to help out, you can [learn more about volunteering here]({% link about.md %}).
{% endif %}
