---
title: Requiem: Recreating the Demo
description: Your Guide to Recreating Elements of the Requiem Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/requiem:Requiem

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Requiem can be done fairly easily. All you need is the right plugins and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Requiem Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Grav back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particle placement and settings for the various positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![](assets/requiem2.jpeg)

:   1. **Navigation** MainNav Left - Icon Menu (Particle) [1%, 13%, se]
    2. **Navigation** Menu (Particle) [1%, 38%, se]
    3. **Navigation** MainNav Right - Icon Menu (Particle) [1%, 83%, se]
    4. **Header** Promo Content (Particle) [4%, 25%, se]
    5. **Showcase** Grid Statistic (Particle) [18%, 20%, se]
    6. **Above** Promo Content (Particle) [23%, 20%, se]
    7. **Utility** Animated Block (Particle) [28%, 12%, se]
    8. **Feature** Testimonial (Particle) [44%, 12%, se]
    9. **Expanded** Info List (Particle) [54%, 13%, se]
    10. **Expanded** Grid Promo (Particle) [54%, 45%, se]
    11. **Extension** Promo Content (Particle) [67%, 13%, se]
    12. **Bottom** Grid Content (particle) [80%, 13%, se]
    13. **Footer** Info List (Particle) [91%, 13%, se]
    14. **Footer** Info List (Particle) [91%, 32%, se]
    15. **Footer** Custom HTML (Widget) [91%, 50%, se]
    16. **Footer** Contact (Particle) [91%, 70%, se]
    17. **Copyright** Branding (Particle) [99%, 13%, se]
    18. **Copyright** Copyright (Particle) [99%, 40%, se]
    19. **Copyright** To Top (Particle) [99%, 85%, se]

Particles
----- 

* Theme Particles
    - [Animated Block](particle_animatedblock.md)
    - [Block Content](particle_block.md)
    - [Contact](particle_contact.md)
    - [Content List](particle_contentlist.md)
    - [Grav Content](particle_grav.md)
    - [Grid Content](particle_gridcontent.md)
    - [Grid Promo Gallery](particle_gridpromogallery.md)
    - [Grid Statistic](particle_grid.md)
    - [Icon Menu](particle_iconmenu.md)
    - [Image Grid](particle_image.md)
    - [Info List](particle_info.md)
    - [Newsletter](particle_newsletter.md)
    - [Promo Content](particle_promocontent.md)
    - [Promo Image](particle_promoimage.md)
    - [Simple Counter](particle_simplecounter.md)
    - [Testimonial](particle_testimonial.md)
* Core Particles 
    - [Logo](http://docs.gantry.org/gantry5/particles/logo)
    - [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
    - [To Top](http://docs.gantry.org/gantry5/particles/to-top)
    - [Social](http://docs.gantry.org/gantry5/particles/social)
    - [Positions](http://docs.gantry.org/gantry5/particles/position)
    - [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
    - [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
    - [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
    - [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
    - [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)


Recreating the Front Page
-----

The front page of the Requiem demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that several layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Requiem demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

We have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Requiem has its own built-in Menu Editor which takes full advantage of Grav's menu system, taking your Grav menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Grav sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Gantry 5 > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Gantry 5** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
