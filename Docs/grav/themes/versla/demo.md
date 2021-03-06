---
title: Versla: Recreating the Demo
description: Your Guide to Recreating Elements of the Versla Demo for Grav
breadcrumb: /grav:Grav/!themes:Themes/versla:Versla

---

Introduction
-----

Recreating features of the demo site used to show off some of the more interesting aspects of Versla can be done fairly easily. All you settings, and you should be able to reproduce most (if not all) of the elements found in our demo site.

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Versla Theme.

Keep in mind that a lot of the detail that makes our demos look so good is the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Grav back end. We have added most of these elements into the theme's core files in order to make them easily accessible without having to edit any code.

>> NOTE: We recommend downloading a copy of the RocketLauncher whenever you are attempting to replicate demo content. This allows easy referencing, whether on your site in a subdirectory, development server, or on a localhost. This will allow you to see all of our demo content in context, making it easier to replicate.

Home Particles
-----

Below, you will find the particles as they appear on the front page of our demo. These can all be found and edited via Gantry 5 > Home > Layout in our RocketLauncher package.

![](assets/versla2.jpeg)

:   1. **Navigation** Logo (Particle) [1%, 13%, se]
    2. **Navigation** Menu (Particle) [1%, 27%, se]
    3. **Navigation** Shopping Cart (Particle) [1%, 75%, se]
    4. **Slideshow** Simple Content (Particle) [5%, 27%, se]
    5. **Slideshow** Owl Showcase (Particle) [8%, 3%, se]
    6. **Header** Product List (Particle) [20%, 10% se]
    7. **Above** Info List (Particle) [50%, 15%, se]
    8. **Feature** Owl Preview (Particle) [60%, 15%, se]
    9. **Expanded** Simple Content (Particle) [73%, 5%, se]
    10. **Expanded** Grav Articles (Particle) [73%, 52%, se]
    11. **Footer** Simple Content (Particle) [90%, 12%, se]
    12. **Footer** Newsletter (Particle) [90%, 62%, se]
    13. **Copyright** Bottom Menu (Particle) [95%, 10%, se]
    14. **Copyright** Branding (Particle) [95%, 70%, se]

Not pictured here is an **Offcanvas** position which hosts the mobile menu. You can find out more about the Offcanvas position in the [Gantry 5 documentation](http://docs.gantry.org/gantry5/configure/layout-manager#offcanvas-section).

Particles
-----

Here is a list of particles that are available in Versla, as well as links to documentation to help you get started:

* Theme Particles
    * [Owl Carousel](particle_owl.md)
    * [Shopping Cart](particle_shopping.md)
    * [Product List](particle_productlist.md)
    * [Video and Video Grid](particle_video.md)
    * [Content Tabs](particle_tabs.md)
    * [Pricing Table](particle_pricing.md)
    * [Grav Articles](particle_grav.md)
    * [Block Content](particle_block.md)
    * [Info List](particle_info.md)
    * [Simple Content](particle_simple.md)
    * [Simple Menu](particle_simplemenu.md)
    * [Image Grid](particle_image.md)

Core Gantry Particles (Documented on [Gantry's Website](http://gantry.org)):

* [Logo](http://docs.gantry.org/gantry5/particles/logo)
* [Menu](http://docs.gantry.org/gantry5/particles/menu-control)
* [To Top](http://docs.gantry.org/gantry5/particles/to-top)
* [Social](http://docs.gantry.org/gantry5/particles/social)
* [Positions](http://docs.gantry.org/gantry5/particles/position)
* [Spacer](http://docs.gantry.org/gantry5/particles/spacer)
* [Mobile Menu](http://docs.gantry.org/gantry5/particles/mobile-menu)
* [Custom HTML](http://docs.gantry.org/gantry5/particles/custom-html)
* [Page Content](http://docs.gantry.org/gantry5/particles/page-content)
* [System Messages](http://docs.gantry.org/gantry5/particles/system-messages)

Recreating the Front Page
-----

The front page of the Versla demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the theme. It is because of this that severa layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Versla demo.

Home Page Layout Presets
-----

![Layout Presets](assets/layout_presets.jpeg)

We have included a layout preset for the home page within the theme if needed. The **Home - Particles** preset includes all of the particle-based home page demo content so you can hit the ground running with a copy of our demo to work from loaded directly into the layout.

You can access the presets by selecting **Load** in the **Layout Manager**.

Menu Editor
-----

![](assets/menu_1.jpeg)

Versla has its own built-in Menu Editor which takes full advantage of Grav's menu system, taking your Grav menus and enhancing them before passing them to visitors on the front end. Any changes made in the Menu Editor will only affect the way it appears to the visitor, and not the way Grav sees or uses it.

You can access the Gantry Menu Editor by navigating to **Admin > Gantry 5 > Menu**. You can find out more about navigating and using the Gantry Menu Editor [in our documentation](http://docs.gantry.org/gantry5/configure/menu-editor).

Assignments
-----

![](assets/assignments_1.jpeg)

Assignments are also managed in the Gantry Administrator. This administrative panel enables you to assign theme outlines to specific menu items, pages, and other areas of your site. By navigating to **Admin > Gantry 5** and selecting an outline other than the **Base Outline**, you will be able to assign that outline by navigating to the **Assignments** panel. Simply switch any menu items to on (green) that you want to assign that outline to. In the case of the Home page, this would be your default Home page in your default (main) menu.
