---
title: Design System Components
linktitle: Components
description: Hugo is the world's fastest static website engine. It's written in Go (aka Golang) and developed by bep, spf13 and friends.
date: 2017-02-01
publishdate: 2017-02-01
categories: []
menu:
  global:
    parent: "components"
    weight: 01
weight: 01	#rem
draft: false
slug:
aliases: []
toc: false
layout: components-home
---
Find below a definition of the npower Design System components and how they all fit together.

The design system is comprised of:

#### Foundation styles

Foundation colours, shadow, curvature, transition times etc. - elements common across the entire system.

#### Atoms

Atoms are the smallest building blocks of the system. They make sense on their own and you couldn't sensibly break them down any further - for example a primary button.

#### Molecules

Molecules are more complex components consisting of atoms and potentially other molecules - for an example an address picker.

#### Organism

Organisms are the most complex components fo all. How do you know if something is an molecule or an organism? Molecules can appear more than once on a view. If it wouldn't make sense for the compoment to appear more than once (e.g. a header or a help and support section, then it's an organism).
