---
layout: post
title: Code syntax highlighting test
tags: [code syntax, highlighting]
---

{{ page.title }}
================

<p class="meta">26 December 2013</p>

```
void DebugOutputSystem( Fartemis::Entity& a_entity ) {
    TransformComponent* transform = a_entity.RequestComponent< TransformComponent >();
    
    if ( transform != nullptr ) {
        std::cout << transform->x << ", " << transform->y << '\n';
    };
};
```
