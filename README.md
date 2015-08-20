[![Build Status](https://travis-ci.org/chikeichan/Trio.svg?branch=dev)](https://travis-ci.org/chikeichan/Trio)
[![Coverage Status](https://coveralls.io/repos/chikeichan/Trio/badge.svg?branch=dev&service=github)](https://coveralls.io/github/chikeichan/Trio?branch=dev)
<br>
[![Stories in Ready](https://badge.waffle.io/chikeichan/Trio.svg?label=ready&title=Ready)](http://waffle.io/chikeichan/Trio)
# Trio

## Main Classes
- Factory reference Resource(id/s)
- Service defines interactions between factory and component
- Component renders UI/UX, register custom element

## Singletons
- Resources interacts with BE and cache results.
- Modules controls import and export of js files, cache results.
- Stylizer compiles CSS, stores variable and mixins
- Renderer compiles HTML, stores templates and helper funnctions

## Design principles
- Less setting and getting
- Small, reusable components
- Less subclassing
- Event-based Data-binding
