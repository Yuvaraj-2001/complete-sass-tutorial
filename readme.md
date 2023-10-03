HOw to create a break point  in SCSS

<style>

@mixin sm {
  @media (max-width: map-get($breakpoints, 480px)) {
    @content;
  }
}

/* How to use it? */
.responsive-test {
    /* Now if you want to add small device breakpoint, directly use it*/
    @include sm { 
    color: blue;
  }
}

</style>