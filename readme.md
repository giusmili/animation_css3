# Animation css3

Ce cours est dédié aux animations avec la css3

```css
figure .logo-2{
    animation: logo_2 1s linear 8 alternate;
    animation-delay: 10s;
}
@keyframes logo_2 {
    0%{
        transform: scale(1);
    }
    20%{
        transform: scale(2);
    }
    40%{
        transform: rotate(-360deg);
    }
    50%{
        transform: translateY(-4rem);
    }
    60%{
        transform: rotate(360deg);
    }
}

```
