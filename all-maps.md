---
title: The Maps
layout: allmaps
description: 'Explore our neighborhood maps'
image: assets/images/hydepark.jpg
nav-menu: true
show_tile: true
---

.tiles2 {
                    @include vendor('align-items', 'center');
            @include vendor('display', 'flex');
            @include vendor('transition', (
                'transform 0.25s ease',
                'opacity 0.25s ease',
                'filter 1s ease',
                '-webkit-filter 1s ease'
            ));
            @include padding(4em, 4em);
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            cursor: default;
            height: 40vh;
            max-height: 40em;
            min-height: 23em;
            overflow: hidden;
            position: relative;
            width: 30% !important;
 
    }
 