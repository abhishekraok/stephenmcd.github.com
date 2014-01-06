---
layout: post
title: "SyDjango Talk: Django Admin, The Missing Manual"
slides: 34
tags:
- python
- django
- sydjango
- speaking
---

<p>Last night I gave my second <a href="http://www.meetup.com/SyDjango/">
SyDjango</a> talk, "Django Admin, The Missing Manual". There were
quite a few new faces this month, as well as a good mix of regular
Djangonauts from previous months.
</p>

<p>
In this talk I covered the <a
href="https://docs.djangoproject.com/en/dev/ref/contrib/admin/">Django
Admin</a>, some reasons people might not use it, why you should use it
anyway, and how to address some of those possible issues. I walked
through a basic project for a blog with a spartan Django Admin interface,
and the steps involved in turning it into a much more full-featured and
attractive experience for the end user.
</p>

<p>
Thanks again to all the fellow Sydney Djangonauts who came along
and made it a great night. You can find source code for this talk
on both <a href="https://github.com/stephenmcd/sydjango-damm">GitHub</a>
 and <a href="https://bitbucket.org/stephenmcd/sydjango-damm">Bitbucket</a>.</p>

<h4>Table of Contents</h4>
<ol id="toc"></ol>
<script src="/static/js/vimeo-deck.js"></script>
<script>

var vd = VimeoDeck({tocID: '#toc'});

vd.setSlide(01, '00:00', 'Welcome'); // Start
vd.setSlide(02, '00:19', 'About Me'); // About me
vd.setSlide(03, '00:24'); // Fairfax
vd.setSlide(04, '00:46'); // Mezzanine
vd.setSlide(05, '01:09'); // Django since 07
vd.setSlide(06, '01:15'); // 50 projects
vd.setSlide(07, '01:37', 'Django Admin'); // Django Admin
vd.setSlide(08, '01:39'); // Saves countless hours
vd.setSlide(09, '02:04'); // Living in the future
vd.setSlide(10, '02:23'); // Example code
vd.setSlide(11, '02:54'); // Example list
vd.setSlide(12, '03:04'); // Example change
vd.setSlide(13, '03:22', 'Why Wouldn\'t You Use It?'); // Why Wouldn't
vd.setSlide(14, '03:49'); // Looks outdated
vd.setSlide(15, '04:11'); // Too database-centric
vd.setSlide(16, '04:36'); // Hard to customise
vd.setSlide(17, '04:59', 'Let\'s Dispel These Myths'); // Dispel these myths
vd.setSlide(18, '05:16', 'Django Admin VS Custom Admin'); // Django vs custom
vd.setSlide(19, '06:28'); // Fake data
vd.setSlide(20, '06:35', 'The Missing Manual'); // Missing Manual
vd.setSlide(21, '06:39', 'Chapter 1: Use All Features'); // Chapter 1
vd.setSlide(22, '07:05'); // Full admin example code
vd.setSlide(23, '08:04'); // Full admin example list
vd.setSlide(24, '08:32', 'Chapter 2: Override Templates!'); // Chapter 2
vd.setSlide(25, '08:52'); // CSS in base_site
vd.setSlide(26, '09:48'); // Skinned list example
vd.setSlide(27, '10:34'); // Skinned change example
vd.setSlide(28, '11:25', 'Chapter 3: Singleton Admin'); // Chapter 3
vd.setSlide(29, '12:35'); // Singleton Admin example
vd.setSlide(30, '15:31', 'But Wait, One More Thing'); // But wait
vd.setSlide(31, '15:36'); // One more thing
vd.setSlide(32, '15:45'); // Links in base_site
vd.setSlide(33, '16:46'); // Dashboard example with links
vd.setSlide(34, '18:17', 'Question Time'); // Thanks

</script>

<iframe id="vimeo" src="http://player.vimeo.com/video/52318351?api=1&player_id=vimeo" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>

<script async class="speakerdeck-embed" data-id="508739b33366490002010f87" data-ratio="1.3333333333333333" src="//speakerdeck.com/assets/embed.js"></script>

<p>Table of contents and video/slides sync via <a href="https://github.com/stephenmcd/vimeo-deck">vimeo-deck</a>.</p>