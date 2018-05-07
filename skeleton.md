What happens to the layout when you resize the screen to less than 550 px. How do you think that works?
    The boxes in the page's boxdesign re-align in a single column in a mobile friendly format.
    You can see in the Skeleton CSS custom code how different styles are added with an @media command as seen here...
        /* Bigger than 550 */
        @media (min-width: 550px)
    
    Code following this applies to the page when the page is being viewed on a browser/screen 550px or smaller.